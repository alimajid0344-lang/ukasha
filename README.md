# C2C Marketplace - Consumer-to-Consumer E-commerce Platform

A complete, modern consumer-to-consumer (C2C) marketplace website built with HTML5, CSS3, and JavaScript (Vanilla JS). This platform allows users to buy and sell products directly with each other, featuring user authentication, seller dashboards, product listings, and messaging between buyers and sellers.

## Features

### User Management
- User registration and login
- Seller and buyer accounts
- Profile management
- Secure authentication using localStorage

### Product Management
- Sellers can list products for sale
- Product categories (Electronics, Fashion, Furniture, etc.)
- Product images, descriptions, and pricing
- Condition tracking (New, Like New, Good, Fair, Poor)

### Marketplace Features
- Browse products by category
- Search functionality
- Shopping cart
- Product comparison
- Wishlist

### Communication
- Built-in messaging system between buyers and sellers
- Conversation management
- Real-time message updates

### Seller Dashboard
- Product management (add, edit, delete)
- Sales tracking
- Order management
- Profile customization

## Project Structure

```
xstore/
├── index.html           # Homepage with featured products
├── shop.html            # Product listing page with filters
├── cart.html            # Shopping cart page
├── checkout.html        # Checkout page
├── contact.html         # Contact form page
├── login.html           # User login page
├── register.html        # User registration page
├── seller-dashboard.html # Seller management dashboard
├── messages.html        # Messaging system
├── my-account.html      # User account page
├── wishlist.html        # Saved products page
├── compare.html         # Product comparison page
├── track-order.html     # Order tracking page
├── about-us.html        # About company page
├── blog.html            # Blog listing page
├── style.css            # Main stylesheet
└── main.js              # Main JavaScript file
```

## Getting Started

1. **Clone or download** the project files
2. **Open index.html** in your web browser
3. **Register** as a new user (choose seller option to list products)
4. **Login** to access your account
5. **Browse products** or list items for sale
6. **Use the messaging system** to communicate with other users

## Technology Stack

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with responsive design
- **JavaScript (ES6+)** - Interactive functionality
- **localStorage** - Client-side data persistence
- **Font Awesome** - Icons and UI elements

## Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## Data Storage

The application uses browser localStorage for data persistence:
- User accounts and profiles
- Product listings
- Shopping cart items
- Messages and conversations
- Order history

## Future Enhancements

- Real-time notifications
- Image upload functionality
- Payment integration
- Review and rating system
- Advanced search filters
- Mobile app version

## Contributing

This is a demonstration project. For production use, consider:
- Server-side data storage (database)
- User authentication security
- Payment processing integration
- Image hosting services
- Email notifications

## License

This project is for educational and demonstration purposes.
- **Page Sections** - Sidebars, breadcrumbs, headings
- **Footer** - Multi-column footer
- **Forms** - Input validation styles
- **Utility Classes** - Flexbox, spacing, text alignment
- **Responsive Design** - Mobile, tablet, desktop breakpoints
- **Animations** - Fade-in, slide effects
- **Loading States** - Preloader animations

**Color Scheme:**
- Primary Color: `#e95d2a` (Orange)
- Secondary Color: `#333333` (Dark Gray)
- Text Color: `#666666` (Gray)
- Light BG: `#f5f5f5` (Light Gray)
- Border Color: `#ebebeb` (Very Light Gray)

### JavaScript File (main.js)

The JavaScript file includes these modules:

1. **Utility Functions** - DOM manipulation, event handling, fade effects
2. **Navigation Module** - Mobile menu, mega menu, sticky header
3. **Search Module** - AJAX search, real-time results
4. **Shopping Cart** - Cart toggle, quantity controls, item removal
5. **Products Module** - Hover effects, filters, grid layout, add to cart
6. **Forms Module** - Form validation, submission handling
7. **Lazy Loading** - Image lazy loading with Intersection Observer
8. **Scroll Effects** - Scroll reveal animations
9. **Comparison Module** - Product comparison functionality
10. **Sliders Module** - Swiper carousel setup
11. **Analytics** - Google Analytics event tracking
12. **Mobile Menu** - Mobile-specific menu handling

## Getting Started

### Installation

1. **Download/Extract Files**
   - Place all files in a directory on your web server or local machine
   - Ensure all files are in the same directory

2. **File Linking**
   - All CSS is linked in the `<head>`: `<link rel="stylesheet" href="style.css">`
   - All JavaScript is linked before `</body>`: `<script src="main.js"></script>`

3. **Open in Browser**
   - Open `index.html` in your web browser
   - Or upload to web server and access via domain

### Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Customization

### Colors

Edit CSS variables in `style.css`:

```css
:root {
  --primary-color: #e95d2a;
  --secondary-color: #333333;
  --text-color: #666666;
  --light-bg: #f5f5f5;
  --border-color: #ebebeb;
  --white: #ffffff;
  --dark: #000000;
}
```

### Fonts

To change fonts, update the Google Fonts link in HTML files:

```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT:wght@400;500;600;700&display=swap" rel="stylesheet">
```

And update CSS:

```css
body {
  font-family: 'YOUR_FONT', sans-serif;
}
```

### Logo

Replace placeholder logo in header:

```html
<img src="path-to-your-logo.png" alt="Logo" width="143" height="53">
```

## Features

### Implemented Features

