# Roomio Marketplace Page - Image Specifications

**For:** Steven  
**Date:** February 24, 2026

---

## 📸 Images Needed for Roomio Marketplace Page

The Roomio marketplace page currently uses placeholder images. Here's what you need to create/source to complete the page.

---

## 1. Hero Background Image

**Location in HTML:** Line 71  
**Purpose:** Large background image for the intro/hero section  
**Current:** `https://roomio.io/wp-content/uploads/2025/09/ae71cd2c882ebac90b89fc069aac88d6e0702b12-818x1024.png`

**Specifications:**
- **Size:** 1920 x 1080px (16:9 aspect ratio)
- **Format:** PNG or JPG
- **Content:** Branded hero image for Roomio
- **Design ideas:**
  - Roomio logo prominently displayed
  - "Professional Floor Plans from Your iPhone" tagline
  - Screenshot of Roomio app interface
  - AUD$15 pricing callout
  - WGAN branding/partnership badge (optional)

**Example style:** Similar to Captur3d hero image at:  
`https://marketplace.wganforum.com/wp-content/uploads/2020/06/WGAN-CAPTUR3D-MarketPlace-NewLogo-1920x1080-FH-19-Apr-24copy.png`

---

## 2. Carousel Image #1

**Location in HTML:** Line 191-196  
**Purpose:** First image in the gallery slider  
**Current:** Using Roomio app screenshot from website

**Specifications:**
- **Size:** 1600 x 1000px (or 1920 x 1080px)
- **Format:** PNG or JPG
- **Content:** Roomio app in action
- **Design ideas:**
  - iPhone showing Roomio app scanning a property
  - "Scan in Under 5 Minutes" headline
  - Visual representation of LiDAR scanning
  - Before/after: scan → floor plan

**Alternative:** Use existing high-quality screenshot from Roomio website or App Store

---

## 3. Carousel Image #2

**Location in HTML:** Line 197-202  
**Purpose:** Second image in the gallery slider  
**Current:** Using Roomio logo

**Specifications:**
- **Size:** 1600 x 1000px (or 1920 x 1080px)
- **Format:** PNG or JPG
- **Content:** Roomio features/benefits banner
- **Design ideas:**
  - "AUD$15 Floor Plans | 12-24 Hour Delivery"
  - Grid showing floor plan templates
  - Custom branding examples
  - Side-by-side comparison: Roomio vs. competitors

**Alternative:** Professional floor plan examples created with Roomio

---

## 4. Carousel Image #3 (Recommended)

**Location in HTML:** Add after line 202  
**Purpose:** Third image in the gallery slider (to match Captur3d's 3-image carousel)  
**Currently:** Not present (only 2 images in carousel)

**Specifications:**
- **Size:** 1600 x 1000px (or 1920 x 1080px)
- **Format:** PNG or JPG
- **Content:** WGAN membership benefit or special offer
- **Design ideas:**
  - "Exclusive Offer for WGAN Members"
  - Free trial or promotional pricing
  - Customer testimonials
  - Trust badges: "iPhone LiDAR Technology" "1-2cm Accuracy"

**Alternative:** Feature comparison chart or use case examples

---

## 5. Optional: Banner Images for Specific Messages

**Additional carousel slides (4th, 5th, etc.):**

### A. Testimonial Banner
- Customer quote from a real estate agent or photographer
- Photo of customer (if available)
- Star ratings or review score
- "Used by [X] Real Estate Professionals"

### B. Feature Highlight Banner
- Focus on one key feature: "Largest Single Scans on the Market"
- Diagram or infographic explaining the technology
- Comparison with traditional laser measuring

### C. Speed/Efficiency Banner
- "4-Bedroom Property Scanned in <5 Minutes"
- Timeline graphic showing scan → submit → receive workflow
- Express delivery callout (8-hour option)

---

## 🎬 Video Specification

**Location in HTML:** Line 182  
**Purpose:** Embedded demo/promo video  
**Current:** `PLACEHOLDER`

**Specifications:**
- **Platform:** YouTube (preferred) or Vimeo
- **Duration:** 1-3 minutes recommended
- **Content:** Roomio app demo
- **Video ideas:**
  - Quick tutorial: How to scan a property with Roomio
  - Before/after showcase: Scan → Floor Plan
  - Customer testimonial compilation
  - Feature walkthrough

**What to replace:**
```html
<!-- Current: -->
<iframe src="https://www.youtube.com/embed/PLACEHOLDER" frameborder="0" allowfullscreen></iframe>

<!-- Replace PLACEHOLDER with actual video ID, e.g.: -->
<iframe src="https://www.youtube.com/embed/ABC123XYZ" frameborder="0" allowfullscreen></iframe>
```

**If Roomio video is:** `https://www.youtube.com/watch?v=ABC123XYZ`  
**Use video ID:** `ABC123XYZ`

---

## 🎨 Design Guidelines

To match the WGAN marketplace style and Captur3d branding:

### Color Palette
- **Primary:** Use Roomio brand colors
- **Accent:** WGAN brand colors for partnership elements
- **Background:** Clean, professional (white or light gray)
- **Text:** High contrast for readability

### Typography
- **Headlines:** Bold, clear, large font (Oswald or similar)
- **Body:** Clean, readable (Lato or similar)
- **Pricing:** Large, prominent display

### Layout
- **Left-aligned** or **centered** text
- **Clear hierarchy:** Headline → Subheadline → Features/Benefits
- **Breathing room:** Don't overcrowd images with text
- **Branding:** Roomio logo should be clearly visible

---

## 📂 Where to Source Images

### Option 1: Use Existing Roomio Marketing Assets
- Check Roomio website for high-res downloads
- App Store screenshots
- Existing marketing materials/brochures
- Social media graphics

### Option 2: Create Custom Banners
- Use Canva, Figma, or Photoshop
- Follow specifications above
- Match Captur3d marketplace style for consistency
- Include WGAN partnership branding

### Option 3: Commission Professional Design
- Hire designer to create branded marketplace banners
- Provide brand guidelines (Roomio + WGAN)
- Reference Captur3d marketplace images for style

---

## ✅ Quick Checklist

Before uploading/updating images in HTML:

- [ ] All images are high resolution (1920x1080 or 1600x1000)
- [ ] File sizes optimized (< 500KB per image if possible)
- [ ] Roomio branding is clear and prominent
- [ ] WGAN partnership/branding included (optional but recommended)
- [ ] Key messaging is clear: pricing, speed, accuracy, templates
- [ ] Images are professional, clean, and on-brand
- [ ] YouTube video ID is correct (if using video)

---

## 🚀 How to Update Images in HTML

1. **Upload images** to WGAN server or host on Roomio CDN
2. **Copy image URLs** (e.g., `https://yourserver.com/roomio-hero.png`)
3. **Open `roomio-marketplace.html`** in text editor
4. **Find and replace** placeholder URLs with your new URLs
5. **Save and test** by opening HTML file in browser

**Example:**
```html
<!-- Line 71 - Replace this: -->
<div id="wp3d-intro" style="background-image: url('OLD_URL_HERE');">

<!-- With this: -->
<div id="wp3d-intro" style="background-image: url('https://yourserver.com/roomio-hero.png');">
```

---

## 📞 Need Help?

If you need:
- Design assistance
- Image optimization
- Help updating the HTML
- Custom graphics created

Let Devon know and I'll help create the assets or make the updates!

---

**Devon 🌐**  
*Image specifications for Roomio marketplace page*
