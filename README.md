# 🖼️ Image Optimization Service

A lightweight, fast, and production-ready **on-the-fly image optimization backend** using **FastAPI**.  
It resizes and converts images to modern formats (like WebP), ideal for integration with CDNs like **CloudFront**.

---

## 🚀 Features

- 🔧 Resize images dynamically via query params
- 🌐 Convert to `webp`, `jpeg`, or `png`
- 📦 Built with FastAPI and Pillow
- 🔐 CORS enabled for browser and CDN use
- ⚡ Ready to be deployed behind CloudFront

---


## 📁 Project Structure

```
image-optimizer/
├── src/
│ ├── main.py # FastAPI app
│ ├── image_utils.py # Image processing logic
│ ├── requirements.txt
│ └── Dockerfile (optional)
```
## Install Python Dependencies
```
pip install -r requirements.txt
```

## Run the Application
```
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```

Your API will be running at:
http://localhost:8000/docs

## Dependencies
- FastAPI
- Uvicorn
- Pillow (PIL)
- requests

---

## 👤 Code Owner & Creator

**Repository Owner:** Ashutosh Mohanty  
**Contact:** https://www.linkedin.com/in/ashutoshmohanty-devops/

---

## 📄 License

This project is licensed under the MIT License.

