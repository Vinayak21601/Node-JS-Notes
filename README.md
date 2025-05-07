# 🖥️ CLI vs 🖼️ GUI

## What are they?

- **CLI (Command Line Interface)**: A text-based interface where users type commands to interact with the system.
- **GUI (Graphical User Interface)**: A visual interface using windows, icons, and buttons to perform actions.

---

## ✅ CLI (Command Line Interface)

**Examples**: Terminal, Command Prompt, Bash, PowerShell

### Advantages
- Faster for experienced users
- Low resource consumption
- Great for automation and scripting
- Offers more flexibility and control

### Disadvantages
- Steep learning curve
- No visual feedback; commands must be memorized
- Easy to make mistakes

---

## ✅ GUI (Graphical User Interface)

**Examples**: Windows, macOS, GNOME, KDE

### Advantages
- User-friendly and intuitive
- Easier for beginners
- Visual feedback helps reduce errors
- Drag and drop support

### Disadvantages
- Slower for repetitive tasks
- Uses more system resources
- Limited automation features

---

## 📊 CLI vs GUI Summary

| Feature              | CLI                         | GUI                         |
|----------------------|-----------------------------|------------------------------|
| Ease of Use          | Difficult for beginners     | Easy and intuitive           |
| Speed                | Fast for experienced users  | Slower due to visuals        |
| Resource Usage       | Low                         | High                         |
| Learning Curve       | Steep                       | Gentle                       |
| Automation           | Excellent (via scripts)     | Limited                      |
| Flexibility          | High                        | Lower                        |

---

## 👀 When to Use Which?

- Use **CLI** for automation, development, server management, and power-user tasks.
- Use **GUI** for general tasks, file browsing, design, and beginner-friendly environments.


---
# 🌐 What is Node.js?

Node.js is a **runtime environment** that allows you to run **JavaScript on the server-side**. Built on **Google Chrome’s V8 JavaScript engine**, Node.js enables developers to create scalable and high-performance applications using JavaScript outside of the browser.

> ⚡️ In simple terms, Node.js lets you use JavaScript to write backend/server-side logic.

---

## 🚀 Key Features

- **Asynchronous & Non-blocking I/O**  
  Efficiently handles multiple requests simultaneously without waiting.

- **Single-threaded Event Loop**  
  Uses a single-threaded architecture to handle concurrent operations via events and callbacks.

- **Cross-platform**  
  Runs on Windows, Linux, and macOS.

- **Package Manager (npm)**  
  Comes with **npm**, the largest open-source library ecosystem in the world.

- **Fast Execution**  
  Uses the V8 engine, which compiles JavaScript into machine code.

---

## 📦 What is Node.js Used For?

Node.js is used to build **fast, scalable network applications** and is widely used in modern web development. Here are common use cases:

### 1. 🔄 Web Servers and APIs
Node.js is commonly used to build RESTful APIs and backend services using frameworks like Express.js.

### 2. 📡 Real-Time Applications
Ideal for real-time apps such as:
- Chat applications
- Online gaming
- Live notifications

### 3. 📁 File System and Script Automation
Useful for CLI tools, automation scripts, and file manipulation tasks.

### 4. 📦 Microservices Architecture
Perfect for building lightweight microservices due to its fast I/O and low memory usage.

### 5. ⚙️ Server-Side Rendering (SSR)
Works with frontend frameworks like React (Next.js), Angular, and Vue for SSR.

### 6. 🛒 E-commerce Platforms
Used in full-stack development for shopping carts, product pages, and backend logic.

---

## 🧰 Popular Frameworks Built on Node.js

| Framework        | Description                        |
|------------------|------------------------------------|
| **Express.js**   | Fast, minimalist web framework     |
| **NestJS**       | Angular-inspired, scalable backend |
| **Koa.js**       | Lightweight and modular            |
| **Next.js**      | React framework for SSR & API      |
| **Socket.io**    | Real-time WebSocket communication  |

---

## 📊 Companies Using Node.js

- Netflix
- LinkedIn
- Uber
- PayPal
- eBay
- Walmart

---

## ✅ Why Use Node.js?

- Full-stack development with JavaScript (frontend + backend)
- Massive ecosystem (npm)
- High performance and scalability
- Ideal for real-time, data-intensive applications





# 📦 Node.js Built-in Modules (Core Modules)

> These modules are part of the Node.js runtime and do not require separate installation.  
> You can import them using `require('module-name')` or `import` in ES Modules.

---

## 🔧 System Modules

| Module Name       | Description |
|-------------------|-------------|
| `assert`          | Provides a set of assertion tests. |
| `buffer`          | Provides operations to handle binary data. |
| `child_process`   | Used to spawn subprocesses. |
| `cluster`         | Allows easy creation of child processes that all share server ports. |
| `console`         | Used to print to stdout and stderr. |
| `constants`       | Contains system-level constants. |
| `crypto`          | Provides cryptographic functionalities like hashing, encryption. |
| `dns`             | Used to do DNS lookups and name resolution. |
| `domain` *(deprecated)* | Provides a way to handle multiple different I/O operations as a single group. |
| `events`          | Enables working with events via `EventEmitter`. |
| `fs`              | File system-related functionality (read/write files, etc). |
| `http`            | Creates HTTP server and handles HTTP requests. |
| `http2`           | Implements HTTP/2 protocol. |
| `https`           | HTTPS server functionality. |
| `inspector`       | Debugging interface for Node.js via Chrome DevTools. |
| `module`          | Internal module handling system. |
| `net`             | Provides asynchronous network APIs. |
| `os`              | Provides operating system-related utility methods. |
| `path`            | Utilities for file and directory paths. |
| `perf_hooks`      | Performance measurement APIs. |
| `process`         | Provides information about the current process. |
| `punycode`        | Converts Unicode to ASCII for domain names. |
| `querystring`     | Utilities for parsing and formatting URL query strings. |
| `readline`        | Allows reading lines from a readable stream (like stdin). |
| `repl`            | Provides a REPL (Read-Eval-Print Loop) implementation. |
| `stream`          | Interfaces for streaming data. |
| `string_decoder`  | Decodes buffer data into readable strings. |
| `timers`          | Handles scheduling functions like `setTimeout`. |
| `tls`             | Implements TLS and SSL protocols. |
| `trace_events`    | Tracing APIs for diagnostic reporting. |
| `tty`             | Provides terminal (TTY) capabilities. |
| `url`             | Utilities for URL resolution and parsing. |
| `util`            | Various utility functions (e.g., `promisify`). |
| `v8`              | Access to V8 engine-specific APIs. |
| `vm`              | Provides APIs to compile and run code in VMs. |
| `worker_threads`  | Multithreading support for CPU-intensive operations. |
| `zlib`            | Compression and decompression (gzip, deflate, etc). |

---

## ✅ Usage Example

```js
const fs = require('fs');
const path = require('path');
```

Or using ES Modules:

```js
import fs from 'fs';
import path from 'path';
```
