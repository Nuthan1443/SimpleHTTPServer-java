# Simple Java HTTP Server

This is a simple HTTP server implemented in Java. It listens for incoming connections on port `8080` and responds with the current date and time.

## Features
- Listens for HTTP requests on port `8080`.
- Responds with the current server date and time in the HTTP response.

## Prerequisites
- Java Development Kit (JDK) version 8 or above installed on your system.

## How to Run
1. Clone this repository or save the code file (`SimpleHTTPServer.java`) to your local machine.
2. Compile the Java file using the following command:
   ```bash
   javac SimpleHTTPServer.java
3. Run the compiled Java program:
   ```bash
   java SimpleHTTPServer
   
4. Open a web browser or use a tool like curl to make a request to the server:
   ```bash
   curl http://localhost:8080
   
- Or visit http://localhost:8080 in your browser.

## Expected Output
When the server receives a request, it will respond with the current date and time in the following format:
   (`HTTP/1.1 200 OK
    [Current Date and Time]`)

- Example:

 (`HTTP/1.1 200 OK
Mon Mar 10 12:34:56 IST 2025`)

## Notes
- The server runs indefinitely and listens for incoming connections until manually stopped.

- To stop the server, use Ctrl+C in the terminal where the server is running.

## Limitations
- This server does not parse incoming HTTP requests or handle HTTP headers.

- It's designed for learning purposes and should not be used in production environments.

## License
- This project is open-source and available under the MIT License.

