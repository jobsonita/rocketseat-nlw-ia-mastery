# rocketseat-nlw-ia-mastery

Rocketseat NLW-IA - Mastery Track

Commands executed:

```bash
npm create vite@latest

# create-vite@4.4.1
# Ok to proceed? (y) 
# ✔ Project name: … upload-ai-web
# ✔ Select a framework: › React
# ✔ Select a variant: › TypeScript

cd upload-ai-web/
npm install

npm i -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
npm i -D @types/node
# configure tsconfig.json and vite.config.ts

npx shadcn-ui@latest init

# shadcn-ui@0.3.0
# Ok to proceed? (y) 
# ✔ Would you like to use TypeScript (recommended)? … no / yes
# ✔ Which style would you like to use? › New York
# ✔ Which color would you like to use as base color? › Zinc
# ✔ Where is your global CSS file? … src/index.css
# ✔ Would you like to use CSS variables for colors? … no / yes
# ✔ Where is your tailwind.config.js located? … tailwind.config.js
# ✔ Configure the import alias for components: … @/components
# ✔ Configure the import alias for utils: … @/lib/utils
# ✔ Are you using React Server Components? … no / yes
# ✔ Write configuration to components.json. Proceed? … yes
```

Creating a button:

```bash
npx shadcn-ui@latest add button
```
