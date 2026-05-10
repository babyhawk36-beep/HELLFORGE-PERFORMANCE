export default function HellForgePerformance() {
  const testimonials = [
    {
      name: 'East Coast Mopar Customs',
      quote: 'HELLFORGE PERFORMANCE helped us source premium widebody kits and performance upgrades fast.'
    },
    {
      name: 'SRT Performance Garage',
      quote: 'Top-tier wholesale pricing and serious Mopar inventory for our builds.'
    },
    {
      name: 'American Muscle Labs',
      quote: 'The best supplier for Hellcat, Trackhawk, and Challenger widebody conversions.'
    }
  ];
  const featuredProducts = [
    {
      name: 'Charger Hellcat Widebody Kit',
      price: '$2,499',
      image: 'https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1200&auto=format&fit=crop'
    },
    {
      name: 'Challenger Demon Widebody Kit',
      price: '$2,899',
      image: 'https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?q=80&w=1200&auto=format&fit=crop'
    },
    {
      name: 'Trackhawk Widebody Conversion',
      price: '$4,299',
      image: 'https://images.unsplash.com/photo-1511919884226-fd3cad34687c?q=80&w=1200&auto=format&fit=crop'
    },
    {
      name: '300C SRT Widebody Kit',
      price: '$2,199',
      image: 'https://images.unsplash.com/photo-1549399542-7e3f8b79c341?q=80&w=1200&auto=format&fit=crop'
    },
    {
      name: 'Durango SRT Aero Package',
      price: '$3,199',
      image: 'https://images.unsplash.com/photo-1552519507-da3b142c6e3d?q=80&w=1200&auto=format&fit=crop'
    },
    {
      name: 'Forged HellForge Wheels',
      price: '$1,899',
      image: 'https://images.unsplash.com/photo-1489824904134-891ab64532f1?q=80&w=1200&auto=format&fit=crop'
    }
  ];

  const partnerBrands = [
    'Mopar',
    'Brembo',
    'Borla',
    'Air Lift Performance',
    'KW Suspension',
    'Forgiato',
    'Nitto Tires',
    'HRE Wheels'
  ];

  const moparGallery = [
    'https://images.unsplash.com/photo-1494905998402-395d579af36f?q=80&w=1400&auto=format&fit=crop',
    'https://images.unsplash.com/photo-1502877338535-766e1452684a?q=80&w=1400&auto=format&fit=crop',
    'https://images.unsplash.com/photo-1544636331-e26879cd4d9b?q=80&w=1400&auto=format&fit=crop'
  ];

  const categories = [
    'Charger Widebody Kits',
    'Challenger Widebody Kits',
    '300C Widebody Kits',
    'Durango SRT Body Kits',
    'Trackhawk Widebody Kits',
    'Mopar Performance Parts',
    'Exhaust Systems',
    'Suspension Upgrades',
    'Custom Wheels',
    'Wholesale Dealer Packages'
  ];

  return (
    <div className="min-h-screen bg-black text-white">
      {/* Header */}
      <header className="border-b border-red-700 bg-black/95 sticky top-0 z-50">
        <div className="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
          <div>
            <h1 className="text-3xl font-black tracking-widest text-red-600">
              HELLFORGE PERFORMANCE
            </h1>
            <p className="text-sm text-gray-400 uppercase tracking-[0.3em]">
              Wholesale Mopar Performance Parts
            </p>
          </div>

          <nav className="hidden md:flex gap-8 text-sm uppercase tracking-wide">
            <a href="#shop" className="hover:text-red-500 transition">Shop</a>
            <a href="#categories" className="hover:text-red-500 transition">Categories</a>
            <a href="#wholesale" className="hover:text-red-500 transition">Wholesale</a>
            <a href="#contact" className="hover:text-red-500 transition">Contact</a>
          </nav>

          <div className="flex gap-3">
            <button className="border border-white/20 hover:border-red-600 px-5 py-2 rounded-2xl font-bold transition">
              Cart (0)
            </button>

            <button className="bg-red-700 hover:bg-red-600 px-5 py-2 rounded-2xl font-bold transition shadow-xl">
              Dealer Login
            </button>
          </div>
        </div>
      </header>

      {/* Hero */}
      <section className="relative overflow-hidden">
        <div
          className="absolute inset-0 bg-cover bg-center opacity-30"
          style={{
            backgroundImage:
              "url('https://images.unsplash.com/photo-1494976388531-d1058494cdd8?q=80&w=1600&auto=format&fit=crop')"
          }}
        />

        <div className="relative max-w-7xl mx-auto px-6 py-28 grid lg:grid-cols-2 gap-12 items-center">
          <div>
            <p className="uppercase tracking-[0.4em] text-red-500 mb-4 text-sm">
              Wholesale Performance Distribution
            </p>

            <h2 className="text-5xl md:text-7xl font-black leading-tight mb-6">
              BUILT FOR
              <span className="block text-red-600">MOPAR POWER</span>
            </h2>

            <p className="text-gray-300 text-lg leading-relaxed mb-8 max-w-xl">
              HELLFORGE PERFORMANCE delivers premium wholesale performance parts, full widebody conversion kits, forged wheels, aero packages, and high-horsepower upgrades for every major Mopar platform including Charger, Challenger, Chrysler 300, Durango SRT, Jeep Trackhawk, and Hellcat builds.
            </p>

            <div className="flex flex-wrap gap-4">
              <button className="bg-red-700 hover:bg-red-600 px-8 py-4 rounded-2xl font-bold text-lg transition shadow-2xl">
                Shop Performance Parts
              </button>

              <button className="border border-white/30 hover:border-red-600 hover:text-red-500 px-8 py-4 rounded-2xl font-bold text-lg transition">
                Apply for Wholesale Pricing
              </button>
            </div>
          </div>

          <div className="bg-white/5 backdrop-blur-lg border border-white/10 rounded-3xl p-8 shadow-2xl">
            <h3 className="text-3xl font-black mb-6 text-red-500">
              Why HELLFORGE?
            </h3>

            <div className="space-y-5">
              <div className="bg-black/40 p-5 rounded-2xl border border-white/5">
                <h4 className="font-bold text-xl mb-2">Wholesale Dealer Pricing</h4>
                <p className="text-gray-400">
                  Special bulk pricing for performance shops, garages, and resellers.
                </p>
              </div>

              <div className="bg-black/40 p-5 rounded-2xl border border-white/5">
                <h4 className="font-bold text-xl mb-2">Premium Mopar Inventory</h4>
                <p className="text-gray-400">
                  Curated inventory focused on high-performance Dodge and Mopar builds.
                </p>
              </div>

              <div className="bg-black/40 p-5 rounded-2xl border border-white/5">
                <h4 className="font-bold text-xl mb-2">Nationwide Shipping</h4>
                <p className="text-gray-400">
                  Fast order processing and delivery across the United States.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Categories */}
      <section id="categories" className="py-20 bg-zinc-950">
        <div className="max-w-7xl mx-auto px-6">
          <div className="flex justify-between items-end mb-12 flex-wrap gap-4">
            <div>
              <p className="uppercase tracking-[0.3em] text-red-500 text-sm mb-3">
                Product Categories
              </p>
              <h3 className="text-4xl font-black">Performance Inventory</h3>
            </div>

            <button className="border border-red-700 px-6 py-3 rounded-2xl hover:bg-red-700 transition font-bold">
              View All Products
            </button>
          </div>

          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            {categories.map((category, index) => (
              <div
                key={index}
                className="bg-black border border-white/10 hover:border-red-700 p-8 rounded-3xl transition duration-300 hover:-translate-y-1 shadow-xl"
              >
                <div className="w-14 h-14 rounded-2xl bg-red-700/20 flex items-center justify-center text-red-500 font-black text-2xl mb-6">
                  {index + 1}
                </div>

                <h4 className="text-2xl font-bold mb-3">{category}</h4>

                <p className="text-gray-400 leading-relaxed">
                  Premium wholesale inventory including complete widebody kits and custom aero solutions for all major Mopar platforms.
                </p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {{/* Mopar Gallery */}
      <section className="py-20 bg-zinc-950">
        <div className="max-w-7xl mx-auto px-6">
          <div className="text-center mb-14">
            <p className="uppercase tracking-[0.3em] text-red-500 text-sm mb-3">
              Mopar Builds
            </p>
            <h3 className="text-5xl font-black">HELLFORGE Showcase</h3>
          </div>

          <div className="grid lg:grid-cols-3 gap-6">
            {moparGallery.map((image, index) => (
              <div
                key={index}
                className="overflow-hidden rounded-3xl border border-white/10 hover:border-red-700 transition shadow-2xl"
              >
                <img
                  src={image}
                  alt="HELLFORGE Mopar Build"
                  className="w-full h-[350px] object-cover hover:scale-105 transition duration-500"
                />
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Brand Partners */}
      <section className="py-20 bg-black border-y border-white/5">
        <div className="max-w-7xl mx-auto px-6 text-center">
          <p className="uppercase tracking-[0.3em] text-red-500 text-sm mb-3">
            Trusted Performance Brands
          </p>

          <h3 className="text-5xl font-black mb-14">
            Brands We Work With
          </h3>

          <div className="grid grid-cols-2 md:grid-cols-4 gap-6">
            {partnerBrands.map((brand, index) => (
              <div
                key={index}
                className="bg-zinc-950 border border-white/10 rounded-3xl p-8 flex items-center justify-center text-2xl font-black hover:border-red-700 transition shadow-xl"
              >
                {brand}
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Featured Products */}}
      <section id="shop" className="py-20 bg-black">
        <div className="max-w-7xl mx-auto px-6">
          <div className="text-center mb-14">
            <p className="uppercase tracking-[0.3em] text-red-500 text-sm mb-3">
              Featured Products
            </p>
            <h3 className="text-5xl font-black">Top Selling Upgrades</h3>
          </div>

          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            {featuredProducts.map((product, index) => (
              <div
                key={index}
                className="bg-zinc-950 rounded-3xl overflow-hidden border border-white/10 hover:border-red-700 transition duration-300 shadow-2xl"
              >
                <img
                  src={product.image}
                  alt={product.name}
                  className="w-full h-64 object-cover"
                />

                <div className="p-6">
                  <div className="flex justify-between items-center mb-4">
                    <h4 className="text-2xl font-bold">{product.name}</h4>
                    <span className="text-red-500 font-black text-xl">
                      {product.price}
                    </span>
                  </div>

                  <p className="text-gray-400 mb-6 leading-relaxed">
                    High-quality performance upgrade designed for maximum horsepower and aggressive styling.
                  </p>

                  <button className="w-full bg-red-700 hover:bg-red-600 py-4 rounded-2xl font-bold transition">
                    Add to Cart
                  </button>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Wholesale CTA */}
      <section id="wholesale" className="py-24 bg-gradient-to-r from-red-900 to-black">
        <div className="max-w-5xl mx-auto px-6 text-center">
          <p className="uppercase tracking-[0.4em] text-red-300 text-sm mb-4">
            Wholesale Partnership Program
          </p>

          <h3 className="text-5xl font-black mb-6">
            Build Your Performance Business With HELLFORGE
          </h3>

          <p className="text-lg text-gray-200 leading-relaxed max-w-3xl mx-auto mb-10">
            Apply for wholesale access to unlock bulk pricing, dealer discounts,
            priority support, and exclusive inventory for your shop or online store.
          </p>

          <div className="flex flex-wrap justify-center gap-5">
            <button className="bg-white text-black hover:bg-gray-200 px-8 py-4 rounded-2xl font-black text-lg transition">
              Become a Dealer
            </button>

            <button className="border border-white px-8 py-4 rounded-2xl font-black text-lg hover:bg-white hover:text-black transition">
              Contact Sales Team
            </button>
          </div>
        </div>
      </section>

      {{/* Dealer Application */}
      <section className="py-20 bg-zinc-950">
        <div className="max-w-4xl mx-auto px-6">
          <div className="text-center mb-12">
            <p className="uppercase tracking-[0.3em] text-red-500 text-sm mb-3">
              Dealer Access
            </p>
            <h3 className="text-5xl font-black">
              Apply For Wholesale Pricing
            </h3>
          </div>

          <div className="bg-black border border-white/10 rounded-3xl p-8 shadow-2xl space-y-6">
            <div className="grid md:grid-cols-2 gap-6">
              <input type="text" placeholder="Business Name" className="bg-zinc-900 border border-white/10 rounded-2xl p-4 outline-none focus:border-red-600" />
              <input type="email" placeholder="Business Email" className="bg-zinc-900 border border-white/10 rounded-2xl p-4 outline-none focus:border-red-600" />
            </div>

            <div className="grid md:grid-cols-2 gap-6">
              <input type="text" placeholder="Phone Number" className="bg-zinc-900 border border-white/10 rounded-2xl p-4 outline-none focus:border-red-600" />
              <input type="text" placeholder="Website or Social Media" className="bg-zinc-900 border border-white/10 rounded-2xl p-4 outline-none focus:border-red-600" />
            </div>

            <textarea placeholder="Tell us about your business" rows="5" className="w-full bg-zinc-900 border border-white/10 rounded-2xl p-4 outline-none focus:border-red-600"></textarea>

            <button className="w-full bg-red-700 hover:bg-red-600 py-4 rounded-2xl font-black text-lg transition">
              Submit Dealer Application
            </button>
          </div>
        </div>
      </section>

      {/* Testimonials */}
      <section className="py-20 bg-black">
        <div className="max-w-7xl mx-auto px-6">
          <div className="text-center mb-14">
            <p className="uppercase tracking-[0.3em] text-red-500 text-sm mb-3">
              Performance Community
            </p>
            <h3 className="text-5xl font-black">Trusted By Mopar Builders</h3>
          </div>

          <div className="grid lg:grid-cols-3 gap-8">
            {testimonials.map((testimonial, index) => (
              <div key={index} className="bg-zinc-950 border border-white/10 rounded-3xl p-8 shadow-2xl hover:border-red-700 transition">
                <h4 className="text-2xl font-black mb-4 text-red-500">
                  {testimonial.name}
                </h4>

                <p className="text-gray-300 leading-relaxed text-lg">
                  “{testimonial.quote}”
                </p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Newsletter */}
      <section className="py-20 bg-gradient-to-r from-black to-red-950 border-y border-white/5">
        <div className="max-w-5xl mx-auto px-6 text-center">
          <h3 className="text-5xl font-black mb-6">
            Join The HELLFORGE Network
          </h3>

          <p className="text-gray-300 text-lg mb-10">
            Get new widebody kit releases, wholesale inventory updates, and exclusive Mopar performance deals.
          </p>

          <div className="flex flex-col md:flex-row gap-4 max-w-2xl mx-auto">
            <input
              type="email"
              placeholder="Enter your email"
              className="flex-1 bg-black border border-white/10 rounded-2xl p-4 outline-none focus:border-red-600"
            />

            <button className="bg-red-700 hover:bg-red-600 px-8 py-4 rounded-2xl font-black transition">
              Subscribe
            </button>
          </div>
        </div>
      </section>

      {/* Footer */}}
      <footer id="contact" className="bg-black border-t border-white/10 py-12">
        <div className="max-w-7xl mx-auto px-6 grid md:grid-cols-3 gap-10">
          <div>
            <h4 className="text-2xl font-black text-red-600 mb-4">
              HELLFORGE PERFORMANCE
            </h4>

            <p className="text-gray-400 leading-relaxed">
              Wholesale Mopar performance parts, widebody kits, wheels, suspension,
              and high-performance upgrades.
            </p>
          </div>

          <div>
            <h5 className="font-bold text-lg mb-4">Quick Links</h5>
            <div className="space-y-3 text-gray-400">
              <p>Shop Products</p>
              <p>Dealer Program</p>
              <p>Shipping Policy</p>
              <p>Returns & Support</p>
            </div>
          </div>

          <div>
            <h5 className="font-bold text-lg mb-4">Business Contact</h5>
            <div className="space-y-3 text-gray-400">
              <p>Email: sales@hellforgeperformance.com</p>
              <p>Phone: (800) 555-HELL</p>
              <p>Nationwide Wholesale Distribution</p>
            </div>
          </div>
        </div>

        <div className="text-center text-gray-600 mt-12 text-sm border-t border-white/5 pt-8">
          © 2026 HELLFORGE PERFORMANCE — Built for American Muscle.
        </div>
      </footer>
    </div>
  );
}
