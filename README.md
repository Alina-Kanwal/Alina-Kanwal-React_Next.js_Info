# Alina-Kanwal-React_Next.js_Info
JSON.stringify() → Object ko string (JSON format) me convert karta hai.
JSON.stringify({name: "Ali"}) // → '{"name":"Ali"}'
JSON.parse() → JSON string ko object me convert karta hai.
JSON.parse('{"name":"Ali"}') // → {name: "Ali"}
🔹 localStorage
Stores data in browser permanently
localStorage.setItem("name", "Imran");
console.log(localStorage.getItem("name")); // Imran
🔹 useState (React)
useState(0) → React hook hai jo ek state variable banata hai.
count → state ka current value (yani abhi kitna number hai).
setCount → state ko update karne ka function.
const [count, setCount] = useState(0);
<button onClick={() => setCount(count + 1)}>{count}</button>
session_22 23_oct_2025
1.🔹 JSX (JavaScript XML)
- JSX allows us to write HTML-like syntax inside JavaScript.
- It makes UI code more readable and easier to maintain.
2.🔹 Components
- Components are the building blocks of a React app.
- They can be **functional** or **class-based**.
- Components help break the UI into reusable pieces.
3.🔹 Props
- “Props” stands for **properties**.
- They are used to pass data from one component (parent) to another (child).
- Props are **read-only** and make components dynamic and reusable.
🔹🪝 React Hooks
github command
git init -> initializing k lea
git add .
git remote add origin https://github.com/Alina-Kanwal/frontened_assigments.git
git branch
git push origin -M main
git push origin main

