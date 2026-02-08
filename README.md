# Robotics & Science Labs - Registration Page

Production-ready early access registration page for robotics students.

## Features

- **Robotics Lab Design**: CAD-style grid with robotic arm, gear mechanism, circuit traces, microchip layouts
- **Responsive**: Mobile-optimized for all devices  
- **Form Validation**: Real-time validation (name, email, phone, grade)
- **Netlify Integration**: Automatic form submission and redirect
- **Security**: reCAPTCHA, honeypot field, HTTPS ready

## Files

- `index.html` - Registration form with validation
- `thank-you.html` - Success confirmation page
- `shared.css` - Styles and robotics lab background design

## Deployment

**Drag & Drop (Easiest)**
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the registration folder
3. Done!

**Git Deploy**
1. Push to GitHub/GitLab/Bitbucket  
2. Connect repo to Netlify
3. Set publish directory to `.`

## Customization

**Change heading** in `index.html`:
```html
<h1>Your Lab Name</h1>
```

**Change colors** in `shared.css`:
```css
:root {
    --primary-color: #1e3a8a;
    --primary-light: #3b82f6;
    --secondary-color: #059669;
    --accent-color: #f59e0b;
}
```

**Modify background grid opacity**:
```css
rgba(10, 132, 255, 0.08) /* Change to 0.04-0.12 */
```

## Form Fields

- Full Name (letters/spaces, 2-50 chars)
- Email (valid format)
- Grade/Class (dropdown)
- Phone (10-digit number)

## Browser Support

Chrome, Firefox, Safari, Edge (latest 2 versions) and modern mobile browsers.

## License

Free to use and modify.