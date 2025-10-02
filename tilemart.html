import { useState } from "react";
import { motion, AnimatePresence } from "framer-motion";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { ShoppingCart, Search, Filter } from "lucide-react";

const products = [
  {
    id: 1,
    name: "Marble White Tile",
    price: 2000,
    image: "https://i.pinimg.com/736x/7e/23/f9/7e23f98c89ab999013f76ab7f0d30fe8.jpg",
    color: "White",
    category: "Marble",
    brand: "TileCo"
  },
  {
    id: 2,
    name: "Granite Black Tile",
    price: 2500,
    image: "https://i.pinimg.com/1200x/61/d7/59/61d759263cdf397dc5545b5da1e404a5.jpg",
    color: "Black",
    category: "Granite",
    brand: "Granito"
  },
  {
    id: 3,
    name: "Ceramic Beige Tile",
    price: 1500,
    image: "https://i.pinimg.com/1200x/0b/4d/97/0b4d97d6d7ea6045d000612b63ac1234.jpg",
    color: "Beige",
    category: "Ceramic",
    brand: "Ceramica"
  },
  {
    id: 4,
    name: "Porcelain Gray Tile",
    price: 2200,
    image: "https://i.pinimg.com/736x/27/82/9a/27829ad84125506a6a60bdcc66af18fd.jpg",
    color: "Gray",
    category: "Porcelain",
    brand: "Porcelanosa"
  },
  {
    id: 5,
    name: "Mosaic Blue Tile",
    price: 2800,
    image: "https://i.pinimg.com/1200x/95/66/4c/95664c5c2bc5511467c84cd6fd8bf19f.jpg",
    color: "Blue",
    category: "Mosaic",
    brand: "Mosaico"
  },
  {
    id: 6,
    name: "Terracotta Rustic Tile",
    price: 1800,
    image: "https://i.pinimg.com/736x/1e/83/e5/1e83e5e317b210843eecab2b14d26e47.jpg",
    color: "Brown",
    category: "Terracotta",
    brand: "Rustico"
  },
  {
    id: 7,
    name: "Textured Stone Tile",
    price: 3000,
    image: "https://i.pinimg.com/1200x/b1/15/1d/b1151d2f3428f1867fe3724745919898.jpg",
    color: "Gray",
    category: "Stone",
    brand: "StoneCraft"
  },
  {
    id: 8,
    name: "Patterned Decorative Tile",
    price: 3500,
    image: "https://i.pinimg.com/736x/43/c4/39/43c43965225150eee7f5ddce97078b07.jpg",
    color: "Multi",
    category: "Decorative",
    brand: "Decora"
  }
];

const colors = ['All','White','Black','Beige','Gray','Blue','Brown','Multi'];
const categories = ['All','Marble','Granite','Ceramic','Porcelain','Mosaic','Terracotta','Stone','Decorative'];

