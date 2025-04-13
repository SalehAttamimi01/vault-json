# Vault-JSON

This project is a simple repository for hosting a JSON file that can be used in other applications. It's designed to make it easy to access and manage static JSON content via a raw file URL.

## 🚀 Purpose

Host a JSON file that can be accessed from anywhere by simply using the raw GitHub file link.

## 📦 Tech

- JSON

## 🔧 Usage

1. Open the JSON file in the repository.
2. Click on **"Raw"** to open the raw version of the file.
3. Copy the URL from the browser address bar.
4. Use that URL wherever your app needs to access the JSON data.

Example usage:
```js
fetch('https://raw.githubusercontent.com/your-username/vault-json/main/your-file.json')
  .then(res => res.json())
  .then(data => {
    console.log(data);
  });
