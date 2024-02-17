# Simple WebSocket Chat Application

This is a basic chat application using raw websockets in Node.js with features to create chat sessions, send messages, and upvote messages. It supports the following functionalities:

## Features

1. **Admin Controls:**
   - Create a new chat session with specified properties:
      - Name
      - Start Time
      - Is Open (whether users can join)
      - Cool Down Time

2. **User Interaction:**
   - Join a chat room and send messages.
   - Upvote chat messages.

3. **Message Management:**
   - Messages with more than 3 upvotes are moved to a separate section.
   - If messages reach more than 10 upvotes, the admin is alerted to answer.

## Getting Started

### Prerequisites

- Node.js installed on your machine. If not installed, you can download it from [Node.js](https://nodejs.org/).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kshatsharmaaa/Chat-UpvoteFunctionality.git
