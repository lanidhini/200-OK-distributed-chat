# 200-OK-distributed-chat

# Simple Distributed Chat Website (Team 200 OK)

A lightweight, two-node distributed web chat application built with Python, WebSockets, and vanilla HTML/CSS/JavaScript. This project demonstrates core distributed systems concepts—including inter-node communication, shared user presence state, message ordering, and basic fault tolerance.

## Contributors
* **Moriah Lane** 
* **Emmanuel Nsiah** 
* **Drake Madesian** 
* **Suraj Shrestha** 

---

## System Architecture

Instead of relying on a single central server, users connect to either **Server 1** or **Server 2**. The two Python servers maintain a peer-to-peer WebSocket link to synchronize online user lists and forward messages across nodes in real time.
