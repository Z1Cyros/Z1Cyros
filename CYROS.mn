- 👋 Hi, I’m @Z1Cyros
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Z1Cyros/Z1Cyros is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import React from "react"; import { BrowserRouter as Router, Route, Routes, Link } from "react-router-dom"; import Home from "./pages/Home"; import About from "./pages/About"; import Products from "./pages/Products"; import ProductDetail from "./pages/ProductDetail"; import Cart from "./pages/Cart"; import Checkout from "./pages/Checkout"; import Contact from "./pages/Contact"; import FAQ from "./pages/FAQ"; import Terms from "./pages/Terms"; import Profile from "./pages/Profile"; import Navbar from "./components/Navbar"; import Footer from "./components/Footer";

function App() { return ( <Router> <div className="flex flex-col min-h-screen"> <Navbar /> <main className="flex-1 container mx-auto px-4 py-6"> <Routes> <Route path="/" element={<Home />} /> <Route path="/about" element={<About />} /> <Route path="/products" element={<Products />} /> <Route path="/product/:id" element={<ProductDetail />} /> <Route path="/cart" element={<Cart />} /> <Route path="/checkout" element={<Checkout />} /> <Route path="/contact" element={<Contact />} /> <Route path="/faq" element={<FAQ />} /> <Route path="/terms" element={<Terms />} /> <Route path="/profile" element={<Profile />} /> </Routes> </main> <Footer /> </div> </Router> ); }

export default App;

// ---------------- Pages ----------------

export function Home() { return ( <div className="text-center"> <h1 className="text-3xl font-bold mb-4">Тавтай морилно уу Cyros дэлгүүрт!</h1> <p className="text-lg text-gray-600">Шинэ бүтээгдэхүүн, хямдрал, үйлчилгээг эндээс</p> <Link to="/products" className="mt-4 inline-block bg-blue-600 text-white px-6 py-2 rounded-xl shadow">Дэлгүүрээр зочлох</Link> </div> ); }

export function About() { return <div className="prose mx-auto"><h2>Бидний тухай</h2><p>Cyros бол Монголын онлайн худалдааны платформ бөгөөд хэрэглэгчдэд чанартай бүтээгдэхүүн, найдвартай үйлчилгээг санал болгодог.</p></div>; }

export function Products() { return ( <div> <h2 className="text-2xl font-semibold mb-4">Бүтээгдэхүүнүүд</h2> <div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4"> {[1, 2, 3].map((id) => ( <Link to={/product/${id}} key={id} className="border rounded-xl p-4 hover:shadow"> <img src={https://via.placeholder.com/150?text=Product+${id}} alt="Product" className="mb-2 w-full" /> <h3 className="text-lg font-medium">Бүтээгдэхүүн {id}</h3> <p className="text-gray-600">₮{id * 10000}</p> </Link> ))} </div> </div> ); }

export function ProductDetail() { return ( <div> <h2 className="text-2xl font-semibold mb-2">Бүтээгдэхүүний дэлгэрэнгүй</h2> <img src="https://via.placeholder.com/300" alt="Product" className="mb-4" /> <p className="text-lg">Бүтээгдэхүүний тайлбар энд орно.</p> <button className="mt-4 bg-green-600 text-white px-6 py-2 rounded-xl">Сагсанд нэмэх</button> </div> ); }

export function Cart() { return <div><h2 className="text-2xl font-semibold mb-4">Таны сагс</h2><p>Сагсанд байгаа бүтээгдэхүүнүүдийг энд харуулна.</p></div>; }

export function Checkout() { return <div><h2 className="text-2xl font-semibold mb-4">Төлбөр хийх</h2><p>Төлбөрийн мэдээллээ бөглөнө үү.</p></div>; }

export function Contact() { return <div><h2 className="text-2xl font-semibold mb-4">Холбоо барих</h2><p>info@cyros.mn</p></div>; }

export function FAQ() { return <div><h2 className="text-2xl font-semibold mb-4">Түгээмэл асуултууд</h2><p>Асуултууд болон хариултуудыг энд харуулна.</p></div>; }

export function Terms() { return <div><h2 className="text-2xl font-semibold mb-4">Нөхцөл, болзол</h2><p>Үйлчилгээний нөхцөл болон хэрэглэгчийн үүрэг, эрх.</p></div>; }

export function Profile() { return <div><h2 className="text-2xl font-semibold mb-4">Хэрэглэгчийн мэдээлэл</h2><p>Таны бүртгэлтэй холбоотой мэдээлэл.</p></div>; }

// ---------------- Components ----------------

export function Navbar() { return ( <nav className="bg-blue-600 text-white p-4 shadow"> <div className="container mx-auto flex justify-between"> <Link to="/" className="text-xl font-bold">Cyros</Link> <div className="space-x-4"> <Link to="/products">Бүтээгдэхүүн</Link> <Link to="/cart">Сагс</Link> <Link to="/profile">Профайл</Link> </div> </div> </nav> ); }

export function Footer() { return ( <footer className="bg-gray-100 text-center py-4 mt-8"> © 2025 Cyros. Бүх эрх хуулиар хамгаалагдсан. </footer> ); }


