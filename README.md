---

# 💧 Octra Faucet Frontend

A clean, responsive web interface for requesting testnet OCT tokens on the [Octra Protocol](https://octra.org) — a secure and private network for the future economy, powered by fully homomorphic encryption and machine learning.

This frontend connects to a backend service to let users request test tokens with wallet validation, toast notifications, and full mobile responsiveness.

---

## ✨ Features

- ✅ Wallet address validation (checks for valid `oct...` format)
- ✅ User-friendly toast notifications (success, error, status updates)
- ✅ Fully responsive design — works flawlessly on desktop and mobile
- ✅ Lightweight with no dependency: built with pure HTML, CSS, and JavaScript
- ✅ Compatible with any backend that supports the `POST /request-tokens` API

---

## 🚀 Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript**
- **Toast Notification System**
- **API Integration** – designed to work with any compatible faucet backend

---

## 📦 Backend Integration

This frontend is designed to work with the following backend project:

🔗 [Octra Faucet Backend (Node.js + Python CLI)](https://github.com/CaringStark/octra-faucet-project)

Make sure your server exposes a `POST /request-tokens` endpoint that accepts a JSON body like:

```json
{
  "address": "oct12dhgShG3235oGSV1ARpnw1LaXC2iFRH"
}
```

---

## 🛠 Contributing

Contributions are very much welcome! If you'd like to improve the UI, add new features, or fix bugs, feel free to open an issue or submit a pull request.

---
