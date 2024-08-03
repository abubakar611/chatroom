 
Here's the updated README with the focus solely on Python for both the server and client:

---

# Python Chat Room with User Authentication

This repository contains a simple chat room application implemented using Python for both the server and client. The application allows multiple clients to connect to a server and communicate with each other in real-time, with each client choosing an alias before joining the chat room.


## Overview

This project demonstrates a chat room application where multiple clients can connect to a server and communicate in real-time. The application includes a user authentication system that prompts clients to choose an alias before joining the chat room.

## Features

- Real-time communication between multiple clients
- User authentication with alias selection
- Broadcasting messages to all connected clients
- Handling client disconnections gracefully

## Technologies Used

- **Programming Language:** Python
- **Networking:** `socket` library
- **Threading:** `threading` library
- **Protocol:** TCP

## Setup and Installation

### Prerequisites

- Python 3.x installed

### Server Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/chatroom.git
    ```

2. Navigate to the project directory:

    ```bash
    cd chatroom
    ```

3. Run the server script:

    ```bash
    python server.py
    ```

### Client Setup

1. Navigate to the project directory (if not already there):

    ```bash
    cd chatroom
    ```

2. Run the client script:

    ```bash
    python client.py
    ```

## Usage

1. Start the server using the instructions above.
2. Run the client script for each user that wants to connect to the chat room.
3. Each client will be prompted to enter an alias.
4. Clients can send messages to the chat room, and all connected clients will receive the messages in real-time.

## Example Usage

1. **Start the Server:**

    ```bash
    python server.py
    ```

2. **Start a Client:**

    ```bash
    python client.py
    ```

3. **Interaction:**

    - Client is prompted to enter an alias.
    - Client sends messages which are broadcast to all connected clients.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.


## Contact

For any questions or further information, please contact [abubakarjunaid611@gmail.com](abubakarjunaid611@gmail.com).

---

This README provides a clear and structured overview of your Python-based chat room project, including setup instructions, features, and usage guidelines. Feel free to adjust the content as needed to match your specific project details.
