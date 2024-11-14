# Distributed Instant Messaging System using Java RMI
This project is a distributed instant messaging application built using Java RMI (Remote Method Invocation). The system allows multiple clients to connect to a central server for managing connections and status notifications. Once connected, clients communicate directly with each other for real-time messaging, bypassing the server to reduce load and ensure a peer-to-peer message flow.

Features:
- Real-Time Notifications: Each client is notified when others connect or disconnect.
- Direct Client-to-Client Messaging: Messages are sent directly between clients without passing through the server.
- Friend Group Management (Optional): Allows users to register and manage friend groups. Friend requests are stored by the server if the target user is offline and are processed upon reconnection.
This architecture efficiently scales by handling connection management on the server while enabling direct messaging between clients, providing a lightweight, responsive messaging experience.
