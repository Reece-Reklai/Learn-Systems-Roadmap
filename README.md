----------------------------------------------------------------------------
Web Development Fundamentals (Golang) 
----------------------------------------------------------------------------

To build a solid foundation in web development, focus on these core concepts:

⚙️ Networking & Protocols

Understand how the HTTP protocol works (requests, responses, headers, status codes)

Learn basic networking principles (IP, DNS, routing, ports)

🧳 Containers & Deployment

Gain experience with containers

Learn the Docker / OCI ecosystem

Explore how applications are built, packaged, and deployed

🗄️ Data & Persistence

Learn how databases operate (SQL & NoSQL)

Write real SQL queries (even if you typically use an ORM)

Understand message queues and asynchronous communication patterns

🧠 Modern Front-End Challenges

Build reactive UIs with vanilla JavaScript + DOM API first

Then learn frameworks like React to understand:

State management

Efficient DOM updating (virtual DOM / diffing)

Component-based architecture

What problems frameworks actually solve

-------------------------------------------------------------------------
Zig Roadmap
-------------------------------------------------------------------------

1️⃣ Core Data Structures

Implement your own foundational library (to be reused in future projects):

String type

Dynamic array / vector

Hash map

2️⃣ Core Utilities (Coreutils)

Re-create essential Unix command-line tools:

cat / less

ls

mv / cp

find / grep
For grep: simple globbing or a custom lightweight pattern engine is fine.

3️⃣ Shell

A great intro to interpreters and system APIs:

Environments + environment variables

Subprocesses (fork, exec)

Signals + traps

String interpolation & variable expansion

POSIX compliance basics

Why cd must be a shell builtin

Familiarity with libc & Linux syscalls

4️⃣ HTTP/1.0 Server

Use raw Linux sockets:

bind, accept, send, recv

Non-blocking accept

Prefer epoll over one thread per connection

Bonus: connection pooling with LRU caching

5️⃣ Interpreter / Compiler

Can be any language — for fun & learning:

Learn recursive descent parsing

Optional: design your own bytecode + VM

Understand labels, jump tables, loops, branches

Suggested resource: Writing an Interpreter in Go by Thorsten Ball

6️⃣ Memory Allocator (C)

Build a custom allocator:

Use mmap for memory regions

Learn fragmentation & book-keeping trade-offs

Reference: Ginger Bill’s allocator series

7️⃣ Emulator Projects

Understand CPU internals & bit manipulation:

Beginner: Chip-8

Advanced: Intel 8080, MOS 6502

8️⃣ Additional Project Ideas

Optional but valuable systems challenges:

CPU cache simulator

TUI text editor

Stackful coroutine-based async I/O library
(e.g., Rust + io_uring, goroutine-style)
