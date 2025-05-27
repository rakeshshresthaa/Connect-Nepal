# Connect Nepal: International Student Engagement Platform

A modern, responsive website designed to connect international students through cultural and student organizations in Nepal. This platform serves as a digital hub for promoting cultural awareness, social activities, student resources, and international events in Nepal.

## 🌟 Features

- Modern, responsive design
- Cultural club directory
- Interactive event calendar with RSVP functionality
- Multimedia gallery
- Student resources section
- Contact and join forms with validation
- Dark/Light theme toggle
- Mobile-friendly navigation
- Smooth animations and transitions

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- JavaScript (ES6+)
- Google Fonts (Poppins & Lora)
- Font Awesome Icons
- Local Storage for theme preference

## 📁 Project Structure

```
/
├── index.html              # Home page
├── about.html              # About page
├── clubs/                  # Club directory
│   ├── index.html         # Clubs listing
│   ├── club-nepal.html    # Nepal club page
│   ├── club-india.html    # India club page
│   └── club-africa.html   # Africa club page
├── events.html            # Events calendar
├── gallery.html           # Photo/video gallery
├── resources.html         # Student resources
├── contact.html           # Contact form
├── join.html              # Join form
├── css/
│   └── style.css         # Main stylesheet
├── js/
│   └── script.js         # Main JavaScript file
├── images/               # Image assets
└── videos/              # Video assets
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/connect-nepal.git
   ```

2. Open the project in your preferred code editor

3. Launch `index.html` in your web browser

## 🎨 Customization

### Colors
The color scheme can be modified in `css/style.css` by updating the CSS variables in the `:root` selector:

```css
:root {
    --primary-color: #d62828;
    --secondary-color: #003049;
    --text-color: #333;
    --light-bg: #fff;
    --dark-bg: #1a1a1a;
}
```

### Fonts
The project uses Google Fonts. To change the fonts, update the Google Fonts link in the HTML files and modify the font-family properties in the CSS.

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

## 🌓 Dark Mode

The website includes a dark mode toggle that:
- Persists user preference using localStorage
- Automatically applies dark theme styles
- Provides smooth transitions between themes

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Your Name - Rakesh Shreestha,Pranit Duwal,Nurbin Suwal

## 🙏 Acknowledgments

- Google Fonts for the beautiful typography
- Font Awesome for the icons
- All contributors who have helped shape this project 
