A lightweight and beginner-friendly web-based tool to encrypt and decrypt messages using the Caesar Cipher algorithm.

📌 Overview
This project is a static webpage that allows users to apply Caesar Cipher logic directly in the browser using JavaScript, styled with CSS, and structured with HTML. It’s ideal for learning basic frontend logic and classical cryptography techniques.

🔗 Live Demo
https://something1188.github.io/SCT_CS_01/

🔧 Features
Encrypt and decrypt text using the Caesar Cipher

Choose any shift value (positive or negative)

Retains non-letter characters like spaces, punctuation, etc.

Simple and responsive UI for easy usage

🚀 Getting Started
You can run this project directly in your browser.

Option 1: Use Online
visit the live version here:
<pre>https://something1188.github.io/SCT_CS_01/</pre>

Option 2: Run Locally
Clone the repository:

<pre>
git clone https://github.com/something1188/SCT_CS_01.git</pre>

Open the project folder and launch index.html in your browser:
<pre>
cd SCT_CS_01
start index.html</pre>
That's it!

🧠 How It Works
JavaScript captures user input: the message and shift value.

It loops through each character, checks if it’s a letter, and shifts it by the given value.

Non-alphabet characters remain unchanged.

The result is displayed in a read-only text box below.

🧪 Example
Input: Hello, World!
Shift: 3
Encrypted: Khoor, Zruog!
Decrypted (with -3): Hello, World!
