# Angor Client

A modern Blazor WebAssembly application styled with Tailwind CSS v4 and a consistent Angor color scheme.

## Features

- 🚀 Blazor WebAssembly (.NET 9)
- 🎨 Tailwind CSS v4 for styling
- 🎭 Custom Angor color palette for consistent branding
- 📱 Responsive design
- 🔄 PWA support
- 🌗 Dark mode support with smooth transitions
- 🧩 Component-based architecture

## Prerequisites

- .NET 9.0 SDK or later
- Node.js and npm

## Getting Started

1. Clone the repository
2. Run the Blazor app:
   ```
   dotnet run
   ```
   
   > **Note:** The Tailwind CSS will be automatically generated during build!

## Manual CSS Generation

If you need to manually generate the CSS:

### On Windows:
```
.\build-tailwind.bat
```

### On Linux/Mac:
```
chmod +x build-tailwind.sh
./build-tailwind.sh
```

## Development Workflow

- For development with watch mode:
  ```
  npm run watch
  ```
- For production builds with minification:
  ```
  npm run build
  ```

## Project Structure

- `Pages/` - Blazor pages
- `Layout/` - Layout components
- `wwwroot/` - Static files
- `style.css` - Main Tailwind CSS entry point
- `tailwind.config.js` - Tailwind configuration with Angor color schema

## Customization

Modify the `tailwind.config.js` file to customize the design system, including colors, spacing, fonts, and more. The Angor color palette provides a unified visual identity across the entire application.