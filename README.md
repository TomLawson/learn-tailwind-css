# learn-tailwind-css

Keeping track of learning tailwind css following the [Tailwind Labs tutorials on youtube](https://www.youtube.com/playlist?list=PL5f_mz_zU5eXWYDXHUDOLBE0scnuJofO0)

## Setup
Set up the environment to build tailwind using Vite
```bash
# Initialise a node module
npm init -y

# Install required modules
npm install -D tailwindcss postcss autoprefixer vite

# Init tailwind and postcss config 
npx tailwindcss init -p
```

Create a css file with the following postcss directives:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Remember to include the Tailwind CSS stylesheet:

```html
<link href="/css/tailwind.css" rel="stylesheet">
```