<template>
  <div id="app">
    <!-- Header Section -->
    <header class="header">
      <div class="container">
        <div class="logo">
          <h1>🎮 Kids Toy Store</h1>
        </div>
        <nav class="nav">
          <a href="#" class="nav-link active">Home</a>
          <a href="#" class="nav-link">Toys</a>
          <a href="#" class="nav-link">Games</a>
          <a href="#" class="nav-link">New Arrivals</a>
          <a href="#" class="nav-link">Sale</a>
          <a href="#" class="nav-link">Contact</a>
        </nav>
        <div class="header-actions">
          <button class="icon-btn">
            <span class="icon">🔍</span>
          </button>
          <button class="icon-btn">
            <span class="icon">🛒</span>
            <span class="badge">3</span>
          </button>
          <button class="btn-primary">Sign In</button>
        </div>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
      <div class="container">
        <div class="hero-content">
          <h2 class="hero-title">Fun & Learning Together!</h2>
          <p class="hero-subtitle">Discover amazing toys and games that spark creativity and imagination</p>
          <div class="hero-actions">
            <button class="btn-primary btn-large">Shop Now</button>
            <button class="btn-secondary btn-large">Learn More</button>
          </div>
        </div>
        <div class="hero-image">
          <div class="image-placeholder">
            🧸🎮🤖
          </div>
        </div>
      </div>
    </section>

    <!-- Featured Products -->
    <section class="featured">
      <div class="container">
        <h2 class="section-title">Featured Products</h2>
        <div class="products-grid">
          <div class="product-card">
            <div class="product-image">
              <span class="sale-badge">-20%</span>
              <div class="image-placeholder">🚗</div>
            </div>
            <div class="product-info">
              <h3 class="product-title">Remote Control Car</h3>
              <p class="product-desc">High-speed racing car with lights and sound</p>
              <div class="product-price">
                <span class="price-current">$29.99</span>
                <span class="price-original">$37.99</span>
              </div>
              <button class="btn-primary btn-small">Add to Cart</button>
            </div>
          </div>
          <div class="product-card">
            <div class="product-image">
              <div class="image-placeholder">🧩</div>
            </div>
            <div class="product-info">
              <h3 class="product-title">Educational Puzzle</h3>
              <p class="product-desc">500-piece puzzle with world map design</p>
              <div class="product-price">
                <span class="price-current">$19.99</span>
              </div>
              <button class="btn-primary btn-small">Add to Cart</button>
            </div>
          </div>
          <div class="product-card">
            <div class="product-image">
              <div class="image-placeholder">🤖</div>
            </div>
            <div class="product-info">
              <h3 class="product-title">Robot Building Kit</h3>
              <p class="product-desc">Build your own programmable robot</p>
              <div class="product-price">
                <span class="price-current">$49.99</span>
              </div>
              <button class="btn-primary btn-small">Add to Cart</button>
            </div>
          </div>
          <div class="product-card">
            <div class="product-image">
              <span class="new-badge">NEW</span>
              <div class="image-placeholder">🎨</div>
            </div>
            <div class="product-info">
              <h3 class="product-title">Art Set Deluxe</h3>
              <p class="product-desc">Complete art set with 100+ pieces</p>
              <div class="product-price">
                <span class="price-current">$34.99</span>
              </div>
              <button class="btn-primary btn-small">Add to Cart</button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Categories Section -->
    <section class="categories">
      <div class="container">
        <h2 class="section-title">Shop by Category</h2>
        <div class="categories-grid">
          <div class="category-card">
            <div class="category-icon">🧸</div>
            <h3 class="category-title">Plush Toys</h3>
            <p class="category-desc">Soft and cuddly friends</p>
          </div>
          <div class="category-card">
            <div class="category-icon">🚗</div>
            <h3 class="category-title">Vehicles</h3>
            <p class="category-desc">Cars, trucks, and planes</p>
          </div>
          <div class="category-card">
            <div class="category-icon">🎮</div>
            <h3 class="category-title">Video Games</h3>
            <p class="category-desc">Family-friendly games</p>
          </div>
          <div class="category-card">
            <div class="category-icon">🧩</div>
            <h3 class="category-title">Puzzles</h3>
            <p class="category-desc">Brain-teasing fun</p>
          </div>
          <div class="category-card">
            <div class="category-icon">🎨</div>
            <h3 class="category-title">Arts & Crafts</h3>
            <p class="category-desc">Creative projects</p>
          </div>
          <div class="category-card">
            <div class="category-icon">⚽</div>
            <h3 class="category-title">Outdoor Play</h3>
            <p class="category-desc">Active fun outside</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <div class="footer-content">
          <div class="footer-section">
            <h3 class="footer-title">🎮 Kids Toy Store</h3>
            <p class="footer-desc">Bringing joy and learning through play since 2020</p>
          </div>
          <div class="footer-section">
            <h4 class="footer-heading">Quick Links</h4>
            <a href="#" class="footer-link">About Us</a>
            <a href="#" class="footer-link">Contact</a>
            <a href="#" class="footer-link">Shipping Policy</a>
            <a href="#" class="footer-link">Returns</a>
          </div>
          <div class="footer-section">
            <h4 class="footer-heading">Customer Service</h4>
            <a href="#" class="footer-link">FAQ</a>
            <a href="#" class="footer-link">Track Order</a>
            <a href="#" class="footer-link">Size Guide</a>
            <a href="#" class="footer-link">Privacy Policy</a>
          </div>
          <div class="footer-section">
            <h4 class="footer-heading">Stay Connected</h4>
            <p class="footer-desc">Subscribe for updates and offers</p>
            <div class="newsletter">
              <input type="email" placeholder="Your email" class="newsletter-input">
              <button class="btn-primary">Subscribe</button>
            </div>
          </div>
        </div>
        <div class="footer-bottom">
          <p>© 2024 Kids Toy Store. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
