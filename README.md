Simple HTTP Server in C

A minimal HTTP server implemented in pure C using Linux system calls.
This project demonstrates how HTTP works internally without using external libraries such as libcurl, Boost, or frameworks.

The goal is to understand low-level networking, sockets, Linux fundamentals, and the internal mechanics of how a web server accepts connections and responds to clients.

Overview

This project contains a simple web server that:

Creates a TCP socket

Binds it to a port

Listens for incoming HTTP requests

Accepts one connection at a time

Sends a static HTTP response (HTML)

Closes the connection

This is one of the simplest working examples of an HTTP server and serves as a foundation for more advanced functionality such as routing, multithreading, dynamic pages, file serving, and handling multiple clients.

Features

Written in standard C (no external libraries)

Uses POSIX socket API

Supports HTTP GET requests

Returns a valid HTTP/1.1 response

Works on any Linux distribution

Small and educational codebase


this was devoloped in Mint linux 
future steps making a framework out if it 

