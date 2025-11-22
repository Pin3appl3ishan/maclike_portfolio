# Mac Portfolio 🖥️

A stunning macOS-themed portfolio website built with React and TypeScript. This interactive portfolio mimics the macOS interface, featuring a menu bar, dock, and window-based navigation system to showcase projects, articles, and skills.

## ✨ Features

- **macOS Interface**: Authentic macOS-style UI with menu bar, dock, and window system
- **Interactive Animations**: Smooth GSAP animations for text hover effects and dock icon interactions
- **Variable Font Animations**: Dynamic font weight changes on hover for an engaging experience
- **Window-Based Navigation**: Click dock icons to open different application windows
- **Responsive Design**: Optimized for desktop and tablet screens
- **Modern Tech Stack**: Built with React 19, TypeScript, and Tailwind CSS v4

## 🛠️ Tech Stack

- **Frontend Framework**: React 19 with TypeScript
- **Build Tool**: Vite 7
- **Styling**: Tailwind CSS v4
- **Animations**: GSAP 3.13 with @gsap/react
- **UI Icons**: Lucide React
- **Date Formatting**: Day.js
- **Tooltips**: React Tooltip

## 📦 Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd mac_portfolio
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Build for production:

```bash
npm run build
```

5. Preview production build:

```bash
npm run preview
```

## 🚀 Usage

- **Welcome Section**: Hover over the title and subtitle to see interactive font weight animations
- **Dock**: Hover over dock icons to see them scale and lift
- **Menu Bar**: View navigation links, system icons, and live time display
- **Applications**: Click dock icons to open different windows (implementation in progress)

## 📁 Project Structure

```
mac_portfolio/
├── public/
│   ├── files/
│   │   └── resume.pdf
│   ├── icons/          # Application and UI icons
│   ├── images/         # Project images, gallery, and assets
│   └── macbook.png
├── src/
│   ├── components/
│   │   ├── Dock.tsx    # Bottom dock with application icons
│   │   ├── Navbar.tsx  # Top menu bar
│   │   └── Welcome.tsx # Hero section with animated text
│   ├── constants/
│   │   └── index.ts    # Data configuration (apps, projects, blog posts, etc.)
│   ├── App.tsx         # Main application component
│   ├── main.tsx        # Application entry point
│   └── index.css       # Global styles and Tailwind configuration
├── package.json
└── vite.config.ts
```

## 🎯 Components

### Dock

Interactive bottom dock with macOS-style application icons. Features hover animations that scale and lift icons based on mouse proximity.

### Navbar

Top menu bar displaying:

- Logo and portfolio name
- Navigation links (Projects, Contact, Resume)
- System icons (WiFi, Search, User, Mode)
- Live time display

### Welcome

Hero section with:

- Animated subtitle: "Hey, I'm Ishan! Welcome to my"
- Large animated title: "portfolio"
- Variable font weight animations on hover
- Mobile-responsive message for small screens

## 📝 Configuration

All application data and settings are stored in `src/constants/index.ts`:

- `dockApps`: Dock application icons and settings
- `navLinks`: Menu bar navigation items
- `blogPosts`: Article/blog post data
- `techStack`: Skills and technology categories
- `socials`: Social media links
- `gallery`: Image gallery items
- `locations`: Finder folder structures for projects

## 🎨 Customization

1. **Personal Information**: Update the name in `Welcome.tsx` and `Navbar.tsx`
2. **Dock Apps**: Modify `dockApps` array in `src/constants/index.ts`
3. **Projects**: Edit the `WORK_LOCATION` object in `src/constants/index.ts`
4. **Social Links**: Update the `socials` array with your profiles
5. **Styling**: Customize colors and styles in `src/index.css`

## 📄 License

This project is open source and available for personal use.

## 👤 Author

**Ishan Shrestha** 

---

_Note: This portfolio is designed for desktop/tablet screens only. Mobile users will see a message indicating this._