✅ Responsive Design (Mobile, Tablet, Desktop)
✅ Product Grid with Hover Effects
✅ Shopping Cart (Off-Canvas)
✅ Search Functionality
✅ Category Filtering
✅ Product Sorting
✅ Wishlist
✅ Product Comparison
✅ Contact Form
✅ Mobile Menu
✅ Sticky Header
✅ Form Validation
✅ Lazy Image Loading
✅ Animations & Transitions
✅ Analytics Ready

### Ready to Integrate

These features are template-ready for server-side integration:

- AJAX Product Search
- Add to Cart Functionality
- Wishlist Management
- Product Filtering
- Form Submission
- Payment Gateway
- Order Tracking

## Responsive Breakpoints

```css
Mobile: 480px (and below)
Tablet: 768px (and above)
Desktop: 992px (and above)
Large Desktop: 1490px (and above)
```

## Configuration

Update `ThemeConfig` in `main.js`:

```javascript
const ThemeConfig = {
  apiUrl: window.location.origin,
  ajaxUrl: '/wp-admin/admin-ajax.php',
  breakpoints: {
    mobile: 480,
    tablet: 768,
    desktop: 992
  }
};
```

## JavaScript API

### Utility Functions

```javascript
// Element Selection
Utils.getElement(selector)
Utils.getElements(selector)
Utils.elementExists(selector)

// Class Management
Utils.addClass(element, className)
Utils.removeClass(element, className)
Utils.toggleClass(element, className)
Utils.hasClass(element, className)

// Events
Utils.addEventListener(selector, event, callback)

// Effects
Utils.fadeIn(element, duration)
Utils.fadeOut(element, duration)
Utils.scrollToElement(selector, offset)

// Device Detection
Utils.isMobile()
Utils.isTablet()
Utils.getViewportWidth()
```

### Using the Theme

In development mode (localhost), access utilities globally:

```javascript
console.log(ThemeConfig)
console.log(ThemeUtils)
```

## Page Template

Basic page structure used across all pages:

```html
<!DOCTYPE html>
<html lang="en-US">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body class="page-classname">
    <!-- Header -->
    <!-- Main Content -->
    <!-- Footer -->
    <script src="main.js"></script>
</body>
</html>
```

## Form Fields & Validation

Supported validation types:

- **Required Fields** - Any field with `required` attribute
- **Email** - `type="email"`
- **Phone** - `name="phone"` with format validation
- **Min Length** - `minlength` attribute

## Utility Classes

### Text Alignment
- `.text-center` - Center align
- `.text-left` - Left align
- `.text-right` - Right align

### Flexbox
- `.flex` - Display flex
- `.justify-content-center` - Center flex items
- `.justify-content-between` - Space between
- `.align-items-center` - Align center
- `.flex-wrap` - Wrap flex items

### Spacing
- `.mt-10`, `.mt-20`, `.mt-30`, `.mt-40` - Margin top
- `.mb-10`, `.mb-20`, `.mb-30`, `.mb-40` - Margin bottom
- `.pt-10`, `.pt-20`, `.pt-30`, `.pt-40` - Padding top
- `.pb-10`, `.pb-20`, `.pb-30`, `.pb-40` - Padding bottom

### Visibility
- `.hidden` - Display none
- `.visible` - Display block

## Product Grid

The products grid automatically adjusts columns based on viewport:

- Mobile (< 480px): 1 column
- Tablet (480-768px): 2 columns
- Desktop (768-1200px): 3 columns
- Large Desktop (1200px+): 4 columns

## Performance Tips

1. **Optimize Images** - Use appropriate image sizes
2. **Lazy Loading** - Images load on scroll (already implemented)
3. **Minify CSS/JS** - For production deployment
4. **Compress Assets** - Use gzip compression
5. **CDN** - Serve static files from CDN

## Deployment

### Local Testing
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

### Web Server
1. Upload all files to web server
2. Ensure .htaccess is configured for clean URLs (if applicable)
3. Test all links and functionality
4. Set up SSL certificate (HTTPS)

## Browser DevTools

In the browser console (when on localhost):

```javascript
// Access utilities
ThemeUtils.isMobile()  // Check if mobile device
ThemeUtils.getViewportWidth()  // Get viewport width
ThemeUtils.scrollToElement('.products-loop')  // Smooth scroll

// Access config
ThemeConfig  // View theme configuration
```

## Support & Customization

This is a fully customizable, standalone HTML/CSS/JS website. To add:

- **Backend** - Integrate with your server (PHP, Node.js, Python, etc.)
- **Database** - Connect to your database for dynamic content
- **Payment Gateway** - Integrate Stripe, PayPal, etc.
- **Email Service** - Add SendGrid, Mailgun, etc.
- **CDN** - Use Cloudflare, AWS CloudFront, etc.

## License

This website template is provided as-is for use and modification.

## Version

**XStore Elementor v1.0**
Last Updated: April 2026

## Files Included

- 11 HTML pages
- 1 CSS stylesheet (600+ lines)
- 1 JavaScript file (600+ lines)
- 1 README file (this file)

## Total Size

- HTML: ~150 KB
- CSS: ~60 KB
- JavaScript: ~45 KB
- **Total: ~255 KB** (uncompressed)

## Notes

- All links are relative and work locally or on web server
- No external dependencies except Font Awesome and Google Fonts
- Fully responsive and mobile-optimized
- SEO-friendly HTML structure
- Accessibility-ready (ARIA labels, semantic HTML)
- Easy to customize and extend

---

**Thank you for using XStore Elementor!**

For questions or suggestions, refer to the code comments in each file.
