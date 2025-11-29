# 📚 My Books - Personal Library

A personal library webpage showcasing my favorite books, currently reading list, and books I want to read. Built with semantic HTML5 and CSS3, focusing on accessibility and clean design.

## 🎯 Project Overview

This project is a static webpage that serves as my digital book collection. It allows visitors to explore my reading journey, see my favorite books, and recommend new titles through a contact form.

## ✨ Features

- **Favorites Section**: Highlighted books that made the biggest impact
- **Currently Reading**: Track what I'm reading right now
- **Read Books**: Complete list of books I've finished
- **To-Read List**: Books on my reading wishlist
- **Book Recommendations**: Contact form for visitors to suggest new books
- **Genre Filter**: Sidebar with book genres for quick reference
- **Fully Accessible**: ARIA attributes for screen readers
- **Responsive Design**: Optimized for all devices
- **SEO Optimized**: Meta tags for better search engine visibility

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Custom styling (styles.css)
- **ARIA**: Web accessibility attributes
- **Favicon**: Custom icons for different devices

## 📁 Project Structure

```
LANDINGPAG/
├── assets/
│   ├── icons/
│   │   ├── apple-touch-icon.png
│   │   ├── favicon-32x32.png
│   │   ├── favicon-16x16.png
│   │   ├── favicon.ico
│   │   └── site.webmanifest
│   ├── Atomic Habits.jpg
│   ├── ELSEÑORANILLOS.png
│   ├── TheCatintheHat.jpeg
│   ├── Thelittleprince.jpeg
│   ├── TheNotebook.jpeg
│   └── YoungHealth.jpeg
├── index.html
├── styles.css
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS (for customization)

### Installation

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/juanda404/mybooks.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd my-books-library
   ```

3. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```

4. **View in browser**
   - Open `http://localhost:8000` in your browser

## 📖 Usage

### Adding New Books

1. Open `index.html` in your code editor
2. Find the appropriate section (Favorites, Read Books, etc.)
3. Copy an existing `<article>` element
4. Update the content:
   ```html
   <article role="listitem">
      <figure>
         <img src="assets/your-book-cover.jpg" alt="Book cover of Your Book Title">
         <figcaption>Cover</figcaption>
      </figure>
      <h3>Your Book Title</h3>
      <p>Read: <strong><time datetime="2025">2025</time></strong></p>
      <p>Your book description here.</p>
   </article>
   ```

### Customizing Styles

Edit `styles.css` to change:
- Colors and fonts
- Layout and spacing
- Responsive breakpoints
- Hover effects

### Adding New Genres

In the sidebar `<aside>` section, add a new list item:
```html
<li role="listitem">Your New Genre</li>
```

## ♿ Accessibility Features

This project implements several accessibility best practices:

- **Semantic HTML5**: `<header>`, `<main>`, `<aside>`, `<footer>`, `<nav>`, `<section>`, `<article>`
- **ARIA Roles**: `role="banner"`, `role="main"`, `role="complementary"`, `role="contentinfo"`
- **ARIA Labels**: Descriptive labels for navigation and interactive elements
- **Alt Text**: All images have descriptive alternative text
- **Keyboard Navigation**: Fully navigable with keyboard
- **Screen Reader Support**: Proper labeling with `aria-labelledby` and `aria-describedby`
- **Emoji Accessibility**: Decorative emojis hidden from screen readers with `aria-hidden="true"`

## 📱 Responsive Design

The layout adapts to different screen sizes:
- **Desktop**: Full sidebar with grid layout
- **Tablet**: Adjusted spacing and layout
- **Mobile**: Stacked layout for easy scrolling

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📝 Form Functionality

The book recommendation form includes:
- Name and email validation
- Required field indicators
- Textarea for detailed recommendations
- Accessible labels and hints

**Note**: The form currently submits to `#` (placeholder). To make it functional, you need to:
1. Set up a backend server (Node.js, PHP, Python, etc.)
2. Or use a form service like Formspree, Netlify Forms, or Google Forms
3. Update the `action` attribute in the `<form>` tag

## 🎨 Customization Ideas

- Add a dark mode toggle
- Implement a search/filter functionality
- Add reading progress bars
- Include book ratings (star system)
- Create a reading statistics dashboard
- Add social sharing buttons
- Implement a "Random Book" generator

## 📚 Books Included

### Favorites
- The Lord of the Rings
- Atomic Habits

### Currently Reading
- The Lord of the Rings

### Read Books
- The Little Prince
- Young People, Social Media and Health
- The Cat in the Hat
- The Notebook

### To Read
- Throne of Glass
- Como Ganar Amigos e Influir sobre las personas
- The Elements of Style
- Courage is Calling
- Meditations
- Harry Potter and the Chamber of Secrets
- Why Code?

## 🤝 Contributing

This is a personal project, but suggestions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Juan David SantaMaria G**

- Email: [juandavidsantamariag@gmail.com](mailto:juandavidsantamariag@gmail.com)
- Phone: +57 300 3617203
- Instagram: [@juanda404](https://instagram.com/juanda404)

## 🙏 Acknowledgments

- Book cover images are for educational purposes
- Icons generated using [Favicon.io](https://favicon.io/)
- Inspired by various book tracking applications

## 📅 Version History

- **v1.0.0** (2025) - Initial release
  - Basic library structure
  - Favorites and reading lists
  - Recommendation form
  - Full accessibility implementation

---

**Happy Reading! 📖✨**

If you find this project helpful, please consider giving it a ⭐ on GitHub!