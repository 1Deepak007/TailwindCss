// Tailwind css production setup
npm init -y     
npm install -D tailwindcss postcss autoprefixer vite
npx tailwindcss init -p

index.html  (input.css)
        -> input.css (add code -> 
                        @tailwind base;
                        @tailwind components;
                        @tailwind utilities;    )

tailwind.config.js  file replace->  content:[], with content:["*"],
package.json   ->  add ->     "start":"vite"
run code               ->      npm run start








---------------------------------------------------------------


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



