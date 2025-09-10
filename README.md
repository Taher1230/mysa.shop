# MYSA Jewelry Store

A beautiful jewelry e-commerce website with dynamic product management.

## Features

- 🛍️ **Product Catalog**: Browse beautiful jewelry collection
- 🛒 **Shopping Cart**: Add items to cart with quantity controls
- 💳 **Bill Generation**: Generate bills for purchases
- 🔐 **Admin Dashboard**: Secure product management system
- 📱 **Responsive Design**: Works on all devices
- 🖼️ **Image Upload**: Upload and manage product images

## How to Use

### For Customers
1. Visit `index.html` to browse products
2. Use +/- buttons to adjust quantities
3. Click "Generate Bill" to create your order

### For Admin (Product Management)
1. Go to `dashboard.html` or click "Admin" in navigation
2. Login with admin key: `mysa2025admin`
3. Add products with:
   - Product name
   - Price (₹)
   - Description (optional)
   - Product image
4. View and manage all products
5. Delete products as needed

## File Structure

```
├── index.html          # Main website
├── dashboard.html      # Admin dashboard
├── cart.html          # Shopping cart
├── bill.html          # Bill generation
├── pay.html           # Payment page
├── contacts.html      # Contact information
├── privacy-policy.html # Privacy policy
├── terms-condition.html # Terms of service
├── style.css          # Main stylesheet
├── script.js          # Main JavaScript
├── images/            # Product images folder
└── README.md          # This file
```

## Deployment on GitHub Pages

1. **Upload your files** to a GitHub repository
2. **Go to Settings** → **Pages**
3. **Select source**: Deploy from a branch
4. **Choose branch**: main (or master)
5. **Save** and wait for deployment
6. **Access your site** at: `https://yourusername.github.io/repository-name`

## Customization

### Change Admin Key
Edit `dashboard.html` line 150:
```javascript
const ADMIN_KEY = "your-new-secure-key";
```

### Add More Product Categories
Edit the navigation in `index.html` to add more product pages.

### Modify Styling
Edit `style.css` to change colors, fonts, and layout.

## Browser Compatibility

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## Data Storage

Products are stored in browser's localStorage, so they persist between sessions. For production use, consider upgrading to a database.

## Support

For issues or questions, contact: mysa.by.nafisa@gmail.com

## License

© 2025 MYSA.IN. All rights reserved.

