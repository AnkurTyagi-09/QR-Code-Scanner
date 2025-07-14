
# QR Code Scanner 📷

A sleek and simple web application to scan QR codes from image uploads using JavaScript.

## 🚀 Features

- Upload an image with a QR code
- Instantly reads and decodes the QR content
- Displays the decoded text in a textarea
- Option to copy the scanned text to clipboard
- Responsive UI design

## 📁 Project Structure

```
project-folder/
│
├── index.html          # Main HTML structure
├── style.css           # Custom styling
├── script.js           # QR code decoding logic
```

## 🧑‍💻 How It Works

1. User clicks the upload area to select an image with a QR code.
2. The `script.js` decodes the QR code using JavaScript and possibly a library like `jsQR` or similar.
3. The decoded text appears in a disabled textarea.
4. User can copy the scanned content using the "Copy Text" button.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (vanilla)
- Font Awesome (for icons)

## 📝 How to Use

1. Clone or download the repository.
2. Make sure `index.html`, `style.css`, and `script.js` are in the same directory.
3. Open `index.html` in a browser.
4. Click the upload area → Select a QR code image → View result → Copy if needed.

## 📌 Notes

- Requires a JavaScript QR decoding library (like `jsQR` or other).
- Customize the look via `style.css`.

## 📄 License

This project is licensed under the MIT License - feel free to use and modify!
