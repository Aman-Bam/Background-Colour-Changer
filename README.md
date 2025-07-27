Background Color Changer 🎨

A simple and interactive React application that allows users to change the background color of the page with a single click. Built with modern web technologies for a smooth and responsive user experience.


## 📸 Screenshot
 <img width="1919" height="971" alt="Screenshot 2025-07-27 080501" src="https://github.com/user-attachments/assets/97dbd1f2-42c9-44bc-940c-75b550ede9f4" />

## ✨ Features

- **10+ Color Options**: Choose from Red, Green, Blue, Black, White, Orange, Purple, Brown, Light Gray, and Violet
- **Instant Color Change**: Click any button to instantly change the background color
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Transitions**: Elegant 200ms duration transition between color changes
- **Modern UI**: Clean and minimalist design with rounded buttons and shadows
- **Tailwind CSS Styling**: Utilizes Tailwind CSS for consistent and modern styling

## 🛠️ Built With

- **React 18** - Frontend framework
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript (ES6+)** - Programming language
- **HTML5** - Markup language
- **CSS3** - Styling

## 🏗️ Project Structure

```
background-colour-changer/
├── src/
│   ├── App.jsx          # Main component with color changing logic
│   └── main.jsx         # React entry point
├── public/              # Static assets
├── index.html           # HTML template
├── package.json         # Dependencies and scripts
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind CSS configuration
├── postcss.config.js    # PostCSS configuration
├── eslint.config.js     # ESLint configuration
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aman-Bam/Background-Colour-Changer.git
   ```

2. **Navigate to project directory**
   ```bash
   cd Background-Colour-Changer
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```
   or
   ```bash
   yarn dev
   ```

5. **Open your browser**
   
   Visit `http://localhost:5173` to see the application running.

## 📱 Usage

1. Open the application in your web browser
2. You'll see a page with an olive-colored background (default)
3. At the bottom of the screen, you'll find a row of colored buttons
4. Click on any button to instantly change the background color
5. Enjoy the smooth color transitions!

## 🎯 Key Components

### App Component
The main component that handles:
- State management using `useState` hook
- Background color changes
- Button click handlers
- Responsive layout

### Color Options
Available colors include:
- Red, Green, Blue
- Black, White
- Orange, Purple, Brown
- Light Gray, Violet

## 🔧 Available Scripts

In the project directory, you can run:

- `npm run dev` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm run preview` - Previews the production build
- `npm run lint` - Runs ESLint to check code quality

## 🎨 Customization

### Adding New Colors

To add new colors, modify the `App.jsx` file:

```jsx
<button
  onClick={() => setColor("yourNewColor")}
  className="outline-none px-4 py-1 rounded-full text-white shadow-lg"
  style={{backgroundColor: "yourNewColor"}}
>
  Your Color Name
</button>
```

### Styling Modifications

- Edit `tailwind.config.js` for Tailwind customizations
- Modify CSS classes in components for styling changes
- Adjust transition duration by changing the `duration-200` class

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 💡 Future Enhancements

- [ ] Add custom color picker
- [ ] Save favorite colors to local storage
- [ ] Add gradient background options
- [ ] Implement keyboard shortcuts
- [ ] Add dark/light mode toggle
- [ ] Include color accessibility features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Aman Bam**
- GitHub: [@Aman-Bam](https://github.com/Aman-Bam)

## 🙏 Acknowledgments

- React team for the amazing framework
- Tailwind CSS for the utility-first approach
- Vite team for the lightning-fast build tool
- The open-source community for inspiration
- 

⭐ Star this repository if you found it helpful!

**Happy Coding!** 🚀
