<template>
  <div class="advance-against-po">
    <div class="body-background">
      <div class="container-section">
        <div class="container-background">
          <header class="header">
            <div class="header-container">
              <div class="logo-container">
                <img
                  src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/bf8a5a6dfce551c928014b23f55b90d7f6a0c000?placeholderIfAbsent=true"
                  class="logo" alt="Drip Capital Logo" />
                <button class="mobile-menu-toggle" @click="toggleMobileMenu">
                  <span></span>
                  <span></span>
                  <span></span>
                </button>
              </div>
              <nav class="main-nav" :class="{ 'mobile-menu-open': mobileMenuOpen }">
                <div class="nav-section">
                  <div class="nav-group">
                    <a href="#" class="nav-link">For Exporter</a>
                    <a href="#" class="nav-link active">
                      For Importer
                      <span class="active-indicator"></span>
                    </a>
                    <a href="#" class="nav-link">For Investor</a>
                    <a href="#" class="nav-link">For Partner</a>
                  </div>
                </div>
                <div class="nav-section">
                  <div class="nav-dropdown">
                    <a href="#" class="nav-link dropdown-toggle">
                      Company
                      <img
                        src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ea6652bbee00c3564e35fa00041053ca2215668d?placeholderIfAbsent=true"
                        class="dropdown-icon" alt="Dropdown" />
                    </a>
                    <div class="dropdown-menu">
                      <a href="#" class="dropdown-item">About Us</a>
                      <a href="#" class="dropdown-item">Leadership</a>
                      <a href="#" class="dropdown-item">Careers</a>
                    </div>
                  </div>
                  <div class="nav-dropdown">
                    <a href="#" class="nav-link dropdown-toggle">
                      Resources
                      <img
                        src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/552e38db2a740e952d6f83ef9b9fa7212f0512e7?placeholderIfAbsent=true"
                        class="dropdown-icon" alt="Dropdown" />
                    </a>
                    <div class="dropdown-menu">
                      <a href="#" class="dropdown-item">Blog</a>
                      <a href="#" class="dropdown-item">Case Studies</a>
                      <a href="#" class="dropdown-item">Guides</a>
                    </div>
                  </div>
                  <div class="nav-dropdown">
                    <a href="#" class="nav-link dropdown-toggle">
                      <img
                        src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/deb4b50db95418b2e6dddfe8ca1ff095f3e18474?placeholderIfAbsent=true"
                        class="country-icon" alt="Country" />
                      India
                      <img
                        src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/71231a8d886597a88b0425cc267d15465c20c3cb?placeholderIfAbsent=true"
                        class="dropdown-icon" alt="Dropdown" />
                    </a>
                    <div class="dropdown-menu">
                      <a href="#" class="dropdown-item">USA</a>
                      <a href="#" class="dropdown-item">Mexico</a>
                      <a href="#" class="dropdown-item">UAE</a>
                    </div>
                  </div>
                </div>
                <div class="nav-buttons">
                  <a href="#" class="login-button">Login</a>
                  <a href="#" class="get-started-button">Get Started</a>
                </div>
              </nav>
            </div>
          </header>
          <div class="hero-container">
            <div class="hero-column-left">
              <div class="hero-title">Advance Against Purchase Order (PO)</div>
              <div class="hero-subtitle">Get working capital before you ship.</div>
              <div class="hero-cta-button">
                <div class="cta-text">Get Started</div>
                <img
                  src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/f3893763c9082f2ed621d73f9e5d31b9905c11c4?placeholderIfAbsent=true"
                  class="cta-arrow" />
              </div>
            </div>
            <div class="hero-column-right">
              <img src="@/assets/ChatGPTImage.png" class="hero-image" />
            </div>
          </div>


        </div>
        <div class="features-card">
          <div class="features-container">
            <div class="feature-item">
              <div class="feature-label">Higher Credit Line</div>
              <div class="feature-value">$2.5 million USD</div>
            </div>
            <div class="feature-item">
              <div class="feature-label">Cost-Efficient</div>
              <div class="feature-value">Competitive pricing</div>
            </div>
            <div class="feature-item">
              <div class="feature-label">Simple Access</div>
              <div class="feature-value">No collateral</div>
            </div>
          </div>
        </div>
        <div class="AdvancePo-section">
          <div class="section-header">
            <div class="section-title">Get up to 60% Advance even before you ship.</div>
            <div class="AdvancePo-content">
              <p class="AdvancePo-text">Advance against PO provides you early access to capital. This innovative
                solution is delivered through our trading subsidiary, Voyager Trading</p>
              <p class="AdvancePo-text">
                It lets you access up to 60% of your PO value before you ship, so you can cover production and logistics
                costs without waiting for buyer payments.</p>
            </div>
          </div>
        </div>
        <div class="how-it-works-section">
          <div class="section-header">
            <div class="section-title">How it works</div>
            <div class="section-underline"></div>
          </div>
          <div class="how-it-works-row">

            <div class="how-it-works-column-left">
              <div class="how-it-works-steps">
                <div class="how-it-works-step">
                  <img class="step-image-mobile"
                    src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true" />

                  <div class="step-title">PO issued</div>
                  <div class="step-description">
                    Your buyer places a PO on Voyager, who then places it with you.
                  </div>
                </div>
                <div class="how-it-works-step">
                  <img class="step-image-mobile"
                    src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true" />

                  <div class="step-title">Initial Advance</div>
                  <div class="step-description">
                    Voyager pays you 60% of the PO value upfront.
                  </div>
                </div>
                <div class="how-it-works-step">
                  <img class="step-image-mobile"
                    src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true" />

                  <div class="step-title">Shipment Stage</div>
                  <div class="step-description">
                    Upload the Bill of Lading and receive another 20%.
                  </div>
                </div>
                <div class="how-it-works-step">
                  <img class="step-image-mobile"
                    src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true" />

                  <div class="step-title">Final payment on Due date</div>
                  <div class="step-description">
                    Once the buyer pays Voyager, you get the balance at the time of settlement.
                  </div>
                </div>
                <div class="how-it-works-cta">Get an Offer</div>
              </div>

            </div>
            <div class="how-it-works-column-right">
              <div class="how-it-works-image-container">
                <img
                  src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true"
                  class="how-it-works-image" />
              </div>
            </div>

          </div>
        </div>
        <div class="for-whom-section">
          <div class="section-header">
            <div class="section-title">Who is This For</div>
          </div>
          <div class="for-whom-content">
            <p>Advance Against PO is exclusively for our existing export customers at Drip Capital</p>
            <div class="for-whom-points">
              <ul class="dash-list">
                <li>SME exporters already working with Drip and handling large or frequent international orders</li>
                <li>Sellers who rely on Drip and need advance
                  payments to manage limited working capital</li>
                <li>Exporters looking to accelerate cash flow
                  without offering additional collateral</li>
              </ul>
              <img src="@/assets/Rectangle.png" class="for-whom-image">
            </div>
            <p>If you are already using our export financing solutions, this is the perfect next step to power your
              growth. Not an existing customer yet? You can easily become one by financing just three invoices with us
            </p>
          </div>
        </div>

        <div class="carousel-wrapper">
          <div class="carousel-track" id="carouselTrack">
            
            <div class="carousel-item">
              <div class="carousel-image">
                <img src="@/assets/Rectangle1.png" alt="Image 2" />
              </div>
              <div class="carousel-content">
                <!-- <h3>Carousel Title 2</h3> -->
                <p>We were able to significantly increase sales to existing customers by shortening our working capital cycle. Thanks to Drip, we have also added new buyers by offering competitive credit terms.</p>
              </div>
            </div>

            <div class="carousel-item">
              <div class="carousel-image">
                <img src="@/assets/Image.png" alt="Image 3" />
              </div>
              <div class="carousel-content">
                <h3>Carousel Title 3</h3>
                <p>This is the third carousel item description.</p>
              </div>
            </div>
          </div>

          <!-- Arrows -->
          <button class="carousel-button left" onclick="changeSlide(-1)">&#10094;</button>
          <button class="carousel-button right" onclick="changeSlide(1)">&#10095;</button>

          <!-- Circles -->
          <div class="carousel-dots" id="carouselDots"></div>
        </div>



        <div class="awards-section">
          <div class="awards-container">
            <div class="awards-title">Awards and Certifications</div>
            <div class="awards-logos">
              <img
                src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/d9ba90a8f069eac920c7d41cecd98b1f09f0b61a?placeholderIfAbsent=true"
                class="award-logo" />
              <img
                src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/7c5931362caa0a2be5b5b087b6dfd1e5c552c832?placeholderIfAbsent=true"
                class="award-logo" />
              <img
                src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/309672f08081f508567663dc6a4cc0efe1163001?placeholderIfAbsent=true"
                class="award-logo" />
              <img
                src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/a492f7fb380642d023584d6490493abf3a276a7b?placeholderIfAbsent=true"
                class="award-logo" />
              <img
                src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/bfa60a99c912fddcdd6cf4430d27091374e6ac20?placeholderIfAbsent=true"
                class="award-logo" />
              <img
                src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/2df1af107e5c338cf69a5a140bdf7b2701344fc4?placeholderIfAbsent=true"
                class="award-logo" />
              <img
                src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/bccf10b749ebb6a2f716bf055849a51de2ff241d?placeholderIfAbsent=true"
                class="award-logo" />
              <img
                src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/b9f78e9bcdcefb55e04dd2917a5df2f9e3c19f6f?placeholderIfAbsent=true"
                class="award-logo" />
            </div>
          </div>
        </div>
        <div class="contact-section">
          <div class="contact-container">
            <div class="contact-row">
              <div class="contact-column-left">
                <div class="contact-text-container">
                  <div class="contact-heading">Settle 80% of your payables<br />within 48 hours</div>
                  <div class="contact-description">
                    Strengthen relationships with your suppliers by ensuring early payment with our collateral-free
                    supply chain management services.
                  </div>
                </div>
              </div>
              <div class="contact-column-right">
                <div class="contact-form-card">
                  <div class="form-container">
                    <div class="form-title">A few details to get you started</div>
                    <div class="contact-form">
                      <div class="form-field">
                        <div class="form-input">Full Name</div>
                      </div>
                      <div class="form-field">
                        <div class="form-input">Email</div>
                      </div>
                      <div class="form-field">
                        <div class="form-input">Phone</div>
                      </div>
                      <div class="form-field">
                        <div class="form-input">Company</div>
                      </div>
                      <div class="form-field">
                        <div class="form-input">What product do you import ?</div>
                      </div>
                      <div class="form-field">
                        <div class="form-input">IEC number</div>
                      </div>
                      <div class="form-field-radio">
                        <div class="radio-label">Select Product</div>
                        <div class="radio-options">
                          <div class="radio-option">
                            <div class="radio-button">
                              <div class="radio-dot"></div>
                            </div>
                            <div class="radio-text">Post Shipment Finance</div>
                          </div>
                          <div class="radio-option">
                            <div class="radio-button-empty"></div>
                            <div class="radio-text">Advance against PO</div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="submit-button">
                    <div class="submit-text">Submit</div>
                    <img
                      src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/4df941b36d3ff5cf2e8b33855b36fd1dea15b407?placeholderIfAbsent=true"
                      class="submit-arrow" />
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="footer-container">
            <div class="footer-content">
              <div class="footer-columns">
                <div class="footer-column-main">
                  <div class="footer-grid">
                    <div class="footer-grid-column">
                      <div class="footer-menu">
                        <div class="footer-menu-title">Products</div>
                        <div class="footer-menu-item">Invoice Factoring</div>
                      </div>
                    </div>
                    <div class="footer-grid-column">
                      <div class="footer-menu">
                        <div class="footer-menu-title">Explore</div>
                        <div class="footer-menu-list">
                          <div class="footer-menu-item">Exporters</div>
                          <div class="footer-menu-item">Importers</div>
                          <div class="footer-menu-item">Investors</div>
                          <div class="footer-menu-item">Partner with Us</div>
                          <div class="footer-menu-item">HSN Code Finder</div>
                          <div class="footer-menu-item">Finance Guides</div>
                          <div class="footer-menu-item">Blog</div>
                        </div>
                      </div>
                    </div>
                    <div class="footer-grid-column">
                      <div class="footer-menu">
                        <div class="footer-menu-title">Help</div>
                        <div class="footer-menu-item">Charges Calculator</div>
                      </div>
                    </div>
                    <div class="footer-grid-column">
                      <div class="footer-menu">
                        <div class="footer-menu-title">Company</div>
                        <div class="footer-menu-list">
                          <div class="footer-menu-item">About Us</div>
                          <div class="footer-menu-item">Contact</div>
                          <div class="footer-menu-item">Leadership Team</div>
                          <div class="footer-menu-item">Careers</div>
                          <div class="footer-menu-item">Media Room</div>
                          <div class="footer-menu-item">POSH Guidelines</div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="footer-column-logo">
                  <img
                    src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/2955df0b26d5cb4970150940638244c6c6303cdf?placeholderIfAbsent=true"
                    class="footer-logo" />
                </div>
              </div>
              <div class="footer-info">
                <div class="footer-address">
                  <div class="country-badge">India</div>
                  <div class="address-text">
                    <span class="address-line">Drip Capital Services India LLP</span><br />
                    <span class="address-line">1221, 2nd Floor, Building 12 Solitaire Corporate Park,</span><br />
                    <span class="address-line">Guru Hargovindji Rd, Chakala, Andheri East, Mumbai, Maharashtra
                      400093</span><br />
                    <span class="contact-line">+91-9987-779-334</span><br />
                    <span class="email-line">cs@dripcapital.com</span>
                  </div>
                </div>
                <div class="footer-badges">
                  <img
                    src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/28a31ef81e9247a09ddca3f18241cfe039bad7f0?placeholderIfAbsent=true"
                    class="footer-badge" />
                  <img
                    src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/efd107716237d7950d3d47965c73545d59b94521?placeholderIfAbsent=true"
                    class="footer-badge-small" />
                </div>
              </div>
              <div class="footer-bottom">
                <div class="footer-copyright">
                  <div class="copyright-text">© 2025 Drip Capital Inc. USA</div>
                  <div class="footer-links">
                    <div class="footer-link">Terms of Use</div>
                    <div class="footer-link">Privacy Policy</div>
                  </div>
                </div>
                <div class="country-selector">
                  <div class="selector-text">India</div>
                  <div class="selector-arrow"></div>
                </div>
              </div>
              <div class="social-icons">
                <img
                  src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/11e28975778dfc27b76675879a18e3f2fcdeb13f?placeholderIfAbsent=true"
                  class="social-icon" />
                <img
                  src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ecb12c15a0576c65e441d26216022d8fd29b3d27?placeholderIfAbsent=true"
                  class="social-icon" />
                <img
                  src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/fd4398fa811b984717e848130410fb7e3256ffff?placeholderIfAbsent=true"
                  class="social-icon" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AdvancedPO',
  data() {
    return {
      mobileMenuOpen: false
    }
  },
  methods: {
    toggleMobileMenu() {
      this.mobileMenuOpen = !this.mobileMenuOpen;
    },
    closeMenu() {
      this.mobileMenuOpen = false;
    }
  }
}
</script>

