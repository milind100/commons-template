npx create-react-app my-app --template redux

https://v3.tailwindcss.com/docs/guides/create-react-app

npm install -D tailwindcss@3
npx tailwindcss init

/** @type {import('tailwindcss').Config} \*/
module.exports = {
content: [
"./src/**/\*.{js,jsx,ts,tsx}",
],
theme: {
extend: {},
},
plugins: [],
}

@tailwind base;
@tailwind components;
@tailwind utilities;
