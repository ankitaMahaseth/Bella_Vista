# 🍽️ Restaurant Website

A modern, responsive restaurant website built with **HTML and CSS**. The design focuses on a clean layout, attractive typography, responsive navigation, menu presentation, contact information, and smooth CSS animations.

## ✨ Features

- 🎨 Modern and clean restaurant design
- 📱 Fully responsive layout
- 🧭 Fixed navigation header
- 🍔 Restaurant menu section with categories and prices
- 🏠 Hero/banner section with background image
- 📖 About section with restaurant information
- 📩 Contact section with contact details and form
- 📱 Mobile hamburger navigation menu
- 🎬 CSS animations and transitions
- 🖱️ Hover effects on buttons, menu items, and links
- 🦶 Responsive footer with social links
- 🎨 CSS custom properties for reusable colors and styling

## 🛠️ Technologies Used

- **HTML5** — Page structure and semantic content
- **CSS3** — Styling, layout, responsiveness, animations, and transitions
- **CSS Grid** — Menu, About, and Contact layouts
- **CSS Flexbox** — Navigation, buttons, and menu items
- **CSS Variables** — Reusable theme colors and design properties
- **Unsplash** — Hero section background image

## 📂 Project Structure

```text
restaurant-website/
│
├── index.html
├── style.css
└── README.md
```

## 🎨 Design System

The project uses CSS custom properties to maintain a consistent visual style.

| Variable            | Value                        | Purpose                  |
| ------------------- | ---------------------------- | ------------------------ |
| `--primary-color`   | `#e74c3c`                    | Primary accent color     |
| `--secondary-color` | `#2c3e50`                    | Header and heading color |
| `--accent-color`    | `#3498db`                    | Secondary accent         |
| `--light-bg`        | `#f8f9fa`                    | Light section background |
| `--dark-text`       | `#333`                       | Main text                |
| `--light-text`      | `#666`                       | Secondary text           |
| `--border-radius`   | `8px`                        | Rounded corners          |
| `--shadow`          | `0 4px 15px rgba(0,0,0,0.1)` | Card shadow              |
| `--transition`      | `all 0.3s ease`              | Common transition        |

## 📱 Responsive Design

The website includes responsive breakpoints for different screen sizes.

### Tablet — `max-width: 768px`

- Hero heading size is reduced
- Hero buttons become vertically stacked
- About and Contact sections change to a single-column layout
- Navigation spacing is reduced

### Mobile — `max-width: 480px`

- Desktop navigation links are hidden
- Hamburger menu becomes visible
- Mobile navigation menu can be toggled using CSS
- Logo size is reduced
- Hero heading becomes smaller
- Content receives reduced horizontal padding

## 🎬 Animations

The project includes CSS animations to improve the visual experience.

### `fadeInUp`

Used for:

- Hero content
- Menu items
- About image

The animation gradually fades elements in while moving them upward.

### `slideInLeft`

A reusable animation that moves elements from the left while fading them in.

### Menu Item Delays

Menu items use different animation delays to create a staggered entrance effect:

```css
.menu_item:nth-child(1) {
  animation-delay: 0.1s;
}
.menu_item:nth-child(2) {
  animation-delay: 0.2s;
}
.menu_item:nth-child(3) {
  animation-delay: 0.3s;
}
.menu_item:nth-child(4) {
  animation-delay: 0.4s;
}
.menu_item:nth-child(5) {
  animation-delay: 0.5s;
}
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/restaurant-website.git
```

### 2. Navigate to the project

```bash
cd restaurant-website
```

### 3. Open the website

Open `index.html` directly in your browser.

Alternatively, use a local development server such as **VS Code Live Server**.

## 🖼️ Hero Image

The hero section currently uses an image hosted by Unsplash:

```css
background-image:
  linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
  url("https://images.unsplash.com/photo-1517248135467-4c7edcad34c4...");
```

For production, consider downloading and hosting the image locally or replacing it with your own restaurant photography.

## 📋 Main Sections

### Hero

The hero section introduces the restaurant with:

- Restaurant heading
- Short description
- Primary call-to-action button
- Secondary button
- Full-screen background image

### Menu

The menu displays restaurant items using cards containing:

- Item name
- Description
- Price

Menu cards include hover effects and entrance animations.

### About

The About section provides information about the restaurant alongside an image.

### Contact

The Contact section contains:

- Restaurant contact information
- Address
- Phone/email information
- Contact form

### Footer

The footer provides:

- Restaurant information
- Navigation links
- Social media links
- Copyright information

## 🔧 Customization

### Change the primary color

Update:

```css
:root {
  --primary-color: #e74c3c;
}
```

### Change the secondary color

```css
:root {
  --secondary-color: #2c3e50;
}
```

### Change the hero image

Replace the image URL inside `.hero`:

```css
.hero {
  background-image:
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("YOUR-IMAGE-URL");
}
```

### Change the restaurant content

Update the text in `index.html` for:

- Restaurant name
- Tagline
- Menu items
- Prices
- About information
- Contact information
- Social links

## 🌐 Browser Support

The website is designed to work with modern browsers including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## 📌 Future Improvements

Possible improvements for future versions:

- [ ] Add JavaScript-powered mobile navigation
- [ ] Add online table reservation functionality
- [ ] Add food/menu images
- [ ] Add an image gallery
- [ ] Add dark/light mode
- [ ] Add form validation
- [ ] Connect the contact form to a backend
- [ ] Add scroll-based animations
- [ ] Add SEO metadata
- [ ] Optimize images for faster loading
- [ ] Add accessibility improvements

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/your-feature
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add your feature"
```

5. Push the branch

```bash
git push origin feature/your-feature
```

6. Open a Pull Request

---

### ⭐ If you like this project

Consider giving the repository a ⭐ on GitHub!
