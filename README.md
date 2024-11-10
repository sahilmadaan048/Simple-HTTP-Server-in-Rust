# Simple-HTTP-Server-in-Rust
This project is a simple HTTP server implemented in Rust, based on the tutorial in The Rust Programming Language book. The project is designed to demonstrate key Rust concepts, including memory safety, concurrency, and low-level networking.
Project Overview
This server handles basic HTTP requests, serving either static HTML content or a 404 error response. It’s designed to be lightweight yet functional, using Rust's standard library for networking and concurrency. By building this server, we explore core Rust features and dive into systems programming in a safe, efficient way.

Key Features
TCP Listener: Listens on a specified port, accepting incoming client connections.
Request Parsing: Reads and parses HTTP requests, handling basic GET requests.
Static Response: Serves static HTML or a 404 error message based on the request path.
Multithreading: Processes each request in a separate thread, utilizing Rust's memory safety features.
Custom Thread Pool: Limits concurrent requests with a custom thread pool for efficient resource management.
Graceful Shutdown: Supports a graceful server shutdown, ensuring resource cleanup.
Getting Started
To run the server:

Clone the repository.
Install Rust if you haven’t already: Rust Installation
Run the server:
bash
Copy code
cargo run
Then, open a web browser and navigate to http://localhost:7878 (or your chosen port) to see it in action.

Project Goals
This project is intended as a learning experience, giving insights into Rust's approach to concurrency, safety, and efficient networking. It’s an excellent starting point for building more advanced and production-ready web servers in Rust.
