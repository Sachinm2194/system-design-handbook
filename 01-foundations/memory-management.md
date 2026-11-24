<h1 style="color: #3673C1;">5. Memory Management</h1>

<h2 style="color: #3673C1;">5.1 Virtual Memory</h2>

**Definition:**

Virtual memory is a technique where the operating system gives each program its own separate memory space, even though multiple programs share the same physical RAM.

**Real-Time Example:**

Imagine opening three applications:

- Chrome
- VS Code
- Spotify

Each application feels like it has its own memory space.

But actually, the operating system manages and maps their memory to physical RAM.

**Key Points:**

- Each process gets its own virtual address space.
- The operating system manages memory mapping.
- Multiple programs can run without directly managing each other's memory.

---

<h2 style="color: #3673C1;">5.2 Paging</h2>

**Definition:**

Paging is a memory management technique that divides virtual memory into small fixed-size blocks called **pages** and physical RAM into blocks called **frames**.

The operating system maps pages to frames.

### Real-Time Example 📚

Imagine a book with 100 pages.

- You divide the book into smaller pages.
- You can store those pages in different locations.
- When needed, you find the required page.

---

<h2 style="color: #3673C1;">5.3 Page Cache</h2>

**Definition:**

Page cache is memory (RAM) used by the operating system to store recently accessed file data so it can be accessed faster next time.

### Real-Time Example 📖

Imagine reading a book.

- You read a page.
- You keep that page nearby.
- When you need it again, you don't search for the book from the beginning.

Similarly, the OS keeps recently accessed file data in RAM instead of reading it from disk again.

---

<h2 style="color: #3673C1;">5.4 Memory-Mapped Files</h2>

**Definition:**

Memory-mapped files allow a program to access file data directly through memory (virtual memory), instead of using traditional read and write operations.

### Real-Time Example 📄

Imagine opening a large PDF file.

- Instead of loading the entire file at once, the OS maps the file into memory.
- You access the parts you need.
- The OS loads the required data into RAM when needed.

---

<h2 style="color: #3673C1;">5.5 Zero-Copy</h2>

**Definition:**

Zero-copy is a technique that reduces unnecessary copying of data between memory buffers, saving CPU work and improving performance.

### Real-Time Example 📦

Imagine sending a large video file over the internet:

- Normally, data may be copied several times between memory buffers.
- With zero-copy, the OS avoids some of these extra copies.
- This makes data transfer more efficient.

---
