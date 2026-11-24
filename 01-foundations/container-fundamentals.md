<h1 style="color: #3673C1;">7. Container Fundamentals</h1>

<h2 style="color: #3673C1;">7.1 Containers</h2>

**Definition:**

Containers are lightweight environments that package an application with the files and dependencies it needs to run.

**Real-Time Example:**

- You build a Python application.
- You package it with Python and its required libraries in a container.
- It can run consistently on different computers that support containers.

**Remember:** Containers help applications run consistently in different environments.

---

<h2 style="color: #3673C1;">7.2 cgroups</h2>

**Definition:**

cgroups (control groups) are a Linux feature that controls how much CPU, memory, and other resources a group of processes can use.

**Real-Time Example:**

- You run a container with a memory limit of 512 MB.
- cgroups help prevent it from using more than its allowed memory.

**Remember:** cgroups control how many resources a container can use.

---

<h2 style="color: #3673C1;">7.3 Namespaces</h2>

**Definition:**

Namespaces are a Linux feature that gives processes separate views of system resources, making them feel isolated from other processes.

**Real-Time Example:**

- You run two containers on one computer.
- Each container can have its own process list and network view.
- Processes in one container don't automatically see processes in the other.

**Remember:** Namespaces separate what processes can see.

---

<h2 style="color: #3673C1;">7.4 Resource Isolation</h2>

**Definition:**

Resource isolation means keeping one application's resource usage separate or limited so it doesn't interfere too much with other applications.

**Real-Time Example:**

- Container A runs a website.
- Container B runs a database.
- You limit Container A's CPU and memory so it cannot consume all the resources needed by Container B.

**Remember:** Resource isolation helps containers share one computer without one taking over all its resources.

---