export default function TilesStore() {
  const [cart, setCart] = useState([]);
  const [search, setSearch] = useState("");
  const [filterColor, setFilterColor] = useState("All");
  const [filterCategory, setFilterCategory] = useState("All");
  const [showCart, setShowCart] = useState(false);
  const [checkout, setCheckout] = useState(false);
  const [paymentDone, setPaymentDone] = useState(false);

  const filteredProducts = products.filter((p) =>
    (filterColor === "All" || p.color === filterColor) &&
    (filterCategory === "All" || p.category === filterCategory) &&
    p.name.toLowerCase().includes(search.toLowerCase())
  );

  const addToCart = (product) => {
    setCart([...cart, product]);
  };

  const total = cart.reduce((sum, item) => sum + item.price, 0);

  return (
    <div className="min-h-screen bg-gray-50 flex flex-col justify-between">
      {!checkout && !paymentDone ? (
        <>
        <div>
          {/* Navbar */}
          <nav className="flex items-center justify-between p-4 bg-white shadow">
            <h1 className="text-2xl font-bold text-gray-800">TileMart</h1>
            <div className="flex gap-2 items-center">
              <div className="flex items-center border rounded-lg px-2">
                <Search className="h-4 w-4 text-gray-500" />
                <input
                  type="text"
                  placeholder="Search tiles..."
                  className="ml-2 outline-none p-1"
                  value={search}
                  onChange={(e) => setSearch(e.target.value)}
                />
              </div>
              <Button onClick={() => setShowCart(true)}>
                <ShoppingCart className="mr-2 h-4 w-4" /> Cart ({cart.length})
              </Button>
            </div>
          </nav>

          {/* Filters */}
          <div className="flex flex-col md:flex-row justify-center p-4 gap-3">
            <div className="flex gap-2 flex-wrap justify-center">
              {colors.map(c => (
                <Button
                  key={c}
                  variant={filterColor===c ? "default" : "outline"}
                  onClick={() => setFilterColor(c)}>
                  <Filter className="h-4 w-4 mr-1"/> {c}
                </Button>
              ))}
            </div>
            <div className="flex gap-2 flex-wrap justify-center">
              {categories.map(cat => (
                <Button
                  key={cat}
                  variant={filterCategory===cat ? "default" : "outline"}
                  onClick={() => setFilterCategory(cat)}>
                  <Filter className="h-4 w-4 mr-1"/> {cat}
                </Button>
              ))}
            </div>
          </div>

          {/* Products */}
          <div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6 p-6">
            {filteredProducts.map(product => (
              <motion.div key={product.id} initial={{opacity:0,y:20}} animate={{opacity:1,y:0}}>
                <Card className="rounded-2xl shadow hover:shadow-lg transition cursor-pointer">
                  <img src={product.image} alt={product.name} className="h-48 w-full object-cover rounded-t-2xl"/>
                  <CardContent className="p-4">
                    <h2 className="text-lg font-semibold">{product.name}</h2>
                    <p className="text-gray-600">₹{product.price}</p>
                    <p className="text-sm text-gray-500">{product.category}</p>
                    <Button className="mt-3 w-full" onClick={() => addToCart(product)}>Add to Cart</Button>
                  </CardContent>
                </Card>
              </motion.div>
            ))}
          </div>
        </div>

        {/* About Section */}
        <footer className="relative bg-white shadow-inner p-6 mt-6 text-center overflow-hidden">
          <img 
            src="https://i.pinimg.com/736x/7e/23/f9/7e23f98c89ab999013f76ab7f0d30fe8.jpg" 
            alt="Tile background" 
            className="absolute inset-0 w-full h-full object-cover opacity-20" 
          />
          <div className="relative z-10">
            <h2 className="text-xl font-bold mb-2">About TileMart</h2>
            <p className="text-gray-700 font-medium max-w-3xl mx-auto">
              At TileMart, we bring you the finest selection of tiles from around the world. From luxurious marbles to durable granite, elegant porcelain, and artistic mosaics, our mission is to provide top-quality products to transform your spaces. With a passion for design and a commitment to customer satisfaction, we make tile shopping simple, inspiring, and affordable.
            </p>
            <p className="text-gray-700 mt-2 font-medium">
              Contact us: support@tilemart.com | +91 98765 43210
            </p>
          </div>
        </footer>

        {/* Cart Sidebar */}
        <AnimatePresence>
          {showCart && (
            <motion.div
              initial={{x: "100%"}}
              animate={{x:0}}
              exit={{x: "100%"}}
              className="fixed top-0 right-0 w-80 h-full bg-white shadow-2xl z-50 p-6 flex flex-col">
              <h2 className="text-xl font-bold mb-4">Your Cart</h2>
              <div className="flex-1 overflow-y-auto">
                {cart.length === 0 ? <p className="text-gray-500">Cart is empty</p> : (
                  cart.map((item, i) => (
                    <div key={i} className="flex justify-between border-b py-2">
                      <span>{item.name}</span>
                      <span>₹{item.price}</span>
                    </div>
                  ))
                )}
              </div>
              <div className="mt-4 font-semibold">Total: ₹{total}</div>
              <Button className="mt-3 w-full" onClick={() => setCheckout(true)}>Checkout</Button>
              <Button variant="outline" className="mt-2 w-full" onClick={()=>setShowCart(false)}>Close</Button>
            </motion.div>
          )}
        </AnimatePresence>
        </>
      ) : checkout && !paymentDone ? (
        <div className="flex flex-col items-center justify-center flex-1 p-6">
          <h2 className="text-2xl font-bold mb-4">Checkout</h2>
          <div className="bg-white shadow rounded-lg p-6 w-full max-w-md">
            <h3 className="text-lg font-semibold mb-2">Order Summary</h3>
            {cart.map((item, i) => (
              <div key={i} className="flex justify-between py-1 border-b">
                <span>{item.name}</span>
                <span>₹{item.price}</span>
              </div>
            ))}
            <div className="mt-2 font-semibold">Total: ₹{total}</div>

            <h3 className="text-lg font-semibold mt-4 mb-2">Payment Details</h3>
            <input type="text" placeholder="Card Number" className="border p-2 rounded w-full mb-2"/>
            <div className="flex gap-2">
              <input type="text" placeholder="MM/YY" className="border p-2 rounded w-1/2"/>
              <input type="text" placeholder="CVV" className="border p-2 rounded w-1/2"/>
            </div>
            <input type="text" placeholder="Cardholder Name" className="border p-2 rounded w-full mt-2"/>

            <Button className="mt-4 w-full" onClick={() => {setPaymentDone(true); setCheckout(false);}}>Pay Now</Button>
            <Button variant="outline" className="mt-2 w-full" onClick={() => setCheckout(false)}>Back</Button>
          </div>
        </div>
      ) : (
        <div className="flex flex-col items-center justify-center flex-1 p-6 text-center">
          <h2 className="text-3xl font-bold mb-4 text-green-600">Payment Successful ✅</h2>
          <p className="text-gray-700 mb-6">Thank you for your purchase! Your order has been placed successfully.</p>
          <Button className="w-full max-w-sm" onClick={() => {setPaymentDone(false); setCart([]);}}>Continue Shopping</Button>
        </div>
      )}
    </div>
  );
}