<style scoped>
.advance-against-po {
  min-height: 720px;
  min-width: 320px;
  overflow: hidden;
}

.body-background {
  background-color: #ffffff;
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: stretch;
}

.container-section {
  background-color: transparent;
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: stretch;
}

.container-background {
  background-color: #f3f3f3;
  display: flex;
  width: 100%;
  padding-bottom: 159px;
  flex-direction: column;
  align-items: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
}

/* Header Styles */
.header {
  background-color: #ffffff;
  box-shadow: 0px 4px 17px -11px rgba(0, 0, 0, 1);
  position: sticky;
  top: 0;
  z-index: 100;
  width: 100%;
}

.header-container {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  padding: 15px 20px;
  max-width: 1440px;
  margin: 0 auto;
}

.logo-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
}

.logo {
  height: 40px;
  width: auto;
  object-fit: contain;
}

.mobile-menu-toggle {
  display: none;
  background: none;
  border: none;
  cursor: pointer;
  padding: 10px;
  margin-left: auto;
}

.mobile-menu-toggle span {
  display: block;
  width: 25px;
  height: 3px;
  background-color: #0a2e57;
  margin: 5px 0;
  transition: all 0.3s ease;
}

.main-nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: calc(100% - 120px);
}

.nav-section {
  display: flex;
  align-items: center;
}

