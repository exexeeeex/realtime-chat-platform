<h1 align="center">E2EE Chat</h1>

<p align="center">
End-to-end encrypted chat application with real-time messaging and secure communication
</p>

<p align="center">
React • TypeScript • Node.js • Axios • FSD • Cryptography
</p>

---

## 🚀 Overview

E2EE Chat is a secure messaging application built around end-to-end encryption.  
Message content is never available to the server — all encryption and decryption happens on the client side.

The system provides:

- real-time messaging
- encrypted message transport
- secure key exchange
- minimal-trust server architecture

---

## ⚙️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,nodejs" />
</p>

**Frontend:**
- React
- TypeScript
- Axios
- Feature-Sliced Design (FSD)

**Backend:**
- Node.js
- HTTP API for message transport
- Crypto utilities for key handling and message relay

---

## 🔐 Security Model

- End-to-end encryption (E2EE)
- Messages are encrypted on the client before sending
- Server only relays encrypted payloads
- No access to plaintext data on backend
- Client-side key generation and decryption

---

## ✨ Features

- Real-time messaging
- Encrypted message delivery
- Secure session-based communication
- API communication via Axios
- Modular architecture with FSD
- Clear separation of transport and business logic

---

## 🧠 Architecture Notes

- Feature-Sliced Design on frontend
- Separation of layers:
  - UI layer
  - domain logic
  - API layer
- Backend acts as a stateless relay service
- All cryptographic operations handled on client side
- TypeScript used across the entire stack for type safety

---

## 📌 What this project demonstrates

- Implementation of end-to-end encryption principles
- Real-time communication system design
- Scalable frontend architecture (FSD)
- Fullstack TypeScript structure
- Secure client-side cryptographic workflows
