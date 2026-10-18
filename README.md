# shoppingwebpage
Responsive e-commerce fashion store website built with HTML5 and CSS3
# 🛍️ E Shopper – Responsive E-Commerce Fashion Website

A responsive e-commerce landing page for a fashion store, built with **HTML5** and **CSS3** only (no JavaScript, no frameworks).

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Design-Responsive-brightgreen)

---

## 📌 Overview

E Shopper is a static front-end template for an online clothing store. It includes the key sections of a typical shop homepage: header with search, category sidebar, hero banner, product listings, offers, newsletter signup and a full footer. The layout is built with Flexbox and adapts to mobile, tablet and desktop screens.

## ✨ Features

- **Top bar** with quick links (FAQs, Help, Support) and social icons
- **Header** with logo, search bar, and wishlist/cart icons
- **Category sidebar** listing clothing categories (Dresses, Shirts, Jeans, etc.)
- **Main navigation** with login/register links
- **Hero banner** with discount call-to-action
- **Feature highlights** – Quality Product, Free Shipping, 14-Day Return, 24/7 Support
- **Category cards** (Men's, Women's, Baby's dresses, Accessories, Bags, Shoes)
- **Offer banners** for seasonal collections
- **Product grids** – "Trendy Products" and "Just Arrived" (8 cards each, with old/new price and View Detail / Add To Cart actions)
- **Newsletter subscription** section
- **Vendor / brand logos** strip
- **Footer** with contact info, quick links, newsletter form and payment icons
- Fully **responsive** layout

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure with semantic tags (`header`, `section`, `aside`, `article`, `footer`) |
| CSS3 | Styling, Flexbox layout, media queries |
| [Font Awesome 6.0](https://fontawesome.com/) | Icons (loaded via CDN) |

## 📁 Project Structure

```
shoppingwebpage/
├── index.html      # Main page markup
├── index.css       # All styles and responsive rules
├── Img/            # Images (banners, categories, products, vendors, payments)
└── README.md
```

## 🚀 Getting Started

### Prerequisites
Only a modern web browser is needed. There is no installation or build step.

### Run locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/akashnpatil2005/shoppingwebpage.git
   ```
2. **Go into the project folder**
   ```bash
   cd shoppingwebpage
   ```
3. **Open `index.html`** in your browser (double-click it, or use the *Live Server* extension in VS Code).

> **Note:** An internet connection is needed to load the Font Awesome icons from the CDN.

## 📱 Responsive Design

| Screen | Breakpoint | What changes |
|--------|-----------|--------------|
| Large tablet | `max-width: 991px` | Category sidebar becomes full width; smaller hero banner |
| Tablet / mobile | `max-width: 768px` | Top bar, header and navigation stack vertically; search bar goes full width |
| Small mobile | `max-width: 480px` | Smaller headings and logo; reduced side padding |

## 🎨 Customization

- **Colors:** The theme uses a dusty rose accent (`#D19C97`) and light blue backgrounds (`#EDF1FF`). Search and replace these values in `index.css` to change the palette.
- **Content:** Edit product names, prices, categories and contact details in `index.html`.
- **Images:** Replace the files in the `Img/` folder, keeping the same file names (or update the `src` paths).
- **Font:** Change the `font-family` in the `*` rule at the top of `index.css`.

## ⚠️ Notes

- The image folder is named `Img` (capital **I**). On case-sensitive systems (Linux servers, GitHub Pages), the folder name must match the `src` paths exactly, or images will not load.
- Forms (search, subscribe, newsletter) are visual only and are not connected to a backend.

## 🗺️ Future Improvements

- [ ] Add a mobile hamburger menu and working category dropdown
- [ ] Make the cart, wishlist and search functional with JavaScript
- [ ] Add separate Shop, Shop Detail and Contact pages
- [ ] Connect the newsletter and subscribe forms to a backend or form service
- [ ] Add a working hero carousel
- [ ] Improve accessibility (ARIA labels, descriptive alt text, color contrast)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**Your Name**
- GitHub: [@akashnpatil2005](https://github.com/akashnpatil2005)