.nav-group {
  display: flex;
  gap: 25px;
  margin-right: 40px;
}

.nav-link {
  color: #0a2e57;
  text-decoration: none;
  font-size: 16px;
  font-weight: 400;
  padding: 8px 0;
  position: relative;
  white-space: nowrap;
}

.nav-link.active {
  font-weight: 500;
}

.active-indicator {
  position: absolute;
  bottom: -4px;
  left: 0;
  width: 100%;
  height: 4px;
  background-color: #27b67c;
  border-radius: 8px 9px 0 0;
}

.nav-dropdown {
  position: relative;
  margin-right: 30px;
}

.dropdown-toggle {
  display: flex;
  align-items: center;
  gap: 6px;
}

.dropdown-icon {
  width: 10px;
  height: auto;
}

.country-icon {
  width: 20px;
  height: auto;
  margin-right: 5px;
}

.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  background-color: #ffffff;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  border-radius: 4px;
  padding: 10px 0;
  min-width: 150px;
  display: none;
  z-index: 10;
}

.nav-dropdown:hover .dropdown-menu {
  display: block;
}

.dropdown-item {
  display: block;
  padding: 8px 15px;
  color: #0a2e57;
  text-decoration: none;
  font-size: 14px;
}

.dropdown-item:hover {
  background-color: #f5f5f5;
}

