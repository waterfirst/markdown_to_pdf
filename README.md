
https://zp1v56uxy8rdx5ypatb0ockcb9tr6a-oci3--5173--7f809d15.local-credentialless.webcontainer-api.io/
https://elegant-kitsune-d37316.netlify.app/

# Markdown to PDF Converter

A sleek and efficient web application that converts Markdown content to PDF files with real-time preview functionality. Built with React, TypeScript, and Tailwind CSS.

![App Screenshot](https://images.unsplash.com/photo-1606857521015-7f9fcf423740?w=1200&h=600&fit=crop)

## Features

- 🔄 Real-time Markdown preview
- 📑 PDF export functionality
- 💅 Clean and modern UI
- 📱 Responsive design
- ⚡ Fast and efficient conversion

## Tech Stack

- **React** - UI library
- **TypeScript** - Type safety and better developer experience
- **Tailwind CSS** - Utility-first CSS framework
- **@tailwindcss/typography** - Beautiful typography for Markdown content
- **react-markdown** - Markdown parsing and rendering
- **html2pdf.js** - PDF generation
- **Lucide React** - Beautiful icons
- **Vite** - Build tool and development server

## Getting Started

1. Clone the repository:
   ```bash
   git clone [your-repository-url]
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

## How It Works

The app consists of three main components:

1. **Markdown Input**
   - A textarea where users can input their Markdown content
   - Real-time state management using React's useState hook

2. **Preview Section**
   - Live rendering of Markdown content using react-markdown
   - Styled with Tailwind's typography plugin for beautiful content presentation

3. **PDF Export**
   - Uses html2pdf.js to convert the rendered content to PDF
   - Maintains styling and formatting during conversion

## Code Structure

```typescript
// Main App Component Structure
function App() {
  const [markdown, setMarkdown] = useState('');
  const previewRef = useRef<HTMLDivElement>(null);

  const handleExportPDF = () => {
    // PDF export logic
  };

  return (
    // UI Components
  );
}
```

## Development Process

1. **Project Setup**
   - Created a new Vite project with React and TypeScript
   - Added Tailwind CSS and its typography plugin
   - Configured ESLint for code quality

2. **UI Implementation**
   - Implemented a responsive two-column layout
   - Added Markdown input and preview sections
   - Integrated Lucide React icons for better UI

3. **Markdown Processing**
   - Integrated react-markdown for parsing and rendering
   - Added real-time preview functionality
   - Styled the output using Tailwind Typography

4. **PDF Export**
   - Implemented PDF export using html2pdf.js
   - Configured export options for optimal output
   - Added export button with loading state

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
