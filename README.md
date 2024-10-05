# HTTP Web Server using C++

This project is a simple HTTP server built using C++ and Winsock2. It handles basic `GET` requests and serves files from the server's directory.

## Requirements
- g++ (MinGW or any other compatible compiler)
- Windows (for Winsock2)
- Basic understanding of socket programming

## Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/webghost696/HTTP-Web-Server-using-Cpp.git
cd HTTP-Web-Server-using-Cpp
```
### 2. Compile the server
```bash
g++ server.cpp -o server.exe -lws2_32
```
### 3. Run the Server
```bash
./server.exe
```
### 4. Enjoy your very own HTTP Server on "http://localhost:8080/index.html"
