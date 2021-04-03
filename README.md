## Initial setup

1. tailwindcss CDN to test only
`<link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">`
HTML `<h1 class="text-4xl font-bold text-center text-blue-500">Hello TailwindCSS</h1>`

2. compile `npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css`

3. init npm directory `npm init -y` generates a `package.json` file too

4. install packages `npm install -D tailwindcss postcss autoprefixer vite`
5. vite for the live server
6. inside `package.json` file's script area, write `"dev": "vite"`

7. generate the config files of tailwind `npx tailwindcss init -p`

8. run the project `npm run dev`

9. dev server link http://localhost:3000/