.nav-buttons {
  display: flex;
  gap: 15px;
}

.login-button {
  border-radius: 3px;
  border: 1px solid #27b67c;
  padding: 10px 20px;
  color: #27b67c;
  text-decoration: none;
  font-size: 16px;
  font-weight: 500;
  text-align: center;
}

.get-started-button {
  border-radius: 3px;
  background-color: #27b67c;
  border: 1px solid #27b67c;
  padding: 10px 20px;
  color: #ffffff;
  text-decoration: none;
  font-size: 16px;
  font-weight: 500;
  text-align: center;
}

.hero-container {
  background-color: transparent;
  align-self: center;
  display: flex;
  flex-direction: row;
  /* <- This one is correct */
  margin-top: -19px;
  /* margin-bottom: -32px; */
  width: 85%;
  max-width: 1440px;
  padding: 80px 50px;
  padding-bottom: 32px;
  align-items: start;
  color: #0a2e57;
  font-weight: 800;
}

.hero-column-left {
  line-height: normal;
  width: 70%;
}

.hero-title {
  font-size: 42px;
  line-height: 60px;
}

.hero-subtitle {
  font-size: 20px;
  font-weight: 400;
  line-height: 1;
  margin-top: 37px;
}

.hero-cta-button {
  border-radius: 8px;
  background-color: #27b67c;
  border: 1px solid #27b67c;
  display: inline-flex;
  /* Changed from flex to inline-flex */
  margin-top: 68px;
  padding: 20px 100px;
  align-items: center;
  /* Optional: aligns content nicely */
  gap: 5px;
  font-size: 15px;
  color: #ffffff;
  text-align: center;
  line-height: 24px;
}

.cta-text {
  margin-top: auto;
  margin-bottom: auto;
}

.cta-arrow {
  aspect-ratio: 0.63;
  object-fit: contain;
  object-position: center;
  width: 10px;
  flex-shrink: 0;
}

.hero-column-right {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 55%;
  margin-left: 20px;
  position: absolute;
  bottom: 0;
  right: 0;
  /* z-index: 0; */
}

.hero-image {
  aspect-ratio: 1.38;
  object-fit: contain;
  object-position: center;
  width: 100%;
  flex-grow: 1;
}

.features-card {
  border-radius: 4px;
  background-color: #ffffff;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.075);
  align-self: center;
  z-index: 10;
  display: flex;
  margin-top: -57px;
  margin-left: 29px;
  width: 945px;
  max-width: 100%;
  padding: 16px 1px;
  flex-direction: column;
  align-items: stretch;
  text-align: center;
  justify-content: center;
}

.features-container {
  background-color: transparent;
  display: flex;
  align-items: stretch;
  flex-wrap: wrap;
}

.feature-item {
  background-color: transparent;
  display: flex;
  padding: 0 47px 16px;
  flex-direction: column;
  align-items: stretch;
  flex: 1;
}

.feature-label {
  color: #2b2b2b;
  font-size: 16px;
  font-weight: 400;
  line-height: 1;
  align-self: center;
}

.feature-value {
  color: #0a2e57;
  font-size: 28px;
  font-weight: 800;
  line-height: 1;
  margin-top: 25px;
}

.AdvancePo-section {
  box-shadow: 3px 5px 4px 0px #00000013;
  max-width: 1440px;
  padding: 0px 60px;
  margin-top: 71px;
  align-self: center;
  width: 80%;
}

.AdvancePo-content {
  font-size: 25px;
  font-weight: 400;
  font-family: Nunito Sans;
  line-height: 36px;
}

.AdvancePo-text {
  margin-bottom: 50px;
}


.how-it-works-section {
  background-color: transparent;
  align-self: center;
  margin-top: 71px;
  width: 85%;
  max-width: 1440px;
  padding: 0px 50px;
}

.how-it-works-row {
  gap: 20px;
  display: flex;
  flex-direction: row-reverse;
}

/* .how-it-works-column {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 50%;
}

.how-it-works-column:first-child {
  margin-left: 0px;
}

.how-it-works-column:last-child {
  margin-left: 20px;
}

.how-it-works-content {
  display: flex;
  flex-grow: 1;
  flex-direction: column;
  align-items: stretch;
} */


.section-underline {
  background-color: #27b67c;
  display: flex;
  margin-top: 24px;
  width: 207px;
  flex-shrink: 0;
  height: 4px;
}

