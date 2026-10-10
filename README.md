CSS Flexbox Photo Gallery

#Features

Responsive layout — adapts to desktop, tablet, and mobile screens.
Flexbox design — arranges images horizontally and wraps them onto new rows when needed.
Spacious image layout — uses gap: 40px to create clear separation between images.
Modern styling — includes rounded corners, subtle shadows, and a clean background.
Hover animations — images gently enlarge when hovered over.
Accessibility — uses semantic HTML elements and alternative text for images.
Optimized loading — lazy-loads images to improve initial page loading.
🛠️ Technologies Used
HTML5
CSS3
Flexbox

Media queries

CSS transitions and transforms
📁 Project Structure
css-flexbox-photo-gallery/
├── index.html
├── styles.css
└── README.md
🚀 Getting Started
1. Clone the repository
git clone YOUR_REPOSITORY_URL
Replace YOUR_REPOSITORY_URL with your actual GitHub repository URL.

2. Open the project
Navigate to the project folder:

cd css-flexbox-photo-gallery
3. Launch the gallery
Open index.html in your web browser.

Alternatively, use the Live Server extension in Visual Studio Code for automatic browser refresh while editing.

🎨 Customization

You can easily customize the gallery by editing styles.css.

Adjust image spacing
.gallery {
  gap: 40px;
}
Increase the value for more space between images or decrease it for a tighter layout.

Change image dimensions
.gallery img {
  width: 300px;
  height: 250px;
  object-fit: cover;
}
Customize image hover effects
.gallery img:hover {
  transform: scale(1.05);
}
Change the gallery colors
Update the background, header, and accent colors in your CSS to create your own visual style.

📱 Responsive Design

The gallery uses Flexbox and CSS media queries to adjust its layout to different screen sizes. Images wrap onto additional rows when necessary, helping prevent horizontal overflow on smaller screens.

🖼️ Image Credits

The demonstration images are provided by freeCodeCamp:

freeCodeCamp CSS Photo Gallery Images

🎯 Project Goals

This project demonstrates practical front-end development skills, including:

Structuring a webpage with semantic HTML.
Building flexible layouts with CSS Flexbox.
Styling images with borders, shadows, and transitions.
Creating responsive designs using media queries.
Improving accessibility and loading performance.
🔮 Future Improvements

Add a lightbox to view images at full size.
Include image captions and descriptions.
Add category filters for organizing photos.
Introduce a dark mode.
Add keyboard-accessible image navigation.
👨‍💻 Author

Created as a front-end development practice project to explore HTML, CSS, and responsive Flexbox layouts.

📄 License

This project is available for learning and personal practice. Check the terms of the image sources before redistributing the images or using them commercially.
