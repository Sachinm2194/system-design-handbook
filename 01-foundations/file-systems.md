<h1 style="color: #3673C1;">6. File Systems and Durability</h1>

<h2 style="color: #3673C1;">6.1 File Systems</h2>

**Definition:**

A file system is the way an operating system organizes, stores, and manages files on a storage device.

**Real-Time Example:**

- You save a photo on your laptop.
- The file system keeps track of the photo's name, location, size, and storage space.
- Later, you can find and open it.

**Remember:** A file system organizes files so the OS can store and find them.

---

<h2 style="color: #3673C1;">6.2 fsync</h2>

**Definition:**

`fsync()` is a system call that asks the OS to write a file's modified data to storage, such as an SSD or hard disk.

**Real-Time Example:**

- You edit a document and click Save.
- The application uses `fsync()` to request that the changes are written to storage.
- This helps ensure the saved data survives a crash or power loss.

**Remember:** `fsync()` asks the OS to make file changes persistent on storage.

---

<h2 style="color: #3673C1;">6.3 Disk Persistence</h2>

**Definition:**

Disk persistence means data remains stored even after a computer is turned off or restarted.

**Real-Time Example:**

- You save a photo on your laptop.
- You shut down the laptop.
- When you turn it on again, the photo is still there.

**Remember:** Disk persistence means saved data stays even after power is off.

---

<h2 style="color: #3673C1;">6.4 What Durability Really Means</h2>

**Definition:**

Durability means that once a system confirms data is safely saved, that data should not be lost—even if the system crashes or loses power.

**Real-Time Example:**

- You transfer money using a banking app.
- The app confirms the transaction.
- Even if the server crashes immediately afterward, the confirmed transaction should remain recorded.

**Remember:** Durability means confirmed data stays saved, even after a crash.

---