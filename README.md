# Hash-Demonstrator

# Interactive SHA-256 Hash Demonstrator

A lightweight, client-side web application that visually demonstrates the core properties of cryptographic hash functions in real-time. 

This tool is designed to help visualize how data authentication and integrity checks work under the hood by generating SHA-256 digests instantly as you type.

## 🔒 Core Cryptographic Concepts Demonstrated

* **The Avalanche Effect:** Observe how changing a single bit of input (like converting an uppercase letter to lowercase) drastically alters the entire output hash.
* **Fixed-Size Output:** Whether the input is a single character, a short password, or paragraphs of text, the resulting digest remains exactly 256 bits (64 hexadecimal characters) long.
* **Deterministic Output:** The same input text will consistently generate the exact same mathematical hash.

## 🚀 How to Use

Because this project runs entirely in the browser using the native Web Crypto API, there are no dependencies to install.

1.  Clone this repository or download the `index.html` file.
2.  Open `index.html` directly in any modern web browser.
3.  Begin typing in the input box to see the SHA-256 digest generate and shift in real-time.

## 🛠️ Technology Stack

* **HTML5 / CSS3:** For the user interface and responsive styling.
* **Vanilla JavaScript:** Handles the real-time event listening.
* **Web Crypto API (`crypto.subtle.digest`):** A native browser API used to securely calculate the SHA-256 hash without needing external libraries.

## 📝 License
This project is open-source and available for educational and personal use.
