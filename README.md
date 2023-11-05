# Chat Server and Client Application

This repository contains a simple chat server and client application implemented in Python. The server allows multiple clients to connect, send messages, and execute basic commands. The communication between the server and clients is facilitated through sockets and threading.

## Features

- **Multiple Client Support:** The server can handle multiple clients simultaneously, allowing them to join the chat and exchange messages.
- **Command Handling:** The server supports basic commands like kicking and banning users. Only the admin user can execute these commands for moderation purposes.
- **Persistent Banning:** Usernames of banned clients are stored in a file (`bans.txt`), ensuring persistent banning even if the server is restarted.

## Prerequisites

- Python 3.x
- Knowledge of basic Python programming concepts
- Terminal or Command Prompt for running the server and client scripts

## How to Run

- Clone the repo
- Move to working directory
- make changes to IP address and port in `**server.py**` file
- Start server by running `python server.py`
- Join as client by running `client.py` on other terminal

## Commands

### Regular Users

- Simply type your message and press Enter to send it to the chat.

### Admin User

- To kick a user from the chat: `/kick username`
- To ban a user: `/ban username`



