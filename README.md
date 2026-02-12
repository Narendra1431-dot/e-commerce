# Fashion Store E-Commerce Website

A modern, animated e-commerce website built with HTML, CSS, and JavaScript featuring a complete shopping experience with user authentication, product management, and smooth animations.

## 🚀 Features

### 🔐 Authentication System
- **Flexible Login**: Accepts any email/password combination for easy testing
- **Auto User Creation**: New users are created automatically on first login
- **Persistent Sessions**: User data stored in localStorage
- **Demo Credentials**: Pre-configured demo user available

### 🛒 Shopping Features
- **Product Catalog**: Real product images and categories
- **Shopping Cart**: Add/remove items with quantity management
- **Wishlist**: Save favorite items for later
- **Search Functionality**: Real-time product search by name
- **Product Sorting**: Sort by price (low to high, high to low) and rating
- **Product Details**: Modal view with larger images and full descriptions

### 🎨 Animations & UI
- **13+ Animation Types**: Including bounce, fade, slide, glow, shimmer effects
- **Smooth Transitions**: CSS-based animations for optimal performance
- **Interactive Elements**: Hover effects, button presses, and visual feedback
- **Responsive Design**: Works on desktop and mobile devices
- **Dark Mode Support**: Toggle between light and dark themes

### 📱 Additional Features
- **Order History**: View past orders (stored in localStorage)
- **Checkout Flow**: Complete order process with address and payment forms
- **Toast Notifications**: User feedback for all actions
- **Coupon System**: Apply discount codes during checkout

## 🎭 Animation Library

The site includes a comprehensive animation library with the following effects:

- `bounceIn` - Bouncy entrance animation
- `fadeInUp` - Fade in from bottom
- `slideInLeft/Right` - Slide in from sides
- `pulseGlow` - Pulsing glow effect
- `shimmer` - Shimmering highlight effect
- `slideInFromBottom` - Slide up from bottom
- `fadeInScale` - Scale and fade in
- `colorShift` - Color gradient animation
- `textGlow` - Glowing text effect
- `borderGlow` - Glowing border effect
- `iconBounce` - Bouncing icon animation
- `cardLift` - Card hover lift effect
- `buttonPress` - Button press feedback

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with animations and responsive design
- **JavaScript (ES6+)**: Interactive functionality and data management
- **Font Awesome**: Icons and visual elements
- **Google Fonts**: Inter font family for typography
- **localStorage**: Client-side data persistence

## 📁 Project Structure

```
E-commerce/
├── index.html          # Main e-commerce homepage
├── login.html          # User authentication page
├── README.md           # Project documentation
└── Untitled-1.html     # Additional page (if needed)
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser

### Installation & Usage

1. **Clone or Download** the project files
2. **Open `login.html`** in your web browser to start
3. **Login with any credentials** (or use demo: demo@example.com / demo123)
4. **Explore the store** - browse products, add to cart, use search/sort features

### Demo Credentials
- **Email**: demo@example.com
- **Password**: demo123

*Note: The login accepts any email/password combination for easy testing*

## 🎯 Key Functionality

### Login System
- Enter any email and password to log in
- New users are created automatically
- Session persists across browser refreshes

### Product Management
- Browse products by category
- Click product images to view details in modal
- Add items to cart or wishlist
- Use search bar to filter products
- Sort by price or rating

### Shopping Experience
- Add/remove items from cart
- Apply coupon codes (SAVE10 for 10% off)
- Complete checkout with address and payment info
- View order history

### Animations
- Login page features bouncy entrance
- Product cards have hover animations
- Buttons provide press feedback
- Smooth transitions throughout the interface

## 🎨 Customization

### Adding New Animations
Add new keyframes in the CSS section and create corresponding utility classes:

```css
@keyframes newAnimation {
    /* Define your animation */
}

.animate-new-animation {
    animation: newAnimation 0.8s ease;
}
```

### Modifying Products
Edit the `products` array in `index.html` to add new items:

```javascript
{
    id: 1,
    name: "Product Name",
    price: 999,
    image: "image_url",
    category: "Category",
    rating: 4.5,
    description: "Product description"
}
```

## 📱 Responsive Design

The website is fully responsive and works on:
- **Desktop**: Full feature set with all animations
- **Tablet**: Optimized layout and touch interactions
- **Mobile**: Streamlined interface with mobile-friendly controls

## 🔧 Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## 📝 Notes

- All data is stored locally in the browser (localStorage)
- No backend server required - fully client-side application
- Animations use CSS transforms for optimal performance
- Product images are loaded from external URLs

## 🤝 Contributing

Feel free to enhance the project by:
- Adding new animation effects
- Implementing additional e-commerce features
- Improving the UI/UX design
- Adding more product categories

## 📄 License

This project is open source and available under the MIT License.

---

**Enjoy shopping with smooth animations! 🛍️✨**
