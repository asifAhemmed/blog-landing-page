# Living the Social Life - Minimalist Blog

A clean, responsive blog layout exploring minimalism and simple living. Built with HTML5 and CSS3, featuring a modern design with sidebar widgets and mobile-first responsive layout.


## 🌟 Features

- **Fully Responsive Design** - Seamless experience across mobile, tablet, and desktop devices
- **Clean Typography** - Beautiful font pairing with Ubuntu and Lora typefaces
- **Featured Article Section** - Highlight your most important content
- **Recent Posts Feed** - Display latest blog entries with images and metadata
- **Sidebar Widgets** - About Me section and Recent Posts sidebar
- **Mobile-First Approach** - Optimized for mobile devices first, then scaled up
- **Minimalist Aesthetic** - Clean, distraction-free reading experience

## 📱 Responsive Breakpoints

- **Mobile**: < 675px (single column layout)
- **Desktop**: ≥ 675px (two-column layout with sidebar)

## 🚀 Demo

[Live Demo](https://simplelifeblog.netlify.app/) 

## 🛠️ Technologies Used

- HTML5
- CSS3
- Google Fonts (Ubuntu & Lora)
- Flexbox Layout

## 📂 Project Structure

```
minimalist-blog/
│
├── index.html              # Main HTML file
├── style.css              # CSS stylesheet
├── images/
│   ├── home.jpg           # Featured article image
│   ├── chair.jfif         # Article images
│   └── person.jfif        # About Me profile image
└── README.md              # Project documentation
```

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/asifAhemmed/blog-landing-page.git
   cd minimalist-blog
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

   Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. **Start customizing!**
   - Replace images in the `images/` folder
   - Update content in `index.html`
   - Modify styles in `style.css`

## 🎨 Customization

### Colors

Update the color scheme in `style.css`:

```css
/* Primary colors used */
--primary-blue: #1792d2;      /* Links and accents */
--dark-blue: #143774;         /* Headings and footer */
--light-gray: #f8f8f8;        /* Backgrounds */
--text-gray: #707070;         /* Body text and borders */
```

### Fonts

The project uses Google Fonts. To change fonts, update the import in `style.css`:

```css
@import url('your-google-font-url');

body {
  font-family: "Your Font", sans-serif;
}

h1, h2, h3 {
  font-family: "Your Heading Font", serif;
}
```

### Layout Width

Adjust the maximum container width:

```css
.container {
  max-width: 900px; /* Change this value */
}
```

## 📋 Page Sections

1. **Header**
   - Site title and subtitle
   - Navigation menu (Home, About Me, Recent Posts)

2. **Featured Article**
   - Large hero image
   - Article title and body
   - Publication date and comment count
   - "Continue Reading" link

3. **Recent Posts**
   - Grid of recent blog entries
   - Thumbnail images
   - Article previews with metadata

4. **Sidebar**
   - About Me widget with profile photo
   - Recent Posts widget with thumbnails

5. **Footer**
   - Site name and copyright information

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📱 Mobile Features

- **Single Column Layout** - Content stacks vertically on mobile
- **Centered Navigation** - Menu items stack for easy touch access
- **Responsive Images** - Images scale to fit screen width
- **Readable Font Sizes** - Optimized typography for small screens
- **Touch-Friendly Spacing** - Adequate padding and margins

## 💡 Usage Tips

### Adding a New Blog Post

1. Copy an existing `<article>` block in `index.html`
2. Update the image, title, date, and content
3. Save and refresh your browser

### Changing the Featured Post

Simply replace the content in the `.article-featured` section:

```html
<article class="article-featured">
  <h2 class="article-title">Your New Title</h2>
  <img src="images/your-image.jpg" alt="description" class="article-image" />
  <p class="article-info">Date | Comments</p>
  <p class="article-body">Your content here...</p>
  <a href="" class="article-read-more">CONTINUE READING</a>
</article>
```

### Updating the Sidebar

Modify the widgets in the `<aside class="sidebar">` section to add your own content, images, and links.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request


## 👤 Author

**Your Name**
- GitHub: [@asifAhemmed](https://github.com/asifAhemmed)
- Email: asifahemmed0@gmail.com

## 🎯 Use Cases

Perfect for:
- Personal blogs
- Minimalist lifestyle websites
- Portfolio blogs
- Writing showcases
- Simple content management
- Learning responsive web design

## 🙏 Acknowledgments

- Typography inspired by modern minimalist blogs
- Layout based on traditional blog design patterns
- Google Fonts for beautiful typography

## 📞 Support

For support, email asifahemmed0@gmail.com or create an issue in the GitHub repository.

---

⭐ **If you found this project helpful, please give it a star!** ⭐
