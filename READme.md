
Collage Maker 🎨
A powerful, cross-platform collage maker application that allows you to create stunning collages with your PNG images. Drag, drop, resize, and rotate images to design beautiful compositions.

https://img.shields.io/badge/Version-1.0.0-blue.svg
https://img.shields.io/badge/License-MIT-green.svg
https://img.shields.io/badge/Platform-Web%2520%257C%2520Desktop%2520%257C%2520Mobile-lightgrey.svg

✨ Features
🖼️ Core Functionality
Drag & Drop Interface - Intuitive image placement

Image Manipulation - Resize, rotate, and position images freely

Real-time Editing - See changes instantly as you work

Multiple Export Options - Save as PNG, JPEG, or project files

Cross-Platform - Works on web, desktop, and mobile devices

🎨 Editing Tools
Rotation Control - Precise image rotation with slider

Opacity Adjustment - Fine-tune image transparency

Canvas Backgrounds - Choose from various background styles

Text Overlays - Add text elements to your collages

Layer Management - Organize images with drag-and-drop

💾 Storage Options
Local Storage - Save projects directly in your browser

Cloud Sync - Optional cloud backup (requires account)

File Export - Export collages as high-quality images

Project Files - Save and reload your work in progress

🚀 Quick Start
Web Version
Visit your-app-url.com

Upload your PNG images via drag & drop or file browser

Drag images from the library to the canvas

Arrange, resize, and rotate to create your collage

Export your creation as PNG or save the project

DESKTOP VERSION

# Download the latest release
# Or build from source:
git clone https://github.com/your-username/collage-maker.git
cd collage-maker
npm install
npm run electron:dev


Mobile Version
Download from:

App Store

Google Play

📥 Installation
Prerequisites
Node.js 16+ (for development)

Modern web browser (Chrome, Firefox, Safari, Edge)

Web Version
No installation required! Simply visit the website and start creating.


LOCAL DEVELOPMENT 

# Clone the repository
git clone https://github.com/your-username/collage-maker.git

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

DESKTOP BUID

# Build Electron app
npm run electron:build

# Platform-specific builds
npm run build:win
npm run build:mac
npm run build:linux


🎯 Usage Guide
Creating Your First Collage
Add Images

Click "Upload Images" or drag PNG files directly

Select from sample images to get started quickly

Arrange Your Collage

Drag images from the library to the canvas

Click and drag to reposition images

Use corner handles to resize

Rotate with the rotation slider

Customize Appearance

Adjust opacity for transparent effects

Change canvas background color or pattern

Add text overlays with custom styling

Save & Export

Save project locally to continue later

Export as high-quality PNG image

Share directly to social media

Advanced Features
Keyboard Shortcuts

Ctrl/Cmd + Z - Undo

Ctrl/Cmd + Y - Redo

Delete - Remove selected element

Arrow keys - Nudge selected element

Touch Gestures (Mobile)

Pinch to zoom canvas

Two-finger rotate for precise control

Swipe to navigate between tools

🏗️ Architecture

Frontend:
  - React 18 + TypeScript
  - Canvas: Fabric.js / Konva.js
  - UI: Chakra UI / Material-UI
  - State: Zustand

Platforms:
  - Web: Vite + PWA
  - Desktop: Electron
  - Mobile: React Native / Capacitor

Storage:
  - Local: IndexedDB & localStorage
  - Cloud: Firebase / Supabase (optional)


PROJECT STRUCTURE

src/
├── components/          # Reusable UI components
│   ├── Canvas/         # Collage canvas component
│   ├── Toolbar/        # Editing tools
│   └── ImageLibrary/   # Image management
├── hooks/              # Custom React hooks
│   ├── useImages.ts    # Image handling logic
│   └── useCanvas.ts    # Canvas operations
├── stores/             # State management
│   └── collageStore.ts # Main application state
├── utils/              # Utility functions
│   ├── imageUtils.ts   # Image processing
│   └── exportUtils.ts  # Export functionality
└── types/              # TypeScript definitions

ENVIRONMENT VIRIABLE 

# Optional: For cloud features
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_KEY=your_supabase_key
VITE_CLOUD_STORAGE_URL=your_storage_url

# Feature flags
VITE_ENABLE_CLOUD_SYNC=false
VITE_ENABLE_USER_ACCOUNTS=false

Customization
Modify src/config/appConfig.ts to customize:

Default canvas sizes

Supported file types

Export quality settings

UI theme and colors

📱 Platform-Specific Features
Web
PWA support for app-like experience

Service worker for offline functionality

Share integration with Web Share API

Desktop
Native file system access

System tray integration

Keyboard shortcut support

High-performance image processing

Mobile
Touch-optimized interface

Camera integration for direct photos

Native sharing capabilities

Gesture-based controls

🤝 Contributing
We love contributions! Here's how to help:

Fork the repository

Create a feature branch: git checkout -b feature/amazing-feature

Commit your changes: git commit -m 'Add amazing feature'

Push to the branch: git push origin feature/amazing-feature

Open a Pull Request

Development Setup

# Install all dependencies
npm run setup

# Run tests
npm test

# Build all platforms
npm run build:all


Code Style
We use:

ESLint for code linting

Prettier for code formatting

TypeScript for type safety

Conventional commits for commit messages

🐛 Troubleshooting
Common Issues
Images not loading?

Check that files are PNG format

Ensure files are under 10MB limit

Verify browser supports File API

Performance issues?

Reduce number of high-resolution images

Close other browser tabs

Use the "Optimize Images" feature

Export problems?

Check available storage space

Ensure canvas isn't too large (max 4000x4000px)

Try different export format

Getting Help
📖 Check our detailed documentation

🐛 Open an issue for bugs

💬 Join our Discord for community support

📧 Email support: support@collagemaker.app

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Icons by Feather Icons

Canvas rendering by Fabric.js

UI components from Chakra UI

Built with Vite

📞 Contact
Project Homepage: https://collagemaker.app

Twitter: @collagemaker

Email: hello@collagemaker.app

<div align="center">
Happy Collage Making! 🎉

If you like this project, please give it a ⭐ on GitHub!

</div>