# Pythonic-Chat: Building a Command-Line Chatroom

## Overview

**Pythonic-Chat** is a command-line chatroom application that allows users to communicate with each other in real time over a network. It is built using Python, leveraging socket programming to establish a server-client architecture. This project demonstrates the basics of networking and real-time communication in Python, providing a simple yet effective implementation of a chatroom system.

## Features

- **Server-Client Architecture**: One server manages multiple clients in a chatroom, allowing seamless message exchange.
- **Real-Time Communication**: Messages are transmitted instantly between connected clients.
- **Command-Line Interface**: Both the server and client are run in the terminal, offering a minimal and easy-to-use interface.
- **Scalability**: The server can handle multiple clients at the same time, enabling group chats.
- **Cross-Platform**: Written in Python, it can be run on any operating system with Python installed.

## Advantages

- **Simple and Easy to Understand**: The project uses basic Python concepts and socket programming, making it an excellent starting point for learning about network programming.
- **Lightweight**: No complex GUI is needed, keeping the system lightweight and focused on core functionality.
- **Real-Time Interaction**: Provides instant messaging, useful for understanding concepts like message broadcasting and event-driven programming.
- **Extendable**: The design of the chatroom can be extended to include more features like encryption, user authentication, and persistent message storage.

## Requirements

- Python 3.x or higher
- No additional external libraries required

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/Pythonic-Chat-Building-a-Command-Line-Chatroom.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Pythonic-Chat-Building-a-Command-Line-Chatroom
    ```

## Usage

### Starting the Server

1. In the terminal, navigate to the folder where the server script is located.
2. Run the server script:

    ```bash
    python server.py
    ```

3. The server will start and wait for client connections.

### Connecting Clients

1. In a new terminal window, navigate to the folder where the client script is located.
2. Run the client script:

    ```bash
    python client.py
    ```

3. Follow the prompts to connect to the server and start chatting.
