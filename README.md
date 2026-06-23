# Zara Noor | Mehndi Artist Portfolio

A stunning, scroll-driven portfolio website for a professional mehndi artist, inspired by the design language of wowfactories.com.

![Preview](https://via.placeholder.com/1200x630/c9a96e/0a0c0a?text=Zara+Noor+Mehndi+Artist)

**Live Demo:** https://infoyashkgf-collab.github.io/mehndi-portfolio/

---

## ✨ Features

- **Three.js Hero Background** - Procedural 3D mandala that rotates and responds to mouse movement
- **GSAP Scroll Animations** - Smooth section reveals and scroll-triggered effects
- **Lenis Smooth Scrolling** - Premium scroll feel
- **Scroll-Triggered Image Sequence** - Images change as you scroll (WowFactories signature effect)
- **Before/After Morph** - Crossfade effect on scroll
- **Responsive Design** - Works on mobile, tablet, and desktop
- **Custom Cursor Glow** - Subtle glow effect follows cursor

---

## 🎨 Design System

### Colors
```css
--gold: #c9a96e
--gold-light: #e8d5a3
--gold-dark: #8b6914
--henna: #8b4513
--henna-deep: #5c2e0a
--green: #2d5a27
--bg-dark: #0a0c0a
--text: #e8d5a3
--text-dim: #8a7a6a
```

### Typography
- **Headings:** Playfair Display
- **Body:** Cormorant Garamond
- **Accent:** Cormorant SC

---

## 🚀 Quick Start

### Local Development
1. Clone or download this repository
2. Open `index.html` in your browser
3. That's it! No build step required.

### GitHub Pages Deployment
1. Push all files to GitHub repository
2. Go to Settings → Pages
3. Select source: `main` branch
4. Save and wait ~1 minute
5. Your site is live at: `https://mehndiwala.github.io/mehndi-portfolio/`

---

## 📁 File Structure

```
mehndi-portfolio/
├── index.html           # Main HTML file with all sections
├── README.md            # This file
├── images/
│   ├── gallery/         # Gallery section photos
│   ├── sequences/       # Before/after images
│   └── hero/            # Hero background (optional)
└── css/                 # (Optional - styles are in index.html)
└── js/                  # (Optional - scripts are in index.html)
```

---

## 🛠️ Technologies Used

| Technology | Purpose | CDN Link |
|------------|---------|----------|
| **Three.js** | 3D mandala background | https://threejs.org |
| **GSAP** | Scroll animations | https://greensock.com/gsap |
| **ScrollTrigger** | Scroll-based triggers | GSAP Plugin |
| **Lenis** | Smooth scrolling | https://github.com/darkroomengineering/lenis |
| **Phosphor Icons** | Icon library | https://phosphoricons.com |
| **Google Fonts** | Typography | Playfair Display, Cormorant Garamond |

---

## 📝 Customization Guide

### Change Artist Details

Open `index.html` and search for:
- `Zara Noor` → Your artist name
- `Delhi, India` → Your location
- `+91 97168 82882` → Your phone
- `zara.noor@mehndi.com` → Your email
- `@zaranoor_mehndi` → Your Instagram

### Replace Gallery Images

Replace files in `images/gallery/`:
- `mehndi-01.jpg` → Bridal design
- `mehndi-02.jpg` → Arabic design
- `mehndi-03.jpg` → Traditional art
- `mehndi-04.jpg` → Contemporary
- `mehndi-05.jpg` → Party mehndi
- `mehndi-06.jpg` → Festival special

### Change Colors

In `index.html`, find the `:root` section in CSS and modify the color variables.

### Adjust Animations

In the `<script>` section at the bottom, find GSAP configurations:
- Change `duration` for animation speed
- Modify `stagger` for delay between elements
- Adjust `ease` for different animation curves

---

## 📊 Performance Tips

1. **Optimize Images** - Use WebP or AVIF format for faster loading
2. **Lazy Loading** - Add `loading="lazy"` to images below the fold
3. **Minify CSS/JS** - Use online tools to compress code
4. **CDN Links** - Keep external libraries on CDN for caching

---

## 🎯 Section Breakdown

| Section | Description | Effect |
|---------|-------------|--------|
| **01 Hero** | Artist name + location | Three.js mandala background |
| **02 Sequence** | Featured work showcase | Scroll-triggered image swap |
| **03 Before/After** | Transformation reveal | Crossfade morph effect |
| **04 Gallery** | 6 design categories | Staggered card reveal |
| **05 About** | Bio + stats | Counter animation |
| **06 Contact** | Booking info + form | Social links |
| **07 Footer** | Copyright | Simple fade |

---

## 🔧 Troubleshooting

### Images Not Loading
- Check file paths are correct
- Ensure images are in `images/gallery/` folder
- Verify file names match exactly (case-sensitive)

### Animations Not Working
- Check internet connection (GSAP loads from CDN)
- Open browser console for errors
- Try clearing browser cache

### Three.js Not Rendering
- Check browser supports WebGL
- Update to latest browser version
- Check console for WebGL errors

---

## 📱 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 90+ | ✅ Full |
| Firefox | 88+ | ✅ Full |
| Safari | 14+ | ✅ Full |
| Edge | 90+ | ✅ Full |
| Mobile | iOS 14+/Android 10+ | ✅ Full |

---

## 🎨 Credits

- **Design Inspiration:** wowfactories.com
- **Icons:** Phosphor Icons
- **Fonts:** Google Fonts
- **Stock Photos:** Pexels, Unsplash
- **3D Library:** Three.js
- **Animations:** GSAP

---

## 📄 License

This project is open source and available for personal and commercial use.

---

## 📞 Support

For questions or issues:
- Open an issue on GitHub
- Email: support@example.com

---

**Made with ❤️ for mehndi artists everywhere**
