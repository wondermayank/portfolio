import { useState, useEffect } from "react";
import { Heart, ShoppingBag, Search, X, Star, ChevronLeft, ChevronRight, Minus, Plus, Check, Truck, Shield, Award, MapPin } from "lucide-react";

const PRODUCTS = [
  {
    id: 1,
    name: "Royal Crimson Patola",
    subtitle: "Double Ikat Silk · Patan, Gujarat",
    price: 28500,
    original: 35000,
    rating: 4.9,
    reviews: 128,
    image: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkFFkQGJMfQWfRWSoqm0H2UI6k5dZ_nIh_TA&s",
    badge: "Bestseller",
    badgeColor: "#8B1A2F",
    desc: "Handwoven in Patan with traditional geometric motifs. 6 months of artisan craft.",
    colors: ["#8B1A2F", "#1A3A8B", "#2E6B3E"],
  },
  {
    id: 2,
    name: "Emerald Rajwadi",
    subtitle: "Single Ikat Patola · Surendranagar",
    price: 18900,
    original: 24000,
    rating: 4.8,
    reviews: 95,
    image: "https://ragthm.com/cdn/shop/files/K-037_2.jpg?v=1729594931&width=1946",
    badge: "New Arrival",
    badgeColor: "#2E6B3E",
    desc: "Natural dye weave with classic lotus border. Certified GI-tagged craftsmanship.",
    colors: ["#2E6B3E", "#C5982B", "#8B1A2F"],
  },
  {
    id: 3,
    name: "Ivory Bridal Patola",
    subtitle: "Pure Silk Ikat · Patan Heritage",
    price: 42000,
    original: 55000,
    rating: 5.0,
    reviews: 43,
    image: "https://www.vastranand.in/cdn/shop/files/3_53dcab4f-cced-42e9-b917-b5fbcfc6ed22.jpg",
    badge: "Premium",
    badgeColor: "#C5982B",
    desc: "Bridal masterpiece with golden zari borders and elephant motifs. 9-month weave.",
    colors: ["#F5E6C8", "#C5982B", "#8B1A2F"],
  },
  {
    id: 4,
    name: "Royal Blue Patan",
    subtitle: "Double Ikat Silk · Navaratna",
    price: 32000,
    original: 40000,
    rating: 4.7,
    reviews: 67,
    image: "https://manyavar.scene7.com/is/image/manyavar/TSBS167-426-T.BLUE2_30-01-2021-23-57:894x1263?&dpr=on,2",
    badge: "Heritage",
    badgeColor: "#1A3A8B",
    desc: "Traditional Navaratna pattern in royal blue with intricate gold thread detailing.",
    colors: ["#1A3A8B", "#C5982B", "#8B1A2F"],
  },
  {
    id: 5,
    name: "Saffron Celebration",
    subtitle: "Festive Patola · Peacock Motif",
    price: 22500,
    original: 28000,
    rating: 4.8,
    reviews: 81,
    image: "https://cdn.swadeshonline.com/v2/patient-paper-41f385/swad-p/wrkr/products/pictures/item/free/resize-w:960/swadesh/471006492/1/602D6Vknbr-471006492001_1_LS.jpg",
    badge: "Festive",
    badgeColor: "#C47A1C",
    desc: "Vibrant saffron with classic peacock and parrot motifs. Perfect for festivals.",
    colors: ["#D4621C", "#C5982B", "#2E6B3E"],
  },
  {
    id: 6,
    name: "Antique Gold Zari",
    subtitle: "Vintage Patola · Collector's Edition",
    price: 38000,
    original: 48000,
    rating: 4.9,
    reviews: 52,
    image: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6Eq07RkuSooO03CBIyukq1ncvPKNHOcJLAA&s",
    badge: "Collector's",
    badgeColor: "#5C3A10",
    desc: "Antique gold thread weaving with Gujarati lotus and parrot motifs. Heirloom piece.",
    colors: ["#C5982B", "#8B1A2F", "#1A1008"],
  },
];

