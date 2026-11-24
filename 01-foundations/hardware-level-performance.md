<h1 style="color: #3673C1;">8. Hardware-Level Performance</h1>

<h2 style="color: #3673C1;">8.1 NUMA Architecture</h2>

**Definition:**

NUMA (Non-Uniform Memory Access) is a computer architecture where each CPU has faster access to its nearby RAM than to RAM connected to another CPU.

**Real-Time Example:**

- Imagine a computer with two CPUs.
- Each CPU has its own nearby memory.
- CPU 1 can access its nearby RAM faster than CPU 2's RAM.
- Accessing distant memory may take more time.

**Remember:** NUMA means memory access speed depends on which CPU accesses the memory.

---

<h2 style="color: #3673C1;">8.2 Hardware Effects on Application Performance</h2>

**Definition:**

Application performance depends not only on code but also on hardware components like the CPU, RAM, disk, and network.

**Real-Time Example:**

Imagine opening a large application:

- **CPU:** A slower CPU may take longer to process tasks.
- **RAM:** Low RAM can cause slowdowns when many applications are open.
- **Disk:** An SSD loads files faster than a traditional HDD.
- **Network:** A slow network delays online requests.

**Remember:** Good software performance depends on both efficient code and capable hardware.

---