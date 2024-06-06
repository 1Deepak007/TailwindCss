npm init-y     
npm install -D tailwindcss postcss autoprefixer vite
npx tailwindcss init -p

include cdn in html file :
        <script src="https://cdn.tailwindcss.com"></script>

In package.json
        "scripts": {
            "start":"vite"
        },

In tailwind.config.js
        content: ["*"],       // mean use tailwind everywhere

npm run start
http://localhost:5173/Index.html



// Tailwind css production setup
