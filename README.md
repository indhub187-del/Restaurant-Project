# GourmetDash - Restaurant Food Delivery Application

## 🎉 Features Implemented

### ✅ Fully Responsive Design

- Mobile-first approach with hamburger menu
- Adapts perfectly to all screen sizes (mobile, tablet, desktop)
- Smooth animations and transitions

### ✅ Complete Cart Functionality

- Add items to cart with quantity management
- Real-time cart count updates
- Persistent cart using localStorage
- Increase/decrease quantities
- Remove items from cart
- Automatic price calculation with delivery fee

### ✅ Location Management

- Detect current location using browser geolocation
- Manual address entry with landmark and phone number
- Saved to localStorage for future orders

### ✅ Payment Integration

- Multiple payment methods:
  - UPI (Google Pay, PhonePe, Paytm)
  - Credit/Debit Card
  - Digital Wallets
  - Cash on Delivery
- Visual payment method selection

### ✅ Order Success Screen

- Beautiful confirmation screen with animated success icon
- Complete order details:
  - Order ID
  - Total amount
  - Payment method
  - Delivery address
  - Estimated delivery time
  - List of ordered items

### ✅ Help & Support

- 24/7 customer support details
- FAQ section with common questions
- Safety and hygiene information
- Direct call and email links

### ✅ Offers & Deals

- Multiple promotional offers:
  - 50% OFF on first order
  - Free delivery
  - Flat discounts
  - Weekend specials
- Beautiful gradient card designs

### ✅ Working Navigation

- ✅ Search - Focuses on search bar and filters restaurants
- ✅ Offers - Opens offers modal with all deals
- ✅ Help - Opens help & support modal
- ✅ Login/Register - Shows user greeting
- ✅ Cart - Opens cart panel with all items

### ✅ Enhanced UI/UX

- Swiggy-like modern design
- Smooth animations and micro-interactions
- Loading states for all actions
- Toast notifications for user feedback
- Glassmorphism and modern gradients

### ✅ All Images Working

- All restaurant images from Unsplash
- All menu item images from Unsplash
- No broken images

## 🚀 How to Use

### 1. **Browse Restaurants**

- Scroll through the 20 restaurants on the homepage
- Each card shows cuisine type, rating, delivery time, and cost
- Click on any restaurant card to view their menu

### 2. **Order Food**

- Click on a restaurant to open their menu
- Browse through menu items
- Click "ADD" button to add items to cart
- Click the same button again to increase quantity

### 3. **View Cart**

- Click on the "Cart" button in the header
- View all added items with images
- Adjust quantities using +/- buttons
- Remove items with trash icon
- See subtotal, delivery fee, and grand total

### 4. **Checkout Process**

1.  Click "Checkout Now" in cart
2.  **Location**: Enter delivery address or use current location
3.  **Payment**: Select payment method (UPI/Card/Wallet/COD)
4.  Click "Place Order"
5.  **Success**: View order confirmation with all details

### 5. **Use Other Features**

- **Search**: Type restaurant name or cuisine to filter
- **Offers**: Click to see all available deals
- **Help**: Get support information and FAQs

## 📱 Responsive Behavior

### Mobile View (< 768px)

- Hamburger menu for navigation
- Full-width cart panel
- Single column restaurant grid
- Stacked footer sections
- Touch-optimized buttons

### Tablet View (768px - 1024px)

- Two-column restaurant grid
- Optimized spacing
- Readable font sizes

### Desktop View (> 1024px)

- Multi-column restaurant grid
- Sidebar cart panel
- Full navigation visible
- Hover effects enabled

## 🎨 Design Highlights

- **Color Scheme**:
  - Primary: Orange (#ff5200)
  - Dark: #1c1c1c
  - Light backgrounds with proper contrast

- **Typography**: Outfit font family (Google Fonts)

- **Animations**:
  - Fade in/out modals
  - Slide animations for cart items
  - Scale effects on buttons and cards
  - Rotation on close buttons

## 💾 Data Persistence

- **Cart**: Saved in localStorage, persists across sessions
- **Location**: Saved for future orders
- **Orders**: Order history maintained in localStorage

## 🛠️ Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern features (Grid, Flexbox, Animations)
- **JavaScript (ES6+)**:
  - Classes for organization
  - LocalStorage API
  - Geolocation API
  - Event handling
  - DOM manipulation

## 📦 Files Structure

```
restaurant project/
├── index.html          # Main HTML file with all modals
├── style.css           # Complete styling (1300+ lines)
├── app.js             # JavaScript functionality
├── login.html         # Login page (existing)
└── images/            # Images folder
    ├── logo.png       # App logo
    └── banner.png     # Hero banner
```

## 🎯 Order Flow

1. **Browse** → Select Restaurant → View Menu
2. **Add to Cart** → Adjust Quantities
3. **Checkout** → Enter Location
4. **Payment** → Select Method
5. **Confirmation** → Order Placed! 🎉

## 🔧 Notes

### Logo Image

The app references `images/logo.png`. You can:

1. Create a 100x100px logo with "GD" or "GourmetDash" text
2. Use any food delivery icon
3. Or update line 33 in index.html to use a different image

### Banner Image

The hero section references `images/banner.png`. You can:

1. Use any food photography image (1920x400px recommended)
2. Download from Unsplash
3. Or remove the `url()` part from style.css line 104 to use gradient only

## ✨ Special Features

1. **Smart Cart**: Prevents duplicate entries, manages quantities automatically
2. **Notifications**: Toast messages for all actions
3. **Click Outside**: Close modals by clicking outside
4. **Keyboard Support**: Works with keyboard navigation
5. **Loading States**: Visual feedback during processing

## 🎨 UI Improvements Made

- Modern glassmorphism effects
- Smooth gradient backgrounds
- Animated success confirmations
- Interactive payment selection
- Professional offer cards
- Clean modal designs
- Responsive filter chips
- Hover effects throughout

## 🔜 Potential Enhancements

- Order tracking page
- User profile management
- Restaurant favorites
- Order rating and reviews
- Real-time order updates
- Actual payment gateway integration

---

**Made with ❤️ by Bereela Indhu**

Enjoy your GourmetDash experience! 🍽️
