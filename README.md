# QR Code Generator

This is a simple *QR Code Generator* web app built with *HTML, CSS*, and JavaScript. It allows users to generate QR codes for any text or URL using a free QR code API.

## 🚀 Features

- Generate QR codes instantly for any input text or link.
- Download or save the generated QR code image.
- Clean and responsive design using HTML and CSS.
- No backend required—works entirely in the browser.
- ## 🛠️ How It Works

This project uses the [QR Code API](https://goqr.me/api/) (or any other QR API of your choice).  
When the user enters text and clicks *Generate*, the app:
1. Constructs an API URL with the input data.
2. Sets the src attribute of an <img> tag to this URL.
3. Displays the QR code image automatically.
  
