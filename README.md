# Happy Mothers Day - Flower Shop Homepage

A responsive flower shop homepage built with **HTML5**, **Bootstrap 5**, and custom **CSS**.

## 📁 File Structure

```
MyWebsite/
├── index.html                          # Main homepage file
├── css/
│   └── styles.css                      # Custom styling
├── images/                             # Create this folder and add your images here
│   ├── hero-image.jpg                  # Hero section image (right side)
│   ├── category-1.jpg                  # Flower category icon 1 (80x80px)
│   ├── category-2.jpg                  # Flower category icon 2 (80x80px)
│   ├── category-3.jpg                  # Flower category icon 3 (80x80px)
│   ├── category-4.jpg                  # Flower category icon 4 (80x80px)
│   ├── flowers-banner.jpg              # Flowers section banner image
│   ├── product-1.jpg to product-8.jpg  # 8 product images (200x200px recommended)
│   ├── testimonial-banner.jpg          # Best sellers section banner
│   ├── profile-1.jpg to profile-4.jpg  # 4 profile images for testimonials (circular, 80x80px)
│   ├── team-1.jpg to team-3.jpg        # 3 team/gallery images
│   └── README.md
└── web-dev-intern-html-sample-home-page.png  # Design reference image
```

---

## 🖼️ IMAGE PLACEHOLDER LOCATIONS

### 1. **Hero Section**
- **File:** `index.html` (Line ~50)
- **Image Name:** `images/hero-image.jpg`
- **Purpose:** Main hero image on the right side of "HAPPY MOTHERS DAY" title
- **Recommended Size:** 500x400px

### 2. **Category Filter Icons** (4 images in a row)
- **File:** `index.html` (Lines ~63-80)
- **Image Names:** 
  - `images/category-1.jpg` (Rose)
  - `images/category-2.jpg` (Tulip)
  - `images/category-3.jpg` (Daisy)
  - `images/category-4.jpg` (Sunflower)
- **Purpose:** Small circular flower category icons
- **Recommended Size:** 80x80px (circular)

### 3. **Flowers Banner**
- **File:** `index.html` (Line ~87)
- **Image Name:** `images/flowers-banner.jpg`
- **Purpose:** Large banner image above the product grid
- **Recommended Size:** 1200x300px

### 4. **Product Cards** (8 images in a 4-column grid)
- **File:** `index.html` (Lines ~97-187)
- **Image Names:** 
  - `images/product-1.jpg` through `images/product-8.jpg`
- **Purpose:** Individual flower product images
- **Recommended Size:** 400x400px

### 5. **Testimonial Banner**
- **File:** `index.html` (Line ~203)
- **Image Name:** `images/testimonial-banner.jpg`
- **Purpose:** Banner image for Best Sellers section (left side)
- **Recommended Size:** 400x500px

### 6. **Profile Pictures** (4 images, circular)
- **File:** `index.html` (Lines ~212, 225, 238, 251)
- **Image Names:**
  - `images/profile-1.jpg` (Sarah Johnson)
  - `images/profile-2.jpg` (Emily Davis)
  - `images/profile-3.jpg` (Jessica Lee)
  - `images/profile-4.jpg` (Michelle White)
- **Purpose:** Customer/team member profile pictures
- **Recommended Size:** 150x150px (will be displayed at 80x80px)

### 7. **Team/Gallery Images** (3 images)
- **File:** `index.html` (Lines ~267-288)
- **Image Names:**
  - `images/team-1.jpg`
  - `images/team-2.jpg`
  - `images/team-3.jpg`
- **Purpose:** Team or shop gallery images
- **Recommended Size:** 600x400px

---

## 🚀 How to Use

### Step 1: Create Images Folder
Create an `images` folder in the project root:
```powershell
New-Item -ItemType Directory -Path "images" -Force
```

### Step 2: Add Your Images
Copy all your images into the `images` folder with the exact names mentioned above.

### Step 3: Preview Locally
Run a local server to preview the website:

**Option A: Using Python (Recommended)**
```powershell
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

**Option B: Using Node.js**
```powershell
npx http-server
# Then open http://localhost:8080 in your browser
```

**Option C: Using Live Server (VS Code Extension)**
- Install "Live Server" extension in VS Code
- Right-click `index.html` → "Open with Live Server"

---

## 📦 Creating Submission ZIP

### Option 1: PowerShell
```powershell
cd d:\MyWebsite
Compress-Archive -Path * -DestinationPath web-dev-intern-submission.zip
```

### Option 2: File Explorer
- Right-click the project folder
- Select "Send to" → "Compressed (zipped) folder"
- Rename to `web-dev-intern-submission.zip`

---

## 🌐 Optional: Host Online (Free Alternatives)

### **Netlify (Recommended)**
1. Create account at [netlify.com](https://netlify.com)
2. Drag & drop your project folder
3. Get instant live link

### **GitHub Pages**
1. Create GitHub repo
2. Push files to `main` branch
3. Enable Pages in settings
4. Live link: `https://yourusername.github.io/repo-name`

### **Vercel**
1. Create account at [vercel.com](https://vercel.com)
2. Import project
3. Auto-deployed

---

## 📝 Customization Tips

### Change Shop Name
- Line 20 in `index.html`: Replace `FlowerShop` with your shop name

### Change Button Text
- Line 46: "Shop Now" button text
- Line 207: "Best Sellers" section heading

### Edit Product Names & Prices
- Lines 106-187: Modify `Flower Name 1-8` and prices

### Edit Testimonials
- Lines 212-257: Change customer names, titles, and quotes

### Modify Colors
- Edit `css/styles.css` (lines 8-14) under `:root`

---

## ✅ Submission Checklist

- [ ] Created `images/` folder
- [ ] Added all 18+ images with correct names
- [ ] Previewed locally (works correctly)
- [ ] Updated shop name and text (optional)
- [ ] Created ZIP file for submission
- [ ] Test the ZIP by extracting it (verify all files present)

---

## 🎨 Design Features

✓ **Responsive Design** - Works on mobile, tablet, desktop  
✓ **Bootstrap 5** - Fast loading, grid system  
✓ **Smooth Animations** - Hover effects on cards/images  
✓ **Accessibility** - Semantic HTML, focus indicators  
✓ **Clean Code** - Well-commented, easy to modify  

---

## 📧 Questions?

If images don't display:
1. Check image names match exactly (case-sensitive on some servers)
2. Verify images are in `images/` folder
3. Try different image formats (JPG, PNG)
4. Check browser console for errors (F12)

---

**Ready to submit?** Create your ZIP and reply to the application email! 🚀
