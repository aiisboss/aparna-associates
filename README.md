# Aparna & Associates - Complete Website Package

## 🎉 Welcome!

This is your complete, ready-to-deploy website! Everything is included and ready to upload to GitHub and Vercel.

---

## 📦 What's Included

### Core Files
- `index.html` - Homepage
- `about.html` - About page  
- `contact.html` - Contact page
- `company-registration-services.html` - Company registration category page
- `compliances-returns-services.html` - Compliances category page
- `license-registration-services.html` - License category page

### Service Pages (29 total)
All service pages are in the `services/` directory organized by category:

**Company Registration (10 pages):**
- services/company-registration/private-limited-company-registration.html
- services/company-registration/partnership-registration.html
- services/company-registration/llp-registration.html
- services/company-registration/opc-registration.html
- services/company-registration/proprietorship-registration.html
- services/company-registration/nidhi-company-registration.html
- services/company-registration/public-company-registration.html
- services/company-registration/producer-company-registration.html
- services/company-registration/nbfc-registration.html
- services/company-registration/mlm-company-registration.html

**Compliances (9 pages):**
- services/compliances/private-limited-company-compliances.html
- services/compliances/opc-compliances.html
- services/compliances/nidhi-company-compliances.html
- services/compliances/llp-compliances.html
- services/compliances/section-8-ngo-compliances.html
- services/compliances/producer-company-compliances.html
- services/compliances/gst-return-filing.html
- services/compliances/fssai-return-filing.html
- services/compliances/income-tax-return-filing.html

**Licenses (10 pages):**
- services/licenses/trademark-registration.html
- services/licenses/fssai-food-license.html
- services/licenses/import-export-code.html
- services/licenses/gst-registration.html
- services/licenses/gumasta-license.html
- services/licenses/pf-esi-registration.html
- services/licenses/msme-registration.html
- services/licenses/iso-certification.html
- services/licenses/mcd-trade-license.html
- services/licenses/shop-establishment-license.html

### Assets
- `css/style.css` - Complete stylesheet
- `js/script.js` - JavaScript functionality
- `images/` - Folder for your images (logo, photos)

---

## 🚀 Quick Start Guide

### Step 1: Add Your Images

Add these files to the `images/` folder:
1. `logo.png` - Your company logo
2. `office-desk.jpg` - Office desk photo
3. `office-signage.jpg` - Office signage photo
4. `favicon.png` - Website favicon (optional)

### Step 2: Upload to GitHub

