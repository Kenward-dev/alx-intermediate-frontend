# Tailwind CSS Grid & Flexbox 

Simple HTML examples demonstrating CSS Grid and Flexbox layouts using Tailwind CSS.

## Files

- `1-index.html` - Basic 3-column grid layout
- `flexbox-nav.html` - Responsive navigation bar with flexbox

## Grid Example Features

- 3-column grid layout using `grid grid-cols-3`
- Responsive design (single column on mobile)
- Different background colors for each column

## Flexbox Example Features

- Horizontal navigation bar using `flex`
- Centered navigation items
- Responsive mobile layout (vertical stack)
- Hover effects on navigation links

## Setup

1. **Install Tailwind CSS:**
   ```bash
   npm install -D tailwindcss
   npx tailwindcss init
   ```

2. **Configure tailwind.config.js:**
   ```js
   module.exports = {
     content: ["./*.html"],
     theme: { extend: {} },
     plugins: [],
   }
   ```

3. **Create input.css:**
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

4. **Build CSS:**
   ```bash
   npx tailwindcss -i ./input.css -o ./output.css --watch
   ```

5. **Open HTML files in browser**

## Key Tailwind Classes Used

### Grid Layout
- `grid` - Creates grid container
- `grid-cols-3` - 3 equal columns
- `gap-4` - Space between grid items

### Flexbox Layout  
- `flex` - Creates flex container
- `justify-center` - Center items horizontally
- `space-x-5` - Horizontal spacing between items

### Responsive Design
- `md:flex-row` - Row layout on medium screens and up
- `md:space-x-5` - Horizontal spacing on medium screens and up