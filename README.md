Building Real-Time Applications with Java Spring Boot and WebSocket
Real-time applications are those that require immediate response and 
interaction with the users and they can often involve data updates or 
notifications without requiring the page refresh. Java Spring Boot along 
with the WebSocket can provide a powerful framework for building such applications.
WebSocket is the communication channel over a single TCP connection, and it can enable real-time, 
bidirectional communication between the client and the server.
WebSocket can allow both the client and server to initiate communication at any time and also enable
instant data exchange without the need for continuous pooling or long-lived connections.

# ChatApp – Real-Time Group Messaging Application

A real-time group chat application built with Java Spring Boot and WebSocket, enabling instant communication between multiple users.

## 🚀 Features
- Real-time bi-directional messaging
- WebSocket integration using Spring
- Group chat support
- Reactive backend with Spring WebFlux
- Thymeleaf-based front-end

## 🛠️ Tech Stack
- Java 17+
- Spring Boot
- Spring WebSocket
- Spring Reactive
- Thymeleaf
- Maven

## 📦 Installation

```bash
git clone https://github.com/manish-op/ChatInGroup.git
cd ChatInGroup
mvn clean install
