# 🛍️ Impulse Theme - Shopify

> Premium Shopify Theme by Archetype Themes

| Property | Value |
|----------|-------|
| **Theme Name** | Impulse |
| **Version** | 6.0.1 |
| **Author** | Archetype Themes |
| **Platform** | Shopify Online Store 2.0 |
| **Documentation** | [archetypethemes.co/blogs/impulse](https://archetypethemes.co/blogs/impulse) |
| **Support** | [archetypethemes.co/pages/support#impulse](https://archetypethemes.co/pages/support#impulse) |

---

## 📁 Theme Structure

```
shopify-theme/
├── 📂 assets/              # CSS, JS, images, icons (19 files)
│   ├── theme.css           # Main stylesheet (~238KB)
│   ├── theme.js            # Main JavaScript (~245KB)
│   ├── vendor-scripts-v11.js  # Third-party libraries (~143KB)
│   ├── country-flags.css   # Multi-currency flag sprites
│   └── ico-*.svg           # Various SVG icons
│
├── 📂 blocks/              # Reusable content blocks (2 files)
│
├── 📂 config/              # Theme configuration (2 files)
│   ├── settings_schema.json   # Theme settings definitions
│   └── settings_data.json     # Current theme settings values
│
├── 📂 layout/              # Theme layouts (4 files)
│   ├── theme.liquid        # Main store layout
│   ├── password.liquid     # Password page layout
│   ├── gift_card.liquid    # Gift card layout
│   └── layouthub.liquid    # LayoutHub integration
│
├── 📂 locales/             # Translation files (12 files)
│   ├── en.default.json     # English (default)
│   ├── de.json             # German
│   ├── es.json             # Spanish
│   ├── fr.json             # French
│   ├── it.json             # Italian
│   └── pt-*.json           # Portuguese (BR/PT)
│
├── 📂 sections/            # Page sections (46 files)
│   ├── header.liquid       # Site header & navigation
│   ├── footer.liquid       # Site footer
│   ├── slideshow.liquid    # Hero slideshow
│   ├── featured-collection.liquid
│   ├── featured-product.liquid
│   ├── promo-grid.liquid   # Promotional grid layouts
│   ├── testimonials.liquid
│   ├── faq.liquid          # FAQ accordion
│   ├── newsletter.liquid
│   ├── map.liquid          # Google Maps integration
│   └── ... (46 total)
│
├── 📂 snippets/            # Reusable Liquid code (62 files)
│   ├── product-grid-item.liquid   # Product card component
│   ├── product-template.liquid    # Product page template
│   ├── cart-drawer.liquid         # Ajax cart drawer
│   ├── drawer-menu.liquid         # Mobile menu drawer
│   ├── header-*.liquid            # Header components
│   ├── footer-*.liquid            # Footer components
│   ├── social-*.liquid            # Social media components
│   └── ... (62 total)
│
└── 📂 templates/           # Page templates (26 files + customers/)
    ├── customers/          # Customer account templates (7 files)
    ├── index.json          # Homepage template
    ├── product.json        # Default product template
    ├── collection.json     # Default collection template
    ├── page.json           # Default page template
    ├── blog.json           # Blog listing template
    ├── article.json        # Blog article template
    ├── cart.json           # Cart template
    ├── search.json         # Search results template
    └── ... (26 total)
```

---

## ✨ Key Features

### 🎨 Design & Styling

| Feature | Description |
|---------|-------------|
| **Color Customization** | Full control over body, header, footer, drawer, button, sale tag, cart indicator colors |
| **Typography** | Custom fonts (Poppins default), adjustable size, spacing, line-height |
| **Button Styles** | Square, round-slight, round, angled options |
| **Icon Customization** | Adjustable weight (2-7px) and linecaps (miter/round) |
| **RTL Support** | Right-to-left text direction for Hebrew, Arabic, etc. |
| **Animations** | Smooth transitions with optional disable toggle |

### 🛒 E-commerce Features

| Feature | Description |
|---------|-------------|
| **Cart Types** | Page-based or drawer-based cart |
| **Quick View/Shop** | Modal product quick shop |
| **Product Swatches** | Color/variant swatches (round or square) |
| **Hover Images** | Secondary image on product hover |
| **Product Reviews** | Integration-ready for Shopify Product Reviews app |
| **Save Amount Display** | Show savings in dollar or percentage |
| **Vendor Display** | Optional product vendor display |
| **Image Aspect Ratios** | Natural, square, landscape, portrait |

### 🔍 Search & Navigation

| Feature | Description |
|---------|-------------|
| **Predictive Search** | Live search suggestions with product images |
| **Search Scope** | Products, pages, articles, collections |
| **Breadcrumbs** | Optional breadcrumb navigation |
| **Mega Menu** | Desktop mega navigation support |
| **Mobile Drawer** | Full-featured mobile menu drawer |

### 📱 Sections Available (46 total)

#### Homepage & Marketing
- `slideshow.liquid` - Hero slideshow/banner
- `hero-video.liquid` - Video hero section
- `promo-grid.liquid` - Promotional grid layouts
- `featured-collection.liquid` - Product collection showcase
- `featured-collections.liquid` - Multiple collections showcase
- `featured-product.liquid` - Single product highlight
- `featured-video.liquid` - Video embed section
- `testimonials.liquid` - Customer testimonials
- `logo-list.liquid` - Brand/partner logos
- `newsletter.liquid` - Email subscription
- `newsletter-popup.liquid` - Pop-up newsletter
- `text-and-image.liquid` - Text with image layout
- `text-columns.liquid` - Multi-column text
- `text-with-icons.liquid` - Features with icons
- `rich-text.liquid` - Rich text content
- `background-image-text.liquid` - Image with text overlay
- `background-video-text.liquid` - Video with text overlay
- `map.liquid` - Google Maps integration
- `faq.liquid` - FAQ accordion
- `contact-form.liquid` - Contact form

#### Product & Collection
- `main-product.liquid` - Product page main content
- `product-full-width.liquid` - Full-width product variant
- `product-recommendations.liquid` - Product recommendations
- `store-availability.liquid` - Store pickup availability
- `main-collection.liquid` - Collection page main content
- `collection-header.liquid` - Collection header/banner
- `Premium-Product-Hotspot.liquid` - Interactive hotspots

#### Blog
- `blog-template.liquid` - Blog listing template
- `article-template.liquid` - Blog article template
- `blog-posts.liquid` - Blog posts grid

#### Other
- `recently-viewed.liquid` - Recently viewed products
- `advanced-content.liquid` - Advanced content blocks
- `premium-scroll-gallery.liquid` - Scroll-based gallery
- `apps.liquid` - App block section

### 📦 Snippets Available (62 total)

#### Product Components
- `product-grid-item.liquid` - Product card for grids
- `product-template.liquid` - Full product template
- `product-form.liquid` - Add to cart form
- `product-images.liquid` - Product image gallery
- `product-inventory.liquid` - Stock level display
- `product-description.liquid` - Product description
- `variant-button.liquid` - Variant button selector
- `variant-dropdown.liquid` - Variant dropdown selector
- `quantity-input.liquid` - Quantity selector

#### Cart Components
- `cart-drawer.liquid` - Ajax cart drawer
- `cart-item.liquid` - Cart line item

#### Navigation & Layout
- `drawer-menu.liquid` - Mobile menu drawer
- `header-desktop-nav.liquid` - Desktop navigation
- `header-icons.liquid` - Header icon buttons
- `header-logo-block.liquid` - Logo component
- `announcement-bar.liquid` - Top announcement bar
- `breadcrumbs.liquid` - Breadcrumb navigation

#### Footer Components
- `footer-menu.liquid` - Footer navigation
- `footer-newsletter.liquid` - Footer newsletter form
- `footer-custom-text.liquid` - Custom footer text
- `footer-logo.liquid` - Footer logo

#### Collection Components
- `collection-grid.liquid` - Collection grid layout
- `collection-grid-item.liquid` - Collection card
- `collection-grid-filters.liquid` - Filter sidebar
- `collection-grid-filters-form.liquid` - Filter form

#### Social & SEO
- `social-icons.liquid` - Social media icons
- `social-sharing.liquid` - Share buttons
- `social-meta-tags.liquid` - Open Graph/Twitter meta
- `seo-title.liquid` - SEO title tag

#### Utilities
- `pagination.liquid` - Pagination controls
- `newsletter-form.liquid` - Newsletter form
- `search-bar.liquid` - Search input
- `css-variables.liquid` - CSS custom properties
- `font-face.liquid` - Font declarations

---

## 🌐 Language Support

| Language | File |
|----------|------|
| English (Default) | `en.default.json` |
| German | `de.json` |
| Spanish | `es.json` |
| French | `fr.json` |
| Italian | `it.json` |
| Portuguese (Brazil) | `pt-BR.json` |
| Portuguese (Portugal) | `pt-PT.json` |

---

## ⚙️ Theme Settings Categories

1. **Colors** - All color customizations
2. **Typography** - Fonts, sizes, spacing
3. **Products** - Product display settings
4. **Product Tiles** - Grid product card settings
5. **Collection Tiles** - Collection card settings
6. **Cart** - Cart behavior and icons
7. **Social Media** - Social links and sharing
8. **Favicon** - Site icon
9. **Search** - Search functionality settings
10. **Extras** - Breadcrumbs, RTL, animations

---

## 🔌 Integrations

- **LayoutHub** - Page builder integration (`layouthub.liquid`, snippets)
- **Loox** - Product reviews (metafield integration in `theme.liquid`)
- **Shopify Product Reviews** - Built-in support
- **Google Maps** - Map section support
- **Multi-currency** - Country flag sprites included

---

## 📜 Template Variants

### Product Templates
- `product.json` - Default product page
- `product.brand-story.json` - With brand story section
- `product.gift-card.json` - Gift card product
- `product.preorder.json` - Pre-order products
- `product.product-landing.json` - Landing page style
- `product.modal.json` - Modal/popup view

### Collection Templates
- `collection.json` - Default collection
- `collection.no-sidebar.json` - Without filter sidebar
- `collection.no-promos.json` - Without promotional blocks
- `collection.collection-landing.json` - Landing page style

### Page Templates
- `page.json` - Default page
- `page.full-width.json` - Full width layout
- `page.about.json` - About us page
- `page.contact.json` - Contact page
- `page.faq.json` - FAQ page

---

## 🛠️ Development Notes

### File Naming Conventions
- `.liquid` - Liquid template files
- `.json` - JSON template/config files
- `.css.liquid` - CSS with Liquid variables
- `.svg.liquid` - SVG with Liquid variables

### CSS Architecture
- Main stylesheet: `assets/theme.css` (238KB)
- CSS variables defined in: `snippets/css-variables.liquid`
- Font faces in: `snippets/font-face.liquid`

### JavaScript Architecture
- Main script: `assets/theme.js` (245KB)
- Vendor libraries: `assets/vendor-scripts-v11.js` (143KB)

### Global Theme Object
```javascript
window.theme = {
  routes: { home, cart, cartPage, cartAdd, cartChange, search },
  strings: { soldOut, unavailable, inStockLabel, ... },
  settings: { 
    cartType, moneyFormat, saveType, 
    productImageSize, quickView, 
    predictiveSearch, themeName, themeVersion 
  }
};
```

---

## 📋 Quick Reference

### Key Liquid Objects Used
- `shop` - Store information
- `settings` - Theme settings
- `product` - Product data
- `collection` - Collection data
- `cart` - Cart data
- `customer` - Customer data
- `request` - Current request info
- `routes` - URL routes

### Common Filters
- `asset_url` - Asset CDN URL
- `img_url` - Image resizing
- `money` - Currency formatting
- `t` - Translation lookup
- `json` - JSON encoding

---

## 📞 Support

- **Documentation**: https://archetypethemes.co/blogs/impulse
- **Support**: https://archetypethemes.co/pages/support#impulse
- **Theme Author**: Archetype Themes

---

*Last Updated: January 2026*