1. **Create GitHub account** at github.com (if you don't have one)
2. **Create new repository:**
   - Click "New" button
   - Name: `aparnaassociates-website`
   - Description: "Aparna & Associates Company Website"
   - Public repository
   - Click "Create repository"

3. **Upload files:**
   - Click "uploading an existing file"
   - Drag and drop ALL files and folders
   - Commit changes

### Step 3: Deploy to Vercel

1. **Create Vercel account** at vercel.com
2. **Import project:**
   - Click "Add New..." → "Project"
   - Import from GitHub
   - Select `aparnaassociates-website` repository
   - Click "Deploy"

3. **Wait 2-3 minutes** for deployment
4. **Get your URL:** `aparnaassociates.vercel.app`

### Step 4: Connect Your Domain

1. **In Vercel:** 
   - Go to your project → Settings → Domains
   - Add `aparnaassociates.in`

2. **In GoDaddy:**
   - Manage DNS
   - Add these records:

   **Option A - Use Vercel nameservers (Recommended):**
   ```
   Name: @
   Type: A
   Value: 76.76.21.21

   Name: www
   Type: CNAME
   Value: cname.vercel-dns.com
   ```

   **Option B - Use Vercel DNS:**
   Follow instructions shown in Vercel dashboard

3. **Wait 2-24 hours** for DNS propagation

---

## ✏️ How to Update Content

### Update Text Content

1. **Open the HTML file** you want to edit (e.g., `index.html`)
2. **Find the text** you want to change
3. **Edit the text** between the HTML tags
4. **Save the file**
5. **Push to GitHub** (or upload via GitHub website)
6. **Vercel auto-deploys** in 1-2 minutes!

### Update Contact Information

**In ALL pages, update:**
- Phone numbers
- Email address
- Office address
- Social media links

**Find and replace:**
```html
+91 8076856909
+91 8076461946
pcsaparnasingh@gmail.com
Office No. 212, 2nd Floor, WZ-97...
```

### Update Pricing

**To add pricing back** (if you want):

Find: `Registration Time: 7-10 working days`

Add after: `Starting Price: ₹7,999`

---

## 🎨 Customization Guide

### Change Colors

Edit `css/style.css` at the top:

```css
:root {
    --primary-color: #1a365d;      /* Main blue */
    --accent-color: #d4af37;       /* Gold/Yellow */
    --text-dark: #2d3748;          /* Dark text */
    /* Change these values to your preferred colors */
}
```

### Change Fonts

In `css/style.css`, find:

```css
body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI'...
}
```

Replace with your preferred font.

---

## 📧 Contact Form Setup

The contact form uses **Formspree** (free service).

### Setup Formspree:

1. **Go to** formspree.io
2. **Sign up** (free)
3. **Create new form**
4. **Get form endpoint:** `https://formspree.io/f/YOUR_FORM_ID`

5. **Update `contact.html`:**
   
   Find:
   ```html
   <form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
   
   Replace `YOUR_FORM_ID` with your actual ID from Formspree.

**Alternative:** Use your own email directly:
```html
<form action="mailto:pcsaparnasingh@gmail.com" method="POST" enctype="text/plain">
```

---

## 🔧 Troubleshooting

### Website not loading?
- Check if files uploaded correctly to GitHub
- Check Vercel deployment logs
- Wait for DNS propagation (up to 24 hours)

### Form not working?
- Make sure Formspree endpoint is correct
- Check Formspree dashboard for submissions

### Images not showing?
- Make sure images are in `images/` folder
- Check image filenames match exactly (case-sensitive)
- Images should be web-optimized (JPEG/PNG, under 500KB each)

### Mobile menu not working?
- Make sure `js/script.js` is loaded correctly
- Check browser console for JavaScript errors

---

## 📱 Features Included

✅ **Responsive Design** - Works on all devices
✅ **SEO Optimized** - Meta tags, schema markup
✅ **Fast Loading** - Optimized code
✅ **Contact Forms** - Working contact form
✅ **WhatsApp Button** - Direct chat button
✅ **Social Media Links** - Facebook, LinkedIn, Instagram
✅ **Google Maps** - Office location (in contact page)
✅ **Mobile Menu** - Hamburger menu for mobile
✅ **Smooth Scrolling** - Smooth page navigation
✅ **Professional Design** - Beautiful, modern look

---

## 🎯 SEO Checklist

After deployment:

1. **Submit to Google:**
   - Google Search Console
   - Submit sitemap (you'll need to create one)

2. **Submit to Bing:**
   - Bing Webmaster Tools

3. **Create Google My Business:**
   - Link to new website

4. **Analytics:**
   - Add Google Analytics code (optional)

---

## 💰 Costs

**Total Cost: ₹0/month** (FREE!)

- GitHub: Free
- Vercel: Free (generous limits)
- Domain: ₹1,000/year (you already have)
- Formspree: Free (50 submissions/month)

---

## 🆘 Need Help?

**Common Issues:**

**Q: How do I add a new service page?**
A: Copy an existing service page, rename it, update the content.

**Q: How do I change the logo?**
A: Replace `images/logo.png` with your logo file (same name).

**Q: Can I add a blog?**
A: Yes! Create a `blog/` folder and add HTML files for each post.

**Q: How do I update after making changes?**
A: Just push to GitHub, Vercel auto-deploys in 1-2 minutes!

---

## 📞 Your Contact Information

Make sure to update these everywhere:

- Phone: +91 8076856909, +91 8076461946
- Email: pcsaparnasingh@gmail.com
- Office: Office No. 212, WZ-97, Paschim Vihar, Delhi 110063
- Facebook: https://www.facebook.com/share/1AXvSq29VJ/
- LinkedIn: https://www.linkedin.com/company/aparna-associates/
- Instagram: https://www.instagram.com/aparna_associates/
- WhatsApp: +91 8076856909

---

## 🎉 You're All Set!

Your website is ready to go live! 

**Next Steps:**
1. Add your images
2. Upload to GitHub
3. Deploy to Vercel
4. Connect your domain
5. Start getting clients!

**Good luck with your new website!** 🚀

---

## 📄 License

This website is created for Aparna & Associates. All rights reserved.

**Created:** January 2025
**Version:** 1.0
**Developer:** Custom built for Aparna & Associates
