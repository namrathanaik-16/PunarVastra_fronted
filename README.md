# PunarVastra - Frontend

## 🌟 Textile Waste Valorization Platform

A platform that connects textile factories with artisans through AI-powered waste valorization for a circular fashion ecosystem.

---

## 🎨 **Features**

### **Factory Dashboard**
- Upload textile waste images
- AI-powered analysis (Color, Texture, Pattern detection)
- Enter quantity available and pricing
- View all uploaded materials
- Real-time inventory management

### **Artisan Marketplace**
- Browse AI-categorized materials
- Filter by color, texture, and quantity
- View detailed material information
- Purchase materials directly
- See real-time availability

### **AI Analysis**
- Automatic color detection
- Texture classification
- Pattern recognition
- Quality assessment

---

## 🚀 **Live Demo**

**Frontend:** https://punarvastra.netlify.app/

**Backend API:** https://punarvastra-backend.onrender.com/

---

## 💻 **Tech Stack**

- **HTML5** - Structure
- **CSS3** - Vogue-inspired black/gold design
- **JavaScript** - Frontend logic and API integration
- **Fetch API** - Backend communication

---

## 🔗 **Backend Integration**

This frontend connects to the PunarVastra backend API:

**Repository:** https://github.com/namrathanaik-16/PunarVastra_backend

**API Endpoints:**
- `POST /api/upload` - Upload material with AI analysis
- `GET /api/materials` - Get all materials (Artisan Marketplace)
- `GET /api/factory/materials` - Get factory's own materials
- `POST /api/orders` - Create purchase order

---

## 📦 **Deployment**

### **Deploy to Netlify**

1. Fork this repository
2. Go to [Netlify](https://netlify.com)
3. Click "Add new site" → "Import from Git"
4. Select this repository
5. Deploy settings:
   - Build command: (leave empty)
   - Publish directory: (leave empty or `/`)
6. Click "Deploy site"

### **Manual Deployment**

1. Download `index.html`
2. Go to Netlify Dashboard
3. Drag and drop the file
4. Done!

---

## 🎯 **How It Works**

### **Factory Workflow:**
```
Upload Image
    ↓
AI Analyzes (Color, Texture, Pattern)
    ↓
Factory Enters (Quantity, Price)
    ↓
Submit Material
    ↓
Appears in Factory Dashboard & Artisan Marketplace
```

### **Artisan Workflow:**
```
Browse Marketplace
    ↓
View Material Details (AI Analysis + Pricing)
    ↓
Select Material
    ↓
Place Order
    ↓
Order Confirmed
```

---

## 🎨 **Design**

- **Theme:** Vogue-inspired luxury aesthetic
- **Colors:** Black (#0a0a0a) with Gold accents (#d4af37)
- **Typography:** Playfair Display (serif) + Arial (sans-serif)
- **Style:** Minimalist, elegant, professional

---

## 📱 **Pages**

1. **Home** - Overview and features
2. **Factory Dashboard** - Upload and manage materials
3. **Artisan Marketplace** - Browse and purchase materials

---

## 🔧 **Configuration**

The backend API URL is configured in the JavaScript section:

```javascript
const API_URL = 'https://punarvastra-backend.onrender.com/api';
```

To change the backend URL, edit this constant in `index.html` (around line 1115).

---

## 📊 **Features Breakdown**

### **Upload System**
- Single file upload
- Image validation (JPG, PNG, JPEG)
- 5MB size limit
- Real-time preview

### **AI Analysis Display**
- Color detection results
- Texture classification
- Pattern identification
- Quality rating

### **Form Validation**
- Required quantity field
- Required price field
- Real-time total calculation
- Input validation

### **Material Display**
- Grid layout for materials
- Filter functionality
- Responsive cards
- Purchase modal

---

## 🌐 **Browser Support**

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

---

## 📄 **License**

MIT License

---

## 👥 **Contributors**

- **Developer:** namrathanaik-16

---

## 🔗 **Related Repositories**

- **Backend:** [PunarVastra_backend](https://github.com/namrathanaik-16/PunarVastra_backend)

---

## 📞