const HERO = [
  { img: "https://www.vastranand.in/cdn/shop/files/3_53dcab4f-cced-42e9-b917-b5fbcfc6ed22.jpg", title: "Woven in Silk,\nBorn in Patan", sub: "Six centuries of double ikat artistry" },
  { img: "https://ragthm.com/cdn/shop/files/K-037_2.jpg?v=1729594931&width=1946", title: "Every Thread\nTells a Story", sub: "GI-certified Patola silk sarees" },
  { img: "https://manyavar.scene7.com/is/image/manyavar/TSBS167-426-T.BLUE2_30-01-2021-23-57:894x1263?&dpr=on,2", title: "Royal Heritage\nReborn", sub: "Worn by queens, treasured by generations" },
];

const fmt = (n) => "₹" + n.toLocaleString("en-IN");

export default function PatolaStore() {
  const [liked, setLiked] = useState({});
  const [cart, setCart] = useState([]);
  const [cartOpen, setCartOpen] = useState(false);
  const [slide, setSlide] = useState(0);
  const [toast, setToast] = useState(null);
  const [searchOpen, setSearchOpen] = useState(false);
  const [addedIds, setAddedIds] = useState({});

  useEffect(() => {
    const t = setInterval(() => setSlide(p => (p + 1) % HERO.length), 5000);
    return () => clearInterval(t);
  }, []);

  const addToCart = (p) => {
    setCart(prev => {
      const ex = prev.find(i => i.id === p.id);
      if (ex) return prev.map(i => i.id === p.id ? { ...i, qty: i.qty + 1 } : i);
      return [...prev, { ...p, qty: 1 }];
    });
    setAddedIds(prev => ({ ...prev, [p.id]: true }));
    setTimeout(() => setAddedIds(prev => ({ ...prev, [p.id]: false })), 1500);
    setToast(p.name);
    setTimeout(() => setToast(null), 3000);
  };

  const toggleLike = (id) => setLiked(prev => ({ ...prev, [id]: !prev[id] }));

  const updateQty = (id, d) =>
    setCart(prev => prev.map(i => i.id === id ? { ...i, qty: Math.max(0, i.qty + d) } : i).filter(i => i.qty > 0));

  const cartTotal = cart.reduce((s, i) => s + i.price * i.qty, 0);
  const cartCount = cart.reduce((s, i) => s + i.qty, 0);

  return (
    <div style={{ fontFamily: "'Inter', 'Helvetica Neue', sans-serif", minHeight: "100vh", background: "#FAF5EE", color: "#1A1008", overflowX: "hidden" }}>
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400;1,600&family=Inter:wght@300;400;500;600&display=swap');
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { background: #FAF5EE; }
        .serif { font-family: 'Playfair Display', Georgia, serif; }
        .btn-gold {
          background: linear-gradient(135deg, #C5982B 0%, #E8C45A 50%, #C5982B 100%);
          color: #fff;
          border: none;
          cursor: pointer;
          font-family: 'Inter', sans-serif;
          font-weight: 600;
          letter-spacing: 0.06em;
          font-size: 13px;
          text-transform: uppercase;
          padding: 13px 24px;
          border-radius: 2px;
          transition: all 0.25s ease;
          display: flex;
          align-items: center;
          gap: 8px;
          justify-content: center;
        }
        .btn-gold:hover { filter: brightness(1.08); transform: translateY(-1px); }
        .btn-ghost {
          background: transparent;
          color: #8B1A2F;
          border: 1.5px solid #8B1A2F;
          cursor: pointer;
          font-family: 'Inter', sans-serif;
          font-weight: 500;
          font-size: 13px;
          letter-spacing: 0.05em;
          padding: 11px 20px;
          border-radius: 2px;
          transition: all 0.2s;
          display: flex;
          align-items: center;
          gap: 6px;
          justify-content: center;
        }
        .btn-ghost:hover { background: #8B1A2F; color: #fff; }
        .card {
          background: #fff;
          border-radius: 4px;
          overflow: hidden;
          border: 1px solid #EDE5D8;
          transition: box-shadow 0.3s ease, transform 0.3s ease;
          position: relative;
        }
        .card:hover { box-shadow: 0 12px 40px rgba(139,26,47,0.12); transform: translateY(-4px); }
        .card-img-wrap {
          position: relative;
          overflow: hidden;
          background: #F5EEDF;
        }
        .card-img {
          width: 100%;
          height: 320px;
          object-fit: cover;
          transition: transform 0.6s ease;
          display: block;
        }
        .card:hover .card-img { transform: scale(1.04); }
        .like-btn {
          position: absolute;
          top: 12px;
          right: 12px;
          width: 36px;
          height: 36px;
          border-radius: 50%;
          background: rgba(255,255,255,0.92);
          border: none;
          cursor: pointer;
          display: flex;
          align-items: center;
          justify-content: center;
          transition: all 0.2s;
          backdrop-filter: blur(4px);
          z-index: 2;
        }
        .like-btn:hover { transform: scale(1.15); }
        .badge {
          position: absolute;
          top: 12px;
          left: 12px;
          padding: 4px 10px;
          font-size: 11px;
          font-weight: 600;
          letter-spacing: 0.07em;
          text-transform: uppercase;
          border-radius: 2px;
          color: #fff;
          z-index: 2;
        }
        .star { color: #C5982B; }
        .hero-slide {
          position: absolute;
          inset: 0;
          transition: opacity 0.9s ease;
        }
        .nav-link {
          font-size: 13px;
          font-weight: 500;
          letter-spacing: 0.06em;
          text-transform: uppercase;
          color: #1A1008;
          text-decoration: none;
          cursor: pointer;
          padding: 4px 0;
          border-bottom: 1.5px solid transparent;
          transition: border-color 0.2s, color 0.2s;
        }
        .nav-link:hover { border-color: #C5982B; color: #8B1A2F; }
        .icon-btn {
          background: none;
          border: none;
          cursor: pointer;
          display: flex;
          align-items: center;
          padding: 6px;
          border-radius: 50%;
          transition: background 0.15s;
          color: #1A1008;
        }
        .icon-btn:hover { background: #F0E8DA; }
        .cart-overlay {
          position: fixed;
          inset: 0;
          background: rgba(26,16,8,0.5);
          z-index: 100;
          animation: fadeIn 0.2s ease;
        }
        .cart-drawer {
          position: fixed;
          right: 0;
          top: 0;
          bottom: 0;
          width: 420px;
          max-width: 100vw;
          background: #FAF5EE;
          z-index: 101;
          display: flex;
          flex-direction: column;
          animation: slideIn 0.3s cubic-bezier(0.25,0.46,0.45,0.94);
          border-left: 1px solid #EDE5D8;
        }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        @keyframes slideIn { from { transform: translateX(100%); } to { transform: translateX(0); } }
        @keyframes toastIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        .toast {
          position: fixed;
          bottom: 32px;
          left: 50%;
          transform: translateX(-50%);
          background: #1A1008;
          color: #FAF5EE;
          padding: 14px 24px;
          border-radius: 3px;
          font-size: 14px;
          font-weight: 500;
          z-index: 200;
          animation: toastIn 0.3s ease;
          display: flex;
          align-items: center;
          gap: 10px;
          white-space: nowrap;
          border-left: 3px solid #C5982B;
        }
        .divider-ornament {
          display: flex;
          align-items: center;
          gap: 16px;
          margin: 0 auto;
        }
        .divider-ornament::before, .divider-ornament::after {
          content: '';
          flex: 1;
          height: 1px;
          background: linear-gradient(90deg, transparent, #C5982B, transparent);
        }
        input[type="text"] {
          font-family: 'Inter', sans-serif;
        }
        ::-webkit-scrollbar { width: 5px; }
        ::-webkit-scrollbar-track { background: #FAF5EE; }
        ::-webkit-scrollbar-thumb { background: #DBC99A; border-radius: 10px; }
      `}</style>

      {/* ─── HEADER ─── */}
      <header style={{ position: "sticky", top: 0, zIndex: 50, background: "rgba(250,245,238,0.97)", backdropFilter: "blur(8px)", borderBottom: "1px solid #EDE5D8" }}>
        {/* Announcement */}
        <div style={{ background: "#8B1A2F", color: "#FAF5EE", textAlign: "center", padding: "8px 20px", fontSize: 12, fontWeight: 500, letterSpacing: "0.08em" }}>
          FREE SHIPPING ON ORDERS ABOVE ₹15,000 · AUTHENTIC GI-TAGGED PATOLA
        </div>
        {/* Nav */}
        <div style={{ maxWidth: 1280, margin: "0 auto", padding: "16px 24px", display: "flex", alignItems: "center", gap: 32, justifyContent: "space-between" }}>
          {/* Logo */}
          <div style={{ display: "flex", flexDirection: "column", lineHeight: 1 }}>
            <span className="serif" style={{ fontSize: 22, fontWeight: 700, color: "#8B1A2F", letterSpacing: "0.02em" }}>PATOLA</span>
            <span style={{ fontSize: 9, fontWeight: 500, letterSpacing: "0.22em", color: "#C5982B", textTransform: "uppercase", marginTop: 2 }}>Patan · Gujarat · Est. 1893</span>
          </div>
          {/* Links */}
          <nav style={{ display: "flex", gap: 28, alignItems: "center" }}>
            {["Collections", "Heritage", "Craftsmanship", "About"].map(l => (
              <span key={l} className="nav-link">{l}</span>
            ))}
          </nav>
          {/* Actions */}
          <div style={{ display: "flex", alignItems: "center", gap: 4 }}>
            <button className="icon-btn" aria-label="Search" onClick={() => setSearchOpen(p => !p)}>
              <Search size={20} />
            </button>
            <button className="icon-btn" aria-label="Wishlist">
              <Heart size={20} />
            </button>
            <button className="icon-btn" style={{ position: "relative" }} aria-label="Cart" onClick={() => setCartOpen(true)}>
              <ShoppingBag size={20} />
              {cartCount > 0 && (
                <span style={{ position: "absolute", top: 2, right: 2, width: 17, height: 17, background: "#8B1A2F", borderRadius: "50%", fontSize: 10, fontWeight: 700, color: "#fff", display: "flex", alignItems: "center", justifyContent: "center" }}>
                  {cartCount}
                </span>
              )}
            </button>
          </div>
        </div>
        {/* Search Bar */}
        {searchOpen && (
          <div style={{ borderTop: "1px solid #EDE5D8", padding: "12px 24px", maxWidth: 1280, margin: "0 auto" }}>
            <div style={{ position: "relative", maxWidth: 480 }}>
              <Search size={16} style={{ position: "absolute", left: 12, top: "50%", transform: "translateY(-50%)", color: "#9A8470" }} />
              <input type="text" placeholder="Search patola sarees…" autoFocus style={{ width: "100%", padding: "10px 12px 10px 36px", border: "1.5px solid #DBC99A", borderRadius: 2, fontSize: 14, background: "#fff", outline: "none", color: "#1A1008" }} />
            </div>
          </div>
        )}
      </header>

      {/* ─── HERO ─── */}
      <section style={{ position: "relative", height: "88vh", minHeight: 520, overflow: "hidden", background: "#1A1008" }}>
        {HERO.map((h, i) => (
          <div key={i} className="hero-slide" style={{ opacity: i === slide ? 1 : 0, pointerEvents: i === slide ? "auto" : "none" }}>
            <img src={h.img} alt="" style={{ width: "100%", height: "100%", objectFit: "cover", opacity: 0.55 }} onError={e => e.target.style.display = "none"} />
          </div>
        ))}
        {/* Gradient overlay */}
        <div style={{ position: "absolute", inset: 0, background: "linear-gradient(135deg, rgba(26,16,8,0.75) 0%, rgba(139,26,47,0.3) 100%)" }} />
        {/* Gold border accent */}
        <div style={{ position: "absolute", inset: 20, border: "1px solid rgba(197,152,43,0.35)", pointerEvents: "none" }} />
        <div style={{ position: "absolute", inset: 28, border: "1px solid rgba(197,152,43,0.15)", pointerEvents: "none" }} />

        {/* Content */}
        <div style={{ position: "absolute", inset: 0, display: "flex", flexDirection: "column", alignItems: "center", justifyContent: "center", textAlign: "center", padding: "0 24px" }}>
          <div style={{ marginBottom: 18, display: "flex", alignItems: "center", gap: 12 }}>
            <div style={{ width: 40, height: 1, background: "#C5982B" }} />
            <span style={{ fontSize: 12, fontWeight: 500, letterSpacing: "0.2em", textTransform: "uppercase", color: "#DBC99A" }}>
              <MapPin size={10} style={{ display: "inline", marginRight: 4 }} />Patan, Gujarat
            </span>
            <div style={{ width: 40, height: 1, background: "#C5982B" }} />
          </div>
          <h1 className="serif" style={{ fontSize: "clamp(40px, 7vw, 80px)", fontWeight: 700, color: "#FAF5EE", lineHeight: 1.1, marginBottom: 20, whiteSpace: "pre-line" }}>
            {HERO[slide].title}
          </h1>
          <p style={{ fontSize: 18, color: "rgba(250,245,238,0.75)", fontWeight: 300, letterSpacing: "0.04em", marginBottom: 40 }}>
            {HERO[slide].sub}
          </p>
          <div style={{ display: "flex", gap: 16, flexWrap: "wrap", justifyContent: "center" }}>
            <button className="btn-gold" style={{ fontSize: 14, padding: "15px 36px", borderRadius: 2 }}>
              Explore Collection
            </button>
            <button style={{ background: "transparent", color: "#FAF5EE", border: "1.5px solid rgba(250,245,238,0.6)", cursor: "pointer", fontFamily: "'Inter',sans-serif", fontWeight: 500, fontSize: 14, letterSpacing: "0.06em", padding: "13px 32px", borderRadius: 2, transition: "all 0.2s" }}>
              Our Heritage
            </button>
          </div>
        </div>

        {/* Slide dots */}
        <div style={{ position: "absolute", bottom: 32, left: "50%", transform: "translateX(-50%)", display: "flex", gap: 8 }}>
          {HERO.map((_, i) => (
            <button key={i} onClick={() => setSlide(i)} style={{ width: i === slide ? 28 : 8, height: 8, borderRadius: 4, background: i === slide ? "#C5982B" : "rgba(197,152,43,0.45)", border: "none", cursor: "pointer", transition: "all 0.3s", padding: 0 }} />
          ))}
        </div>

        {/* Arrows */}
        <button onClick={() => setSlide(p => (p - 1 + HERO.length) % HERO.length)} style={{ position: "absolute", left: 24, top: "50%", transform: "translateY(-50%)", width: 44, height: 44, borderRadius: "50%", background: "rgba(250,245,238,0.15)", border: "1px solid rgba(250,245,238,0.3)", color: "#FAF5EE", cursor: "pointer", display: "flex", alignItems: "center", justifyContent: "center", backdropFilter: "blur(4px)", transition: "background 0.2s" }}>
          <ChevronLeft size={20} />
        </button>
        <button onClick={() => setSlide(p => (p + 1) % HERO.length)} style={{ position: "absolute", right: 24, top: "50%", transform: "translateY(-50%)", width: 44, height: 44, borderRadius: "50%", background: "rgba(250,245,238,0.15)", border: "1px solid rgba(250,245,238,0.3)", color: "#FAF5EE", cursor: "pointer", display: "flex", alignItems: "center", justifyContent: "center", backdropFilter: "blur(4px)", transition: "background 0.2s" }}>
          <ChevronRight size={20} />
        </button>
      </section>

      {/* ─── TRUST BAR ─── */}
      <div style={{ background: "#fff", borderTop: "3px solid #C5982B", borderBottom: "1px solid #EDE5D8" }}>
        <div style={{ maxWidth: 1280, margin: "0 auto", padding: "20px 24px", display: "flex", justifyContent: "center", gap: 48, flexWrap: "wrap" }}>
          {[
            { icon: <Award size={20} color="#C5982B" />, label: "GI-Certified Patola", sub: "Govt. of India authenticated" },
            { icon: <Truck size={20} color="#C5982B" />, label: "Free Insured Shipping", sub: "On orders above ₹15,000" },
            { icon: <Shield size={20} color="#C5982B" />, label: "100% Authentic Silk", sub: "Silk Mark certified" },
            { icon: <Check size={20} color="#C5982B" />, label: "30-Day Returns", sub: "Hassle-free exchange" },
          ].map(({ icon, label, sub }) => (
            <div key={label} style={{ display: "flex", alignItems: "center", gap: 12 }}>
              <div style={{ width: 40, height: 40, borderRadius: "50%", background: "#FFF5E0", display: "flex", alignItems: "center", justifyContent: "center", flexShrink: 0 }}>
                {icon}
              </div>
              <div>
                <div style={{ fontSize: 13, fontWeight: 600, color: "#1A1008" }}>{label}</div>
                <div style={{ fontSize: 12, color: "#9A8470" }}>{sub}</div>
              </div>
            </div>
          ))}
        </div>
      </div>

      {/* ─── COLLECTION HEADER ─── */}
      <div style={{ maxWidth: 1280, margin: "0 auto", padding: "64px 24px 32px" }}>
        <div style={{ textAlign: "center", marginBottom: 48 }}>
          <span style={{ fontSize: 11, fontWeight: 600, letterSpacing: "0.2em", textTransform: "uppercase", color: "#C5982B", display: "block", marginBottom: 12 }}>
            ◆ Curated Collection ◆
          </span>
          <h2 className="serif" style={{ fontSize: "clamp(28px, 4vw, 44px)", fontWeight: 700, color: "#1A1008", lineHeight: 1.2, marginBottom: 16 }}>
            The Patola Treasury
          </h2>
          <p style={{ fontSize: 16, color: "#6E5840", maxWidth: 560, margin: "0 auto", lineHeight: 1.7, fontWeight: 300 }}>
            Each piece carries the legacy of Patan's master weavers — handcrafted over months using ancient double ikat techniques passed down through generations.
          </p>
        </div>

        {/* ─── PRODUCT GRID ─── */}
        <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fill, minmax(300px, 1fr))", gap: 28 }}>
          {PRODUCTS.map(p => (
            <div key={p.id} className="card">
              {/* Image */}
              <div className="card-img-wrap">
                <img className="card-img" src={p.image} alt={p.name} onError={e => { e.target.src = "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='320' viewBox='0 0 400 320'%3E%3Crect fill='%23F5EEDF' width='400' height='320'/%3E%3Ctext x='50%25' y='50%25' fill='%23C5982B' text-anchor='middle' font-size='14' dy='.3em'%3EPatola Saree%3C/text%3E%3C/svg%3E"; }} />

                {/* Badge */}
                <span className="badge" style={{ background: p.badgeColor }}>{p.badge}</span>

                {/* Like Button */}
                <button className="like-btn" onClick={() => toggleLike(p.id)} aria-label="Wishlist">
                  <Heart size={16} fill={liked[p.id] ? "#8B1A2F" : "none"} color={liked[p.id] ? "#8B1A2F" : "#6E5840"} />
                </button>

                {/* Overlay color swatches on hover */}
                <div style={{ position: "absolute", bottom: 12, left: 12, display: "flex", gap: 6 }}>
                  {p.colors.map(c => (
                    <div key={c} style={{ width: 16, height: 16, borderRadius: "50%", background: c, border: "2px solid rgba(255,255,255,0.8)", cursor: "pointer" }} title={c} />
                  ))}
                </div>
              </div>

              {/* Info */}
              <div style={{ padding: "20px 20px 24px" }}>
                {/* Rating */}
                <div style={{ display: "flex", alignItems: "center", gap: 6, marginBottom: 10 }}>
                  <div style={{ display: "flex", gap: 2 }}>
                    {[...Array(5)].map((_, i) => (
                      <Star key={i} size={13} fill={i < Math.floor(p.rating) ? "#C5982B" : "none"} color="#C5982B" className="star" />
                    ))}
                  </div>
                  <span style={{ fontSize: 12, fontWeight: 600, color: "#C5982B" }}>{p.rating}</span>
                  <span style={{ fontSize: 12, color: "#9A8470" }}>({p.reviews})</span>
                </div>

                {/* Name */}
                <h3 className="serif" style={{ fontSize: 18, fontWeight: 700, color: "#1A1008", marginBottom: 4, lineHeight: 1.3 }}>{p.name}</h3>
                <p style={{ fontSize: 12, color: "#9A8470", fontWeight: 500, letterSpacing: "0.04em", marginBottom: 10 }}>{p.subtitle}</p>

                {/* Desc */}
                <p style={{ fontSize: 13, color: "#6E5840", lineHeight: 1.6, marginBottom: 16 }}>{p.desc}</p>

                {/* Price */}
                <div style={{ display: "flex", alignItems: "baseline", gap: 10, marginBottom: 18 }}>
                  <span className="serif" style={{ fontSize: 22, fontWeight: 700, color: "#8B1A2F" }}>{fmt(p.price)}</span>
                  <span style={{ fontSize: 14, color: "#9A8470", textDecoration: "line-through" }}>{fmt(p.original)}</span>
                  <span style={{ fontSize: 12, fontWeight: 700, color: "#2E6B3E", background: "#E6F4EB", padding: "2px 8px", borderRadius: 2 }}>
                    {Math.round((1 - p.price / p.original) * 100)}% OFF
                  </span>
                </div>

                {/* Actions */}
                <div style={{ display: "flex", gap: 10 }}>
                  <button className="btn-gold" style={{ flex: 1 }} onClick={() => addToCart(p)}>
                    {addedIds[p.id] ? <><Check size={14} /> Added</> : <><ShoppingBag size={14} /> Add to Cart</>}
                  </button>
                  <button className="btn-ghost" style={{ padding: "11px 14px" }} onClick={() => toggleLike(p.id)} aria-label="Wishlist">
                    <Heart size={16} fill={liked[p.id] ? "#8B1A2F" : "none"} color="#8B1A2F" />
                  </button>
                </div>
              </div>
            </div>
          ))}
        </div>

        {/* Load More */}
        <div style={{ textAlign: "center", marginTop: 56, marginBottom: 32 }}>
          <button className="btn-ghost" style={{ padding: "14px 48px", fontSize: 14 }}>
            View Full Collection
          </button>
        </div>
      </div>

      {/* ─── HERITAGE STRIP ─── */}
      <div style={{ background: "#1A1008", padding: "64px 24px", textAlign: "center" }}>
        <div style={{ maxWidth: 720, margin: "0 auto" }}>
          <span style={{ fontSize: 11, fontWeight: 600, letterSpacing: "0.2em", textTransform: "uppercase", color: "#C5982B", display: "block", marginBottom: 16 }}>◆ Our Promise ◆</span>
          <h2 className="serif" style={{ fontSize: "clamp(22px, 3.5vw, 36px)", fontWeight: 600, color: "#FAF5EE", lineHeight: 1.4, fontStyle: "italic", marginBottom: 24 }}>
            "Each Patola takes 3 to 9 months to weave — a sacred geometry of warp and weft, coloured before they meet."
          </h2>
          <p style={{ fontSize: 14, color: "#9A8470", letterSpacing: "0.06em", textTransform: "uppercase", fontWeight: 500 }}>
            — Master Weavers of Patan, Gujarat
          </p>
          <div style={{ display: "flex", justifyContent: "center", gap: 48, marginTop: 48, flexWrap: "wrap" }}>
            {[["600+", "Years of Tradition"], ["47", "Master Artisans"], ["3–9", "Months per Saree"], ["100%", "Pure Silk"]].map(([n, l]) => (
              <div key={l} style={{ textAlign: "center" }}>
                <div className="serif" style={{ fontSize: 36, fontWeight: 700, color: "#C5982B" }}>{n}</div>
                <div style={{ fontSize: 12, color: "#9A8470", letterSpacing: "0.08em", textTransform: "uppercase", marginTop: 4, fontWeight: 500 }}>{l}</div>
              </div>
            ))}
          </div>
        </div>
      </div>

      {/* ─── FOOTER ─── */}
      <footer style={{ background: "#0F0803", color: "#9A8470", padding: "48px 24px", textAlign: "center" }}>
        <div className="serif" style={{ fontSize: 20, fontWeight: 700, color: "#C5982B", marginBottom: 8 }}>PATOLA</div>
        <p style={{ fontSize: 12, letterSpacing: "0.15em", textTransform: "uppercase", marginBottom: 24 }}>Patan · Gujarat · Crafted Since 1893</p>
        <p style={{ fontSize: 13, color: "#5A4A3C" }}>© 2025 Patola Heritage. All rights reserved. GI Tag: GI/2013/0000059</p>
      </footer>

      {/* ─── CART DRAWER ─── */}
      {cartOpen && (
        <>
          <div className="cart-overlay" onClick={() => setCartOpen(false)} />
          <div className="cart-drawer">
            {/* Header */}
            <div style={{ padding: "24px 24px 20px", borderBottom: "1px solid #EDE5D8", display: "flex", justifyContent: "space-between", alignItems: "center", background: "#fff" }}>
              <div>
                <h2 className="serif" style={{ fontSize: 20, fontWeight: 700, color: "#1A1008" }}>Your Cart</h2>
                <p style={{ fontSize: 12, color: "#9A8470", marginTop: 2 }}>{cartCount} item{cartCount !== 1 ? "s" : ""}</p>
              </div>
              <button className="icon-btn" onClick={() => setCartOpen(false)} aria-label="Close cart">
                <X size={20} />
              </button>
            </div>

            {/* Items */}
            <div style={{ flex: 1, overflowY: "auto", padding: "16px 24px" }}>
              {cart.length === 0 ? (
                <div style={{ textAlign: "center", padding: "60px 0" }}>
                  <ShoppingBag size={48} color="#DBC99A" style={{ margin: "0 auto 16px", display: "block" }} />
                  <p className="serif" style={{ fontSize: 18, color: "#9A8470", fontStyle: "italic" }}>Your cart is empty</p>
                  <p style={{ fontSize: 13, color: "#C5AC8A", marginTop: 8 }}>Add a Patola to get started</p>
                  <button className="btn-gold" style={{ marginTop: 24, padding: "12px 28px" }} onClick={() => setCartOpen(false)}>
                    Browse Collection
                  </button>
                </div>
              ) : (
                <div style={{ display: "flex", flexDirection: "column", gap: 16 }}>
                  {cart.map(item => (
                    <div key={item.id} style={{ display: "flex", gap: 14, padding: 14, background: "#fff", borderRadius: 4, border: "1px solid #EDE5D8" }}>
                      <img src={item.image} alt={item.name} style={{ width: 72, height: 88, objectFit: "cover", borderRadius: 2, flexShrink: 0 }} onError={e => e.target.style.display = "none"} />
                      <div style={{ flex: 1, minWidth: 0 }}>
                        <h4 className="serif" style={{ fontSize: 14, fontWeight: 700, color: "#1A1008", marginBottom: 2, whiteSpace: "nowrap", overflow: "hidden", textOverflow: "ellipsis" }}>{item.name}</h4>
                        <p style={{ fontSize: 11, color: "#9A8470", marginBottom: 10 }}>{item.subtitle}</p>
                        <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center" }}>
                          <div style={{ display: "flex", alignItems: "center", gap: 8, border: "1px solid #EDE5D8", borderRadius: 2, overflow: "hidden" }}>
                            <button onClick={() => updateQty(item.id, -1)} style={{ width: 28, height: 28, background: "none", border: "none", cursor: "pointer", display: "flex", alignItems: "center", justifyContent: "center", color: "#6E5840" }}>
                              <Minus size={13} />
                            </button>
                            <span style={{ fontSize: 13, fontWeight: 600, minWidth: 20, textAlign: "center", color: "#1A1008" }}>{item.qty}</span>
                            <button onClick={() => updateQty(item.id, 1)} style={{ width: 28, height: 28, background: "none", border: "none", cursor: "pointer", display: "flex", alignItems: "center", justifyContent: "center", color: "#6E5840" }}>
                              <Plus size={13} />
                            </button>
                          </div>
                          <span className="serif" style={{ fontSize: 16, fontWeight: 700, color: "#8B1A2F" }}>{fmt(item.price * item.qty)}</span>
                        </div>
                      </div>
                    </div>
                  ))}
                </div>
              )}
            </div>

            {/* Footer */}
            {cart.length > 0 && (
              <div style={{ padding: "20px 24px", borderTop: "1px solid #EDE5D8", background: "#fff" }}>
                <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: 6 }}>
                  <span style={{ fontSize: 13, color: "#9A8470" }}>Subtotal</span>
                  <span className="serif" style={{ fontSize: 20, fontWeight: 700, color: "#1A1008" }}>{fmt(cartTotal)}</span>
                </div>
                <p style={{ fontSize: 11, color: "#9A8470", marginBottom: 20 }}>
                  {cartTotal >= 15000 ? "✓ Free insured shipping included" : `Add ${fmt(15000 - cartTotal)} more for free shipping`}
                </p>
                <button className="btn-gold" style={{ width: "100%", padding: "16px", fontSize: 14, borderRadius: 2 }}>
                  Proceed to Checkout
                </button>
                <button className="btn-ghost" style={{ width: "100%", marginTop: 10, padding: "13px" }} onClick={() => setCartOpen(false)}>
                  Continue Shopping
                </button>
              </div>
            )}
          </div>
        </>
      )}

      {/* ─── TOAST ─── */}
      {toast && (
        <div className="toast">
          <Check size={16} color="#C5982B" />
          <span><strong>{toast}</strong> added to cart</span>
        </div>
      )}
    </div>
  );
}
