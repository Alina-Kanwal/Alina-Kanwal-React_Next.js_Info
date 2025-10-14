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
