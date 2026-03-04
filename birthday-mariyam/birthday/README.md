# 🌸 Mariyam's Birthday Month Page — Setup Guide

## Folder Structure
```
📁 birthday/
├── index.html          ← the main page
└── 📁 images/
    ├── message1.jpg    ← photo for Day 1 letter
    ├── message2.jpg    ← photo for Day 2 letter
    ├── message3.jpg    ← ...and so on up to message30.jpg
    ├── gallery1.jpg    ← birthday rain photo 1
    ├── gallery2.jpg    ← birthday rain photo 2
    ├── ...             ← up to gallery10.jpg (can add more!)
```

## 📸 Adding Photos

### For daily letters (Days 1–30):
- Name your photos: `message1.jpg`, `message2.jpg`, ... `message30.jpg`
- Drop them into the `images/` folder
- Any format works (jpg, png, webp) — just rename them

### For the birthday rain (Day 31):
- Name your photos: `gallery1.jpg`, `gallery2.jpg`, ... `gallery10.jpg`
- Add as many as you want — update `GALLERY_COUNT` in the JS to match

## 🔑 Changing the Password
Open `index.html`, find this line near the top of the `<script>`:
```js
const PASSWORD = "mariyam2025";
```
Change it to whatever you want!

## 💬 Changing Photo Captions
In the same script section, find the `captions` array:
```js
const captions = [
  "Us 💜",         // shown under Day 1 photo
  "My favourite laugh 🌸",  // Day 2
  ...
];
```
Edit each caption to match your photo memory.

## 🚀 Sharing with Mariyam
Just zip the whole `birthday/` folder (with the images inside) and:
- Host it for free on **Netlify Drop** (drag & drop at netlify.com/drop)
- Or host on **GitHub Pages**
- Or just send her the folder and she opens `index.html` in her browser!

## Password hint
Default password is: **mariyam2025** (change this before sharing!)
