# ⚡ ShrinkStudio | Pro-Grade Image & PDF Compressor

![ShrinkStudio Hero](/public/hero-bg.png)

**ShrinkStudio** is a ultra-modern, high-performance web application designed to shrink your images and PDFs without compromising on quality. Built with a focus on **privacy** and **speed**, all processing happens locally in your browser—your files never touch a server.

[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Lucide](https://img.shields.io/badge/Lucide-Icons-pink?style=for-the-badge)](https://lucide.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## ✨ Key Features

- 🖼️ **Multi-Format Support**: Compress JPG, PNG, WEBP, and PDF files instantly.
- 🔒 **Privacy First**: 100% Client-side processing. Your data stays on your device.
- 🚀 **Turbo-Speed**: Leverages Web Workers for non-blocking, multi-threaded compression.
- 💎 **Premium UI**: Sleek glassmorphism design with dynamic gradients and micro-animations.
- 📦 **Bulk Processing**: Drag and drop dozens of files and compress them all with one click.
- 📊 **Real-time Stats**: View exact compression ratios and space saved before downloading.

---

## 🛠️ Tech Stack

- **Framework**: [React 18](https://reactjs.org/) with [Vite](https://vitejs.dev/)
- **Compression**: [browser-image-compression](https://www.npmjs.com/package/browser-image-compression) & [pdf-lib](https://pdf-lib.js.org/)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Styling**: Vanilla CSS (Custom Design System) + Tailwind CSS

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/IndronathBasu/Image-Compressor.git
   cd Image-Compressor
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

---

## 📖 How it Works

ShrinkStudio uses the browser's native Canvas API and specialized compression algorithms to reduce file sizes:
1. **Images**: Intelligently adjusts resolution and quantization parameters while maintaining visual fidelity.
2. **PDFs**: Optimizes document structure and metadata streams to strip away unnecessary overhead.
3. **Huffman Coding**: Leverages standard entropy coding during the final encoding stage (via browser-native engines) to ensure optimal lossless storage.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Built with 💜 by <a href="https://github.com/IndronathBasu">Indronath Basu</a>
</p>
