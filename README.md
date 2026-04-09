# Food Delivery App 🍕🍔

A modern and interactive food delivery application with an intuitive user interface. Browse restaurants, select items, and manage your orders seamlessly.

## Features ✨

- **Restaurant Browsing**: Explore multiple restaurants and cuisines
- **Menu Management**: View detailed food items with descriptions and prices
- **Order Placement**: Easy-to-use ordering system
- **Shopping Cart**: Add/remove items and track total cost
- **Order Summary**: Clear breakdown of your order
- **Responsive Design**: Works perfectly on all devices
- **Real-time Updates**: Dynamic cart and order management

## Demo 🎯

The app provides a complete food ordering experience:
- Browse available restaurants
- View menu items with prices
- Add items to cart
- Review order summary
- Calculate total including taxes/delivery
- User-friendly checkout process

## Technologies Used 💻

- **HTML5** - Semantic structure
- **CSS3** - Modern styling, animations, and responsive layout
- **JavaScript** - Dynamic functionality and interactivity
- **Local Storage** - Persistent cart data

## File Structure 📁

```
Food-delivery-app/
├── index.html   # Main application file
├── style.css    # Complete styling and layout
├── script.js    # App functionality and logic
└── assets/      # Images and icons (if any)
```

## Getting Started 🚀

1. **Clone the repository**
   ```bash
   git clone https://github.com/vibhabohra/Food-delivery-app.git
   ```

2. **Navigate to project**
   ```bash
   cd Food-delivery-app
   ```

3. **Open in browser**
   - Double-click `index.html` or
   - Open with your preferred web browser

4. **Start ordering!**
   - Browse available restaurants
   - Click on items to add to cart
   - Proceed to checkout

## How to Use 📖

### Browsing
- View all available restaurants
- Check cuisine types and ratings
- See delivery times and costs

### Ordering
| Action | How |
|--------|-----|
| Add Item | Click "Add to Cart" button |
| View Cart | Click cart icon in header |
| Remove Item | Click remove button in cart |
| Update Quantity | Use +/- buttons |
| Proceed | Click "Checkout" |

### Cart Management
- View total price
- See itemized breakdown
- Apply discounts if available
- Proceed to payment

## Features Explained 🎨

### Restaurant List
- Restaurant names and logos
- Cuisine categories
- Delivery time and cost
- Rating and reviews count

### Menu Display
- Food item images
- Detailed descriptions
- Pricing information
- Customization options

### Shopping Cart
- Real-time price calculation
- Item quantity adjustment
- Remove items easily
- Order summary display

### User Experience
- Smooth transitions and animations
- Responsive mobile design
- Intuitive navigation
- Clear call-to-action buttons

## Customization Guide 🛠️

### Add More Restaurants
Edit the restaurants array in `script.js`:
```javascript
const restaurants = [
  {
    id: 1,
    name: "Restaurant Name",
    cuisine: "Cuisine Type",
    delivery_time: "30 mins",
    delivery_fee: "$2.99",
    rating: 4.5
  }
  // Add more...
];
```

### Update Menu Items
Add items to the menu array with:
- Item name
- Description
- Price
- Category
- Image

### Customize Colors
Modify the color scheme in `style.css`:
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --accent-color: #your-color;
}
```

## Browser Compatibility 🌐

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips 📊

- Optimized image loading
- Minimal CSS and JS
- Smooth animations
- Fast DOM manipulation
- Efficient local storage usage

## Data Persistence 💾

The app uses browser's local storage to:
- Save cart items
- Remember user preferences
- Maintain order history

## Security Considerations 🔒

For production deployment:
- Validate all inputs
- Implement user authentication
- Use HTTPS for all connections
- Secure payment processing
- Protect sensitive data

## Integration Points 🔗

Ready to integrate with:
- Backend API for real restaurant data
- Payment gateway (Stripe, PayPal)
- Maps API for delivery tracking
- SMS/Email notifications
- User authentication system

## Future Enhancements 🔄

- [ ] Backend API integration
- [ ] User authentication
- [ ] Order tracking in real-time
- [ ] Payment gateway integration
- [ ] Rating and reviews system
- [ ] Favorites/Wishlist
- [ ] Promotion codes
- [ ] Multiple delivery addresses
- [ ] Order history
- [ ] Push notifications

## API Integration Guide 📡

To connect with a backend server:

```javascript
// Example: Fetch restaurants from API
fetch('/api/restaurants')
  .then(response => response.json())
  .then(data => {
    // Process restaurant data
  });
```

## Testing 🧪

Manual testing checklist:
- [ ] Add items to cart
- [ ] Update quantities
- [ ] Remove items
- [ ] Calculate totals correctly
- [ ] Responsive on mobile
- [ ] Cart persists on refresh
- [ ] All animations smooth
- [ ] No console errors

## License 📄

This project is open source and available under the MIT License.

## Author 👤

**Vibha Bohra**
- GitHub: [@vibhabohra](https://github.com/vibhabohra)

## Contributing 🤝

Contributions are welcome! Areas for improvement:
- UI/UX enhancements
- Backend integration
- Payment processing
- Order management system
- Real-time notifications

**To contribute:**
1. Fork the repository
2. Create your feature branch
3. Make your improvements
4. Commit and push
5. Submit a pull request

## Support & Feedback 💬

Have suggestions or found issues? 
- Open an issue on GitHub
- Submit a pull request
- Contact via email

---

**Pro Tips:**
- Test on real mobile devices
- Optimize for slow internet
- Implement proper error handling
- Add loading states
- Test payment flows thoroughly

⭐ If you found this helpful, please star the repository!