// Component logic will go here
</script>

<style scoped>
/* Reset and base styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

/* Header */
.header {
  background: white;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  position: sticky;
  top: 0;
  z-index: 1000;
}

.header .container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 15px 20px;
}

.logo h1 {
  font-size: 24px;
  color: #4a6cf7;
  margin: 0;
}

.nav {
  display: flex;
  gap: 30px;
}

.nav-link {
  text-decoration: none;
  color: #555;
  font-weight: 500;
  transition: color 0.3s;
}

.nav-link:hover,
.nav-link.active {
  color: #4a6cf7;
}

.header-actions {
  display: flex;
  align-items: center;
  gap: 15px;
}

.icon-btn {
  background: none;
  border: none;
  font-size: 20px;
  cursor: pointer;
  position: relative;
  padding: 8px;
  border-radius: 50%;
  transition: background 0.3s;
}

.icon-btn:hover {
  background: #f5f5f5;
}

.badge {
  position: absolute;
  top: -5px;
  right: -5px;
  background: #ff4757;
  color: white;
  font-size: 12px;
  padding: 2px 6px;
  border-radius: 10px;
}

.btn-primary {
  background: #4a6cf7;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 25px;
  font-weight: 600;
  cursor: pointer;
  transition: background 0.3s;
}

.btn-primary:hover {
  background: #3a5ce5;
}

/* Hero Section */
.hero {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 80px 0;
}

.hero .container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 50px;
}

.hero-content {
  flex: 1;
}

.hero-title {
  font-size: 48px;
  margin-bottom: 20px;
  line-height: 1.2;
}

.hero-subtitle {
  font-size: 18px;
  margin-bottom: 30px;
  opacity: 0.9;
}

.hero-actions {
  display: flex;
  gap: 15px;
}

.btn-large {
  padding: 15px 30px;
  font-size: 16px;
}

.btn-secondary {
  background: transparent;
  color: white;
  border: 2px solid white;
}

.btn-secondary:hover {
  background: rgba(255, 255, 255, 0.1);
}

.hero-image {
  flex: 1;
}

.image-placeholder {
  width: 100%;
  height: 300px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 60px;
}

/* Featured Products */
.featured {
  padding: 80px 0;
}

.section-title {
  text-align: center;
  font-size: 36px;
  margin-bottom: 50px;
  color: #333;
}

.products-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.product-card {
  background: white;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}

.product-card:hover {
  transform: translateY(-5px);
}

.product-image {
  position: relative;
  height: 200px;
  background: #f8f9fa;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 60px;
}

.sale-badge,
.new-badge {
  position: absolute;
  top: 15px;
  right: 15px;
  padding: 5px 10px;
  border-radius: 15px;
  font-size: 12px;
  font-weight: bold;
}

.sale-badge {
  background: #ff4757;
  color: white;
}

.new-badge {
  background: #2ed573;
  color: white;
}

.product-info {
  padding: 20px;
}

.product-title {
  font-size: 18px;
  margin-bottom: 10px;
  color: #333;
}

.product-desc {
  color: #666;
  font-size: 14px;
  margin-bottom: 15px;
}

.product-price {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 15px;
}

.price-current {
  font-size: 20px;
  font-weight: bold;
  color: #4a6cf7;
}

.price-original {
  font-size: 16px;
  color: #999;
  text-decoration: line-through;
}

.btn-small {
  padding: 8px 16px;
  font-size: 14px;
  width: 100%;
}

/* Categories */
.categories {
  background: #f8f9fa;
  padding: 80px 0;
}

.categories-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 25px;
}

.category-card {
  background: white;
  padding: 30px 20px;
  border-radius: 15px;
  text-align: center;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}

.category-card:hover {
  transform: translateY(-5px);
}

.category-icon {
  font-size: 40px;
  margin-bottom: 15px;
}

.category-title {
  font-size: 18px;
  margin-bottom: 10px;
  color: #333;
}

.category-desc {
  color: #666;
  font-size: 14px;
}

/* Footer */
.footer {
  background: #2c3e50;
  color: white;
  padding: 60px 0 30px;
}

.footer-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 40px;
  margin-bottom: 40px;
}

.footer-section {
  display: flex;
  flex-direction: column;
}

.footer-title {
  font-size: 24px;
  margin-bottom: 15px;
  color: #4a6cf7;
}

.footer-desc {
  color: #bdc3c7;
  margin-bottom: 20px;
}

.footer-heading {
  font-size: 18px;
  margin-bottom: 20px;
  color: white;
}

.footer-link {
  color: #bdc3c7;
  text-decoration: none;
  margin-bottom: 10px;
  transition: color 0.3s;
}

.footer-link:hover {
  color: white;
}

.newsletter {
  display: flex;
  gap: 10px;
  margin-top: 15px;
}

.newsletter-input {
  flex: 1;
  padding: 10px 15px;
  border: none;
  border-radius: 25px;
  background: rgba(255, 255, 255, 0.1);
  color: white;
}

.newsletter-input::placeholder {
  color: #bdc3c7;
}

.footer-bottom {
  text-align: center;
  padding-top: 30px;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  color: #bdc3c7;
  font-size: 14px;
}

/* Responsive */
@media (max-width: 768px) {
  .header .container {
    flex-direction: column;
    gap: 15px;
  }
  
  .nav {
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
  }
  
  .hero .container {
    flex-direction: column;
    text-align: center;
  }
  
  .hero-title {
    font-size: 36px;
  }
  
  .hero-actions {
    justify-content: center;
  }
  
  .products-grid {
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  }
  
  .categories-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .categories-grid {
    grid-template-columns: 1fr;
  }
}
</style>