# 👕 SSH | Style Status Hub

**Premium Streetwear & Modern Fashion E-commerce Website**

## 🚀 Live Website
🎉 **Website is LIVE on GitHub Pages!**

👉 **Visit:** [https://ssmnssty-bot.github.io/ssh-fashion-hub/](https://ssmnssty-bot.github.io/ssh-fashion-hub/)

---

## 📱 Features

✅ **Modern Responsive Design** - Mobile, Tablet & Desktop friendly  
✅ **WhatsApp Integration** - Direct order placement via WhatsApp  
✅ **Product Grid** - Beautiful product display with images  
✅ **Shopping Cart Counter** - Track your orders  
✅ **Hero Banner** - Eye-catching banner section  
✅ **Fast Loading** - Optimized for speed  
✅ **Professional UI/UX** - Modern design with Poppins font  

---

## 🛍️ Products

1. **Oversized Black Tee** - ₹799
2. **Relaxed Fit Denim** - ₹1,499
3. **Streetwear Hoodie** - ₹1,299
4. **Urban Jacket** - ₹1,999
5. **Premium Sneakers** - ₹2,499
6. **Trendy Baseball Cap** - ₹599

---

## 🔧 How to Update WhatsApp Number

Edit `index.html` and find this line:

```javascript
const myPhoneNumber = "919876543210";
```

Replace `919876543210` with your WhatsApp number (with country code):
- **India:** `91` + your 10-digit number
- **Example:** `919876543210`

---

## 📁 Project Structure

```
ssh-fashion-hub/
│
└── index.html          (Main website file)
└── README.md           (This file)
```

---

## 🎨 Customization

### Change Store Name
In `index.html`, find:
```html
<div class="logo">SSH | Style Status Hub</div>
```

### Add More Products
Copy this product block and modify:
```html
<div class="product-card">
    <img src="YOUR_IMAGE_URL" alt="Product Name">
    <div class="product-title">Product Name</div>
    <div class="product-price">₹Price</div>
    <button class="btn-order" onclick="orderOnWhatsApp('Product Name', 'Price')">Order on WhatsApp</button>
</div>
```

### Change Colors
Edit CSS variables:
- `#e63946` = Red (accent color)
- `#25D366` = WhatsApp Green
- `#111` = Black (header/footer)

---

## 📊 How It Works

1. Customer clicks "Order on WhatsApp"
2. WhatsApp message is pre-filled with product details
3. Message opens in customer's WhatsApp
4. Customer sends message to your WhatsApp number
5. You get instant notification and can process the order

---

## 🌐 Deploy on Other Platforms

### GitHub Pages (Free - Already Setup ✅)
Your website is already live!

### Deploy Elsewhere
- **Netlify:** Drag & drop the folder
- **Vercel:** Connect GitHub repo
- **Firebase Hosting:** Follow their docs
- **Your Own Server:** Upload `index.html`

---

## 📞 Support

- **GitHub:** [https://github.com/ssmnssty-bot/ssh-fashion-hub](https://github.com/ssmnssty-bot/ssh-fashion-hub)
- **Edit Code:** Use GitHub's built-in editor
- **Push Changes:** Use Git commands or GitHub Desktop

---

## 📝 License

© 2026 Style Status Hub (SSH). All rights reserved.

---

**Made with ❤️ by Copilot**

**Last Updated:** 2026-09-14
