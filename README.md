# Rarity Agency Landing Page

A modern, responsive landing page for Rarity Agency - Growth for Startups.

## 🚀 How to Run Locally

Since this is a **static HTML file**, you have several options to view it locally:

### Option 1: Direct Browser Opening (Easiest)
1. Navigate to the project folder in File Explorer
2. Double-click on `lp_caio_rarity_offer.html`
3. The page will open directly in your default browser

### Option 2: Python HTTP Server
```bash
# Navigate to the project directory
cd "path/to/lp_caio_rarity_offer-main"

# Start Python HTTP server
python -m http.server 8080
```

Then open your browser and go to: **http://localhost:8080/lp_caio_rarity_offer.html**

### Option 3: Node.js http-server
```bash
# Navigate to the project directory
cd "path/to/lp_caio_rarity_offer-main"

# Start http-server (will install if not available)
npx http-server -p 3000
```

Then open your browser and go to: **http://localhost:3000/lp_caio_rarity_offer.html**

### Option 4: VS Code Live Server
1. Install the "Live Server" extension in VS Code
2. Right-click on `lp_caio_rarity_offer.html`
3. Select "Open with Live Server"

## ⚠️ Important Notes

- **Do NOT use `npm run dev`** - This is a static HTML file, not a Node.js project
- No `package.json` file is needed
- No build process required
- Works directly in any modern browser

## 🔧 Troubleshooting

### Port Already in Use
If you get an error like `EADDRINUSE: address already in use`, try:
- Use a different port: `python -m http.server 8081`
- Or kill the process using the port: `netstat -ano | findstr :3000`

### File Not Found
- Make sure you're in the correct directory
- Check that `lp_caio_rarity_offer.html` exists in the current folder

### Browser Issues
- Try refreshing the page (Ctrl+F5)
- Clear browser cache
- Try a different browser

## 📁 Project Structure
```
lp_caio_rarity_offer-main/
└── lp_caio_rarity_offer.html
```

## 🎨 Features
- Responsive design
- Modern dark theme with purple gradients
- Smooth animations
- Professional typography
- Mobile-friendly layout

## 🌐 Live Demo
The landing page is designed to showcase Rarity Agency's growth services for startups and e-commerce brands.

---
**Rarity Agency © 2025 | All rights reserved.** 