/* .how-it-works-image-container {
  background-color: transparent;
  margin-top: 50px;
  overflow: hidden;
}

.how-it-works-image {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

.steps-container {
  display: flex;
  margin-top: auto;
  margin-bottom: auto;
  flex-direction: column;
  align-self: stretch;
  align-items: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 400;
}

.steps-content {
  background-color: transparent;
  padding: 77px 15px;
}

.step-item {
  background-color: transparent;
  display: flex;
  padding: 0 36px 37px;
  flex-direction: column;
  align-items: stretch;
  color: #0a2e57;
}

.step-title {
  font-size: 28px;
  line-height: 1;
  align-self: start;
}

.step-title-alt {
  color: #2b2b2b;
  font-size: 28px;
  line-height: 1.2;
}

.step-description {
  font-size: 20px;
  line-height: 1;
  margin-top: 14px;
}

.get-offer-button {
  border-radius: 3px;
  background-color: #27b67c;
  border: 1px solid #27b67c;
  align-self: start;
  z-index: 10;
  margin-top: -7px;
  margin-left: 15px;
  padding: 9px 23px 21px;
  font-size: 16px;
  color: #ffffff;
  text-align: center;
} */
/* how-it-works Section Styles */

.section-header {
  background-color: transparent;
  max-width: 100%;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 31px;
  color: #0a2e57;
  font-weight: 800;
  line-height: 1;
}

.section-title {
  margin-bottom: 18px;
}

.process-section {
  background-color: transparent;
  margin-top: 149px;
  width: 100%;
  padding: 0 49px;
}

.process-content {
  margin-top: 23px;
  display: flex;
  gap: 20px;
}

.how-it-works-column-left {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 50%;
}

.how-it-works-steps {
  background-color: transparent;
  display: flex;
  flex-grow: 1;
  padding: 90px 15px;
  flex-direction: column;
  align-items: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 400;
  width: 100%;
}

.how-it-works-step {
  background-color: transparent;
  display: flex;
  padding: 0 36px 10px;
  flex-direction: column;
  align-items: start;
  color: #0a2e57;
  margin-bottom: 24px;

}

.how-it-works-step:first-child {
  color: #0a2e57;
  border-left: 3px solid #27b67c;
}

/* All other steps turn gray */
.how-it-works-step:not(:first-child) {
  color: rgb(149, 146, 146);
  border-left: 2px solid rgb(149, 146, 146);
}

.step-title {
  font-size: 28px;
  line-height: 1;
}

.step-description {
  font-size: 16px;
  line-height: 1;
  margin-top: 9px;
}

.how-it-works-cta {
  border-radius: 3px;
  background-color: #27b67c;
  border: 1px solid #27b67c;
  align-self: start;
  margin-top: 16px;
  padding: 9px 23px 21px;
  font-size: 16px;
  color: #ffffff;
  text-align: center;
}

.how-it-works-column-right {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 50%;
  margin-left: 20px;
}

.how-it-works-image-container {
  background-color: transparent;
  overflow: hidden;
  width: 100%;
}

