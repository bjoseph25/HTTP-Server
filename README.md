# HTTP Server

A lightweight HTTP server built with Python that serves static web content and handles basic HTTP requests. This project was created to deepen my understanding of networking concepts, the HTTP protocol, socket programming, and server-client communication.

## Features

- Serves static HTML files
- Handles HTTP GET requests
- Returns appropriate HTTP status codes (200, 404, etc.)
- Supports multiple client connections (if implemented)
- Lightweight command-line server
- Easy to customize and extend

## Technologies Used

- Python 3
- Socket Programming
- HTTP Protocol

## Getting Started

### Prerequisites

- Python 3.x installed

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/HTTP-Server.git
```

2. Navigate to the project directory:

```bash
cd HTTP-Server
```

3. Start the server:

```bash
python server.py
```

4. Open your browser and visit:

```text
http://localhost:8080
```

> Replace `8080` with your configured port if different.

## Example

```text
Server started on port 8080...
Waiting for client connections...

GET / HTTP/1.1
Response: 200 OK

GET /about.html HTTP/1.1
Response: 200 OK

GET /missing.html HTTP/1.1
Response: 404 Not Found
```

## Project Structure

```text
HTTP-Server/
├── server.py
├── index.html
├── README.md
└── static/
```

## Skills Demonstrated

- Python programming
- Socket programming
- HTTP protocol fundamentals
- Client-server communication
- Request parsing
- Error handling
- Networking fundamentals
- Debugging and testing

## Future Improvements

- Support POST requests
- Multi-threaded client handling
- Logging and monitoring
- HTTPS support
- MIME type detection
- Directory serving
- REST API support

## License

This project is licensed under the MIT License.

## Author

**Brandon Joseph**

- GitHub: https://github.com/bjoseph25
- LinkedIn: https://linkedin.com/in/brandonjosephcs
