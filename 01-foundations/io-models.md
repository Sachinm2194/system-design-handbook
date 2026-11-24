## 4.1 Blocking and Non-Blocking I/O

### What is I/O?

I/O stands for **Input/Output**.

It means communication between a program and external resources, such as:

- Reading a file.
- Receiving data from a network.
- Sending data to a server.
- Reading user input.

### 1. Blocking I/O

**Blocking I/O** means a thread waits until the I/O operation completes before continuing its work.

**Real-Time Example: Bank Queue 🏦**

Imagine standing in a bank queue. You wait until your transaction is completed before doing anything else.

### 2. Non-Blocking I/O

**Non-Blocking I/O** means a thread doesn't have to wait for an I/O operation to complete. It can continue doing other work and check for the result later.

**Real-Time Example: Restaurant 🍽️**

You order food at a restaurant, get a token, and do other things while your food is being prepared.

### Difference Between Blocking and Non-Blocking I/O

| Blocking I/O | Non-Blocking I/O |
|---|---|
| Waits for completion. | Doesn't wait. |
| Thread can remain idle. | Thread can do other work. |
| Simpler to understand. | More complex to manage. |

---

## 4.2 Asynchronous I/O

**Asynchronous I/O** means starting an I/O operation and continuing other work without waiting. When the operation finishes, you receive a notification or callback with the result.

### Real-Time Example 🍕

You order food using an app.

- Place your order.
- Continue watching a movie.
- When the food is ready, you receive a notification.
---

## 4.3 epoll

### What is epoll?

`epoll` is a Linux mechanism that monitors multiple file descriptors (such as network sockets) to check which ones are ready for reading or writing.

It helps programs handle many connections efficiently without continuously checking every connection.

### Real-Time Example 📞

Imagine a receptionist handling 100 phone lines.

- Instead of continuously checking every phone.
- The receptionist gets notified when someone calls.
- The receptionist handles only the active calls.

---

## 4.4 io_uring

### What is io_uring?

`io_uring` is a Linux I/O interface that allows applications to submit I/O requests and receive completion notifications efficiently, often without blocking threads.

### Real-Time Example 📦

Imagine ordering 10 products online.

- You submit all 10 orders.
- The system processes them.
- You receive notifications as each order is completed.

Similarly, `io_uring` allows applications to submit multiple I/O operations and collect their completion results.

---
## 4.5 Event Loops

### What is an Event Loop?

An **Event Loop** continuously checks for events or completed tasks and executes the corresponding callbacks without blocking the entire program.

### Real-Time Example 🍽️

Imagine a restaurant waiter.

- Takes an order from Customer A.
- Takes an order from Customer B.
- Checks which order is ready.
- Serves the completed order.

The waiter doesn't wait beside one customer until their food is ready.

Similarly, an event loop handles multiple tasks efficiently.

---