.how-it-works-image {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

/* Hide image inside each step on desktop */
.step-image-mobile {
  display: none;
}

/* .process-image {
  aspect-ratio: 1.37;
  object-fit: contain;
  object-position: center;
  width: 100%;
  background-color: transparent;
  align-self: center;
  z-index: 10;
  margin-top: 47px;
  margin-left: 27px;
  margin-bottom: -484px;
  max-width: 1567px;
} */

/* Who is This For section*/
.for-whom-section {
  background-color: transparent;
  align-self: center;
  margin-top: 71px;
  width: 100%;
  max-width: 1336px;
  padding: 30px 80px;
}

.for-whom-content {
  font-size: 25px;
  font-family: Nunito Sans;
}

.for-whom-points {
  display: flex;
  align-items: center;
  padding: 20px 0;
  justify-content: space-between;
}

.dash-list {
  list-style-type: none;
  padding-left: 0;
  width: 40%;
}

.dash-list li {
  margin-bottom: 36px;
  /* Adds spacing between list items */
}

.dash-list li::before {
  content: "– ";
  /* En dash or hyphen */
  margin-right: 8px;
}

.carousel-wrapper {
  position: relative;
  width: 844px;
  margin: auto;
  overflow: hidden;
}

.carousel-track {
  display: flex;
  transition: transform 0.5s ease;
  width: 100%;
}

.carousel-item {
  min-width: 844px;
  height: 271px;
  background: #f3f3f3;
  border-radius: 3px;
  box-shadow: 1px 3px 4px 0px #00000026;
  display: flex;
  overflow: hidden;
  flex-shrink: 0;
  padding: 0 50px;
  align-items: center;
}

.carousel-image {
  width: 10%;
  height: 70%;
}

.carousel-image img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.carousel-content {
  width: 70%;
  padding: 24px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.carousel-button {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: white;
  border: none;
  font-size: 24px;
  cursor: pointer;
  z-index: 1;
  padding: 8px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
  border-radius: 50%;
}

.carousel-button.left {
  left: -40px;
}

.carousel-button.right {
  right: -40px;
}

.carousel-dots {
  text-align: center;
  margin-top: 12px;
}

.carousel-dot {
  display: inline-block;
  height: 10px;
  width: 10px;
  margin: 0 5px;
  background-color: #bbb;
  border-radius: 50%;
  cursor: pointer;
}

.carousel-dot.active {
  background-color: #333;
}

.awards-section {
  background-color: #ffffff;
  align-self: end;
  display: flex;
  margin-top: 594px;
  width: 1888px;
  max-width: 100%;
  padding: 0 80px;
  flex-direction: column;
  align-items: center;
}

.awards-container {
  background-color: transparent;
  display: flex;
  margin-left: 16px;
  width: 100%;
  max-width: 1440px;
  padding: 0 65px;
  flex-direction: column;
  align-items: stretch;
}

.awards-title {
  color: #0a2e57;
  font-size: 32px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 800;
  line-height: 1;
  align-self: start;
  margin-left: 15px;
}

.awards-logos {
  background-color: transparent;
  display: flex;
  margin-top: 35px;
  padding: 24px 27px;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: space-between;
}

.award-logo {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 116px;
  align-self: stretch;
  flex-shrink: 0;
  max-width: 100%;
}

.award-logo-small {
  aspect-ratio: 1.88;
  object-fit: contain;
  object-position: center;
  width: 105px;
  align-self: stretch;
  margin-top: auto;
  margin-bottom: auto;
  flex-shrink: 0;
  max-width: 100%;
}

.contact-section {
  background-color: #0a2e57;
  z-index: 10;
  display: flex;
  margin-top: 43px;
  margin-bottom: -837px;
  width: 100%;
  padding: 174px 80px 9px;
  flex-direction: column;
  align-items: center;
}

.contact-container {
  width: 100%;
  max-width: 1443px;
}

.contact-row {
  gap: 20px;
  display: flex;
}

.contact-column-left {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 55%;
  margin-left: 0px;
}

.contact-column-right {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 45%;
  margin-left: 20px;
}

.contact-text-container {
  background-color: transparent;
  display: flex;
  margin-top: auto;
  margin-bottom: auto;
  padding: 0 78px 7px 15px;
  flex-direction: column;
  align-self: stretch;
  align-items: start;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  color: #ffffff;
  width: 100%;
}

.contact-heading {
  font-size: 31px;
  font-weight: 800;
  line-height: 43px;
}

.contact-description {
  font-size: 16px;
  font-weight: 400;
  line-height: 22px;
  margin-top: 22px;
}

.contact-form-card {
  border-radius: 24px;
  background-color: #ffffff;
  box-shadow: 0px 6px 12px rgba(10, 46, 87, 0.2);
  border: 1px solid rgba(0, 0, 0, 0.125);
  display: flex;
  margin-top: -168px;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
  padding: 29px 21px;
  flex-direction: column;
  align-items: stretch;
}

.form-container {
  background-color: transparent;
  padding: 20px;
}

.form-title {
  color: #2b2b2b;
  font-size: 31px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 800;
  line-height: 1;
  text-align: center;
}

.contact-form {
  background-color: transparent;
  margin-top: 21px;
  padding-bottom: 15px;
}

.form-field {
  background-color: transparent;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 16px;
  color: #9d9d9d;
  font-weight: 400;
  line-height: 1;
  margin-top: 42px;
}

.form-field:first-child {
  margin-top: 0;
}

.form-input {
  background-color: transparent;
  border-bottom: 1px solid #d2d2d2;
  padding: 6px 0 20px;
  overflow: hidden;
}

.form-field-radio {
  background-color: transparent;
  display: flex;
  margin-top: 35px;
  width: 419px;
  max-width: 100%;
  padding: 0 62px 0 1px;
  flex-direction: column;
  align-items: start;
}

.radio-label {
  color: #0a2e57;
  font-size: 16px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 400;
  z-index: 10;
  margin-top: -5px;
}

.radio-options {
  display: flex;
  margin-top: 20px;
  width: 100%;
  align-items: stretch;
  gap: 18px;
}

.radio-option {
  display: flex;
  align-items: center;
  gap: 8px;
  justify-content: start;
  flex: 1;
}

.radio-button {
  fill: #FFF;
  stroke-width: 1px;
  stroke: #00284B;
  border: 1px solid #00284b;
  align-self: stretch;
  display: flex;
  margin-top: auto;
  margin-bottom: auto;
  padding: 4px;
  flex-direction: column;
  overflow: hidden;
  align-items: stretch;
  justify-content: center;
  width: 18px;
}

.radio-dot {
  border-radius: 50%;
  display: flex;
  width: 10px;
  flex-shrink: 0;
  height: 10px;
  background-color: #00284B;
}

.radio-button-empty {
  fill: #FFF;
  stroke-width: 1px;
  stroke: #00284B;
  border: 1px solid #00284b;
  align-self: stretch;
  display: flex;
  margin-top: auto;
  margin-bottom: auto;
  width: 18px;
  flex-shrink: 0;
  height: 18px;
}

.radio-text {
  color: #0A2E57;
  font-family: Inter, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 14px;
  font-weight: 400;
  align-self: stretch;
  margin-top: auto;
  margin-bottom: auto;
}

.submit-button {
  border-radius: 8px;
  background-color: #27b67c;
  border: 1px solid #27b67c;
  align-self: start;
  display: flex;
  margin-top: 8px;
  margin-left: 20px;
  padding: 20px 29px;
  align-items: stretch;
  gap: 8px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 15px;
  color: #ffffff;
  font-weight: 800;
  white-space: nowrap;
  text-align: center;
  line-height: 2;
}

.submit-text {
  margin-top: auto;
  margin-bottom: auto;
}

.submit-arrow {
  aspect-ratio: 0.63;
  object-fit: contain;
  object-position: center;
  width: 10px;
  flex-shrink: 0;
}

.footer-container {
  background-color: transparent;
  display: flex;
  margin-top: 92px;
  width: 100%;
  padding: 0 64px 19px;
  flex-direction: column;
  align-items: stretch;
}

.footer-content {
  background-color: transparent;
  border-bottom: 4px solid #27b67c;
  width: 100%;
  padding: 0 80px 19px;
}

.footer-columns {
  gap: 20px;
  display: flex;
}

.footer-column-main {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 77%;
  margin-left: 0px;
}

.footer-column-logo {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 23%;
  margin-left: 20px;
}

.footer-grid {
  background-color: transparent;
  flex-grow: 1;
  padding: 10px 10px 0 0;
  width: 100%;
}

.footer-grid {
  gap: 20px;
  display: flex;
}

.footer-grid-column {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 25%;
}

.footer-grid-column:not(:first-child) {
  margin-left: 20px;
}

.footer-menu {
  background-color: transparent;
  display: flex;
  padding: 0 41px 7px 0;
  flex-direction: column;
  align-items: start;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  width: 100%;
}

.footer-menu-title {
  color: #f8f9fa;
  font-size: 18px;
  font-weight: 800;
  line-height: 1;
}

.footer-menu-item {
  color: #ffffff;
  font-size: 13px;
  font-weight: 400;
  line-height: 1;
  margin-top: 17px;
}

.footer-menu-list {
  background-color: transparent;
  display: flex;
  margin-top: 14px;
  padding: 0 41px 8px 0;
  flex-direction: column;
  align-items: start;
  font-size: 13px;
  color: #ffffff;
  font-weight: 400;
  line-height: 1;
}

.footer-menu-list .footer-menu-item {
  margin-top: 7px;
}

.footer-menu-list .footer-menu-item:first-child {
  margin-top: 0;
}

.footer-logo {
  aspect-ratio: 3;
  object-fit: contain;
  object-position: center;
  width: 261px;
  margin-top: auto;
  margin-bottom: auto;
  flex-shrink: 0;
  max-width: 100%;
  align-self: stretch;
}

.footer-info {
  background-color: transparent;
  display: flex;
  margin-top: 10px;
  width: 100%;
  padding: 0 80px 16px;
  align-items: stretch;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: space-between;
}

.footer-address {
  background-color: transparent;
  display: flex;
  padding: 8px 0 26px;
  flex-direction: column;
  align-items: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
}

.country-badge {
  border-radius: 2px;
  background-color: #27b67c;
  align-self: start;
  padding: 4px 16px 10px;
  font-size: 10px;
  color: #ffffff;
  font-weight: 800;
  white-space: nowrap;
  text-align: center;
  line-height: 1;
}

.address-text {
  color: #000000;
  font-size: 12px;
  font-weight: 400;
  margin-top: 5px;
}

.address-line {
  font-size: 13px;
  line-height: 19px;
  color: #f8f9fa;
}

.contact-line {
  font-size: 13px;
  line-height: 19px;
  color: #ffffff;
}

.email-line {
  text-decoration: underline;
  font-size: 13px;
  line-height: 19px;
  color: #ffffff;
}

.footer-badges {
  align-self: start;
  display: flex;
  margin-top: 8px;
  align-items: stretch;
  gap: 16px;
}

.footer-badge {
  aspect-ratio: 0.72;
  object-fit: contain;
  object-position: center;
  width: 102px;
  flex-shrink: 0;
  max-width: 100%;
}

.footer-badge-small {
  aspect-ratio: 0.58;
  object-fit: contain;
  object-position: center;
  width: 46px;
  margin-top: auto;
  margin-bottom: auto;
  flex-shrink: 0;
}

.footer-bottom {
  background-color: transparent;
  align-self: center;
  display: flex;
  width: 1120px;
  max-width: 100%;
  align-items: stretch;
  gap: 20px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 400;
  flex-wrap: wrap;
  justify-content: space-between;
}

.footer-copyright {
  background-color: transparent;
  display: flex;
  flex-direction: column;
  align-items: stretch;
  font-size: 13px;
}

.copyright-text {
  color: #f8f9fa;
  line-height: 1;
  align-self: start;
}

.footer-links {
  background-color: transparent;
  display: flex;
  margin-top: 15px;
  padding-bottom: 8px;
  align-items: stretch;
  gap: 20px;
  color: #ffffff;
  justify-content: space-between;
}

.footer-link {
  line-height: 1.5;
  align-self: start;
}

.country-selector {
  border-radius: 2px;
  background-color: #0a2e57;
  border: 1px solid transparent;
  display: flex;
  margin-top: auto;
  margin-bottom: auto;
  padding: 6px 2px;
  align-items: stretch;
  gap: 4px;
  font-size: 12px;
  color: #ffffff;
  white-space: nowrap;
  text-align: center;
  line-height: 2;
}

.selector-text {
  color: #ffffff;
}

.selector-arrow {
  background-color: transparent;
  border-color: transparent;
  border-right-width: 3px;
  border-bottom-width: 3px;
  border-left-width: 3px;
  align-self: start;
  display: flex;
  width: 6px;
  flex-shrink: 0;
  height: 3px;
}

.social-icons {
  background-color: transparent;
  display: flex;
  margin-top: 16px;
  padding: 0 80px 16px;
  align-items: start;
  gap: 20px;
  flex-wrap: wrap;
}

.social-icon {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 30px;
  flex-shrink: 0;
}

/* Footer Styles */
.footer {
  background-color: #0a2e57;
  color: #ffffff;
  padding: 60px 0 20px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
}

.footer-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

@media (max-width: 991px) {
  .mobile-menu-toggle {
    display: block;
  }

  .logo-container {
    width: 100%;
    display: flex;
    justify-content: space-between;
  }

  .main-nav {
    flex-direction: column;
    align-items: flex-start;
    position: absolute;
    top: 70px;
    left: 0;
    width: 100%;
    background-color: #ffffff;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    padding: 20px;
    display: none;
    z-index: 100;
  }

  .main-nav.mobile-menu-open {
    display: flex;
  }

  .nav-section {
    flex-direction: column;
    align-items: flex-start;
    width: 100%;
    margin-bottom: 20px;
  }

  .nav-group {
    flex-direction: column;
    gap: 15px;
    margin-right: 0;
    width: 100%;
  }

  .nav-dropdown {
    margin-right: 0;
    width: 100%;
    margin-bottom: 15px;
  }

  .dropdown-menu {
    position: static;
    box-shadow: none;
    display: none;
    padding-left: 15px;
  }

  .nav-dropdown:hover .dropdown-menu {
    display: none;
  }

  .dropdown-toggle.active+.dropdown-menu {
    display: block;
  }

  .nav-buttons {
    flex-direction: column;
    width: 100%;
  }

  .login-button,
  .get-started-button {
    width: 100%;
    text-align: center;
    padding: 12px 20px;
  }

  .container-section {
    max-width: 100%;
  }

  .container-background {
    max-width: 100%;
    padding-bottom: 100px;
  }

  .hero-container {
    margin-bottom: 10px;
    padding-right: 20px;
  }

  .hero-title {
    max-width: 100%;
  }

  .hero-cta-button {
    padding: 20px;
    margin-top: 40px;
  }

  .features-container {
    max-width: 100%;
    padding: 0 20px;
  }

  .features-content {
    max-width: 100%;
  }

  .feature-item {
    padding: 0 20px 16px;
  }

  .description-card {
    max-width: 100%;
    padding: 45px 20px;
    margin-top: 40px;
  }

  .description-title {
    max-width: 100%;
  }

  .description-text {
    max-width: 100%;
  }

  .how-it-works-section {
    max-width: 100%;
    margin-top: 40px;
  }

  .how-it-works-row {
    flex-direction: column;
    align-items: stretch;
    gap: 0px;
  }

  .how-it-works-column {
    width: 100%;
    margin-left: 0;
  }

  .how-it-works-content {
    max-width: 100%;
    margin-top: 40px;
  }

  .section-heading {
    padding-right: 20px;
  }

  .how-it-works-image-container {
    max-width: 100%;
    margin-top: 40px;
  }

  .how-it-works-image {
    max-width: 100%;
  }

  .steps-container {
    max-width: 100%;
    margin-top: 40px;
  }

  .step-item {
    max-width: 100%;
    padding: 0 20px 37px;
  }

  .step-description {
    max-width: 100%;
  }

  .get-offer-button {
    margin-left: 10px;
    padding: 9px 20px 21px;
  }

  .process-image {
    max-width: 100%;
    margin-bottom: 10px;
    margin-top: 40px;
  }

  .awards-section {
    max-width: 100%;
    padding: 0 20px;
    margin-top: 40px;
  }

  .awards-container {
    max-width: 100%;
    padding: 0 20px;
  }

  .awards-title {
    margin-left: 10px;
  }

  .awards-logos {
    padding: 24px 20px;
  }

  .contact-section {
    max-width: 100%;
    margin-bottom: 10px;
    padding: 100px 20px 9px;
    margin-top: 40px;
  }

  .contact-container {
    max-width: 100%;
  }

  .contact-row {
    flex-direction: column;
    align-items: stretch;
    gap: 0px;
  }

  .contact-column-left {
    width: 100%;
    margin-left: 0;
  }

  .contact-column-right {
    width: 100%;
    margin-left: 0;
  }

  .contact-text-container {
    max-width: 100%;
    margin-top: 40px;
    padding-right: 20px;
  }

  .contact-description {
    max-width: 100%;
  }

  .contact-form-card {
    max-width: 100%;
    margin-top: -93px;
    padding: 29px 20px;
  }

  .form-container {
    max-width: 100%;
  }

  .form-title {
    max-width: 100%;
    margin-right: 2px;
  }

  .contact-form {
    max-width: 100%;
  }

  .form-field {
    max-width: 100%;
  }

  .form-input {
    max-width: 100%;
    padding-right: 20px;
  }

  .form-field-radio {
    max-width: 100%;
    padding-right: 20px;
  }

  .submit-button {
    margin-left: 10px;
    padding: 20px;
    white-space: initial;
  }

  .footer-container {
    max-width: 100%;
    margin-right: 3px;
    padding: 0 20px 19px;
    margin-top: 40px;
  }

  .footer-content {
    max-width: 100%;
    padding: 0 20px 19px;
  }

  .footer-columns {
    flex-direction: column;
    align-items: stretch;
    gap: 0px;
  }

  .footer-column-main {
    width: 100%;
    margin-left: 0;
  }

  .footer-column-logo {
    width: 100%;
    margin-left: 0;
  }

  .footer-grid {
    max-width: 100%;
  }

  .footer-grid {
    flex-direction: column;
    align-items: stretch;
    gap: 0px;
  }

  .footer-grid-column {
    width: 100%;
    margin-left: 0;
  }

  .footer-menu {
    margin-top: 19px;
  }

  .footer-menu-list {
    padding-right: 20px;
  }

  .footer-logo {
    margin-top: 40px;
  }

  .footer-info {
    max-width: 100%;
    padding: 0 20px 16px;
  }

  .footer-address {
    max-width: 100%;
  }

  .country-badge {
    white-space: initial;
  }

  .address-text {
    max-width: 100%;
  }

  .social-icons {
    padding: 0 20px 16px;
  }
}
</style>