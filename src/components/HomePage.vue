<template>
  <div class="home-page">
    <div class="body-background">
      <header class="header">
        <div class="header-container">
          <div class="logo-container">
            <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/bf8a5a6dfce551c928014b23f55b90d7f6a0c000?placeholderIfAbsent=true" class="logo" alt="Drip Capital Logo" />
            <button class="mobile-menu-toggle" @click="toggleMobileMenu">
              <span></span>
              <span></span>
              <span></span>
            </button>
          </div>
          <nav class="main-nav" :class="{ 'mobile-menu-open': mobileMenuOpen }">
            <div class="nav-section">
              <div class="nav-group">
                <a href="#" class="nav-link active">
                  For Exporter
                  <span class="active-indicator"></span>
                </a>
                <a href="#" class="nav-link">For Importer</a>
                <a href="#" class="nav-link">For Investor</a>
                <a href="#" class="nav-link">For Partner</a>
              </div>
            </div>
            <div class="nav-section">
              <div class="nav-dropdown">
                <a href="#" class="nav-link dropdown-toggle">
                  Company
                  <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ea6652bbee00c3564e35fa00041053ca2215668d?placeholderIfAbsent=true" class="dropdown-icon" alt="Dropdown" />
                </a>
              </div>
              <div class="nav-dropdown">
                <a href="#" class="nav-link dropdown-toggle">
                  Resources
                  <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/552e38db2a740e952d6f83ef9b9fa7212f0512e7?placeholderIfAbsent=true" class="dropdown-icon" alt="Dropdown" />
                </a>
              </div>
              <div class="nav-dropdown">
                <a href="#" class="nav-link dropdown-toggle">
                  <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/deb4b50db95418b2e6dddfe8ca1ff095f3e18474?placeholderIfAbsent=true" class="country-icon" alt="Country" />
                  India
                  <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/71231a8d886597a88b0425cc267d15465c20c3cb?placeholderIfAbsent=true" class="dropdown-icon" alt="Dropdown" />
                </a>
              </div>
            </div>
            <div class="nav-buttons">
              <a href="#" class="login-button">Login</a>
              <a href="#" class="get-started-button">Get Started</a>
            </div>
          </nav>
        </div>
      </header>
      <div class="main-container">
        <div class="hero-section">
          <div class="hero-content">
            <div class="hero-column-left">
              <div class="hero-text-container">
                <div class="hero-title">Fuel Your Exports with Fast Financing</div>
                <div class="hero-subtitle">
                  Collateral-free finance for your export business – from before you ship to after you ship.
                </div>
                <div class="hero-cta">
                  <div class="cta-text">Get Started</div>
                  <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/2131da8f501fe7447bd4737c09ad266bd85c3a34?placeholderIfAbsent=true" class="cta-arrow" />
                </div>
              </div>
            </div>
            <div class="hero-column-right">
              <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/6a29260776ad959dbe2712325ed03cd4de557a26?placeholderIfAbsent=true" class="hero-image" />
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
      </div>
      <div class="content-section">
        <div class="finance-cards-container">
          <div class="finance-card">
          <div class="finance-card-content">
            <div class="finance-header">
              <div class="finance-title">Post-Shipment Finance</div>
            </div>
            <div class="finance-description">
              Secure immediate funds against your export invoices.
            </div>
            <div class="finance-cta">Get Started</div>
            </div>
          </div>

          <div class="finance-card">
          <div class="finance-card-highlighter">
          <p>Newly Launched</p>
          </div>
          <div class="finance-card-content">
            <div class="finance-header">
            
              <div class="finance-title">Advance Against Purchase Order</div>
            </div>
            <div class="finance-description">
              Up to 60% financing upfront against confirmed buyer purchase orders.
            </div>
              <router-link to="/advance-po" class="finance-cta">Learn More</router-link>
            </div>
          </div>
        </div>
        <div class="advantage-section">
          <div class="section-header">
            <div class="section-title">The Drip Advantage</div>
            <div class="section-underline"></div>
          </div>
          <div class="advantage-content">
            <div class="advantage-column-left">
              <div class="advantage-image-container">
                <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/52cfbb5c1bf5f10647706a2f16375e50874d3627?placeholderIfAbsent=true" class="advantage-image" />
              </div>
            </div>
            <div class="advantage-column-right">
              <div class="advantage-text-container">
                <div class="advantage-item">
                  <div class="advantage-item-title">Collateral free working capital</div>
                  <div class="advantage-item-description">
                    Submit your invoices to receive advances against your account receivables.
                  </div>
                </div>
                <div class="advantage-item">
                  <div class="advantage-item-title">Efficient and Competitive</div>
                  <div class="advantage-item-description">
                    A digital and flexible finance solution with higher credit lines and competitive pricing.
                  </div>
                </div>
                <div class="advantage-item">
                  <div class="advantage-item-title">Increase Liquidity and Grow Sales</div>
                  <div class="advantage-item-description">
                    Expand your business and improve your cash flow to finance your growth.
                  </div>
                </div>
                <div class="advantage-item">
                  <div class="advantage-item-title">Fast, Easy, and Transparent</div>
                  <div class="advantage-item-description">
                    Complete digital onboarding with minimal paperwork, finance invoices via Drip's portal, and receive funds within 24 hours.
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="process-section">
          <div class="section-header">
            <div class="section-title">Simple 4-step Application Process</div>
            <div class="section-underline"></div>
          </div>
          <div class="process-content">
            <div class="process-column-left">
              <div class="process-steps">
                <div class="process-step">
                  <img class="step-image-mobile" src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true"/>

                  <div class="step-title">Apply Online</div>
                  <div class="step-description">
                    Submit basic details about your business on our website.
                  </div>
                </div>
                <div class="process-step">
                                  <img class="step-image-mobile" src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true"/>

                  <div class="step-title">Credit Assessment</div>
                  <div class="step-description">
                    Obtain an offer letter following an automated credit assessment.
                  </div>
                </div>
                <div class="process-step">
                                  <img class="step-image-mobile" src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true"/>

                  <div class="step-title">Submit Invoice</div>
                  <div class="step-description">
                    Securely upload your invoice on our dashboard.
                  </div>
                </div>
                <div class="process-step">
                                  <img class="step-image-mobile" src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true"/>

                  <div class="step-title">24 Hour Disbursements</div>
                  <div class="step-description">
                    Get advance payment directly to your account.
                  </div>
                </div>
              </div>
              <div class="process-cta">Get an Offer</div>
            </div>
            <div class="process-column-right">
              <div class="process-image-container">
                <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ece982c2223d6f0f345306850a53d78bcae01d97?placeholderIfAbsent=true" class="process-image" />
              </div>
            </div>
          </div>
        </div>
        <div class="partners-section">
          <div class="section-header centered">
            <div class="section-title">Our Customers Work with Industry Leaders</div>
            <div class="section-underline centered"></div>
          </div>
          <div class="partners-logos">
            <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/520bf3f592c5410dfcd4de30387d8a488f66ae20?placeholderIfAbsent=true" class="partners-image" />
          </div>
          <div class="section-header centered">
            <div class="section-title">Global Awards and Certifications</div>
            <div class="section-underline centered"></div>
          </div>
          <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/a457289728e6982340fb88467abcc256068721d2?placeholderIfAbsent=true" class="awards-image" />
        </div>
        <div class="news-section">
          <div class="section-header centered">
            <div class="section-title">In the News</div>
            <div class="section-underline centered"></div>
          </div>
          <div class="news-content">
            <div class="news-logos">
              <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/872366e78230d3e91ee426348a7c6e3e7a193c36?placeholderIfAbsent=true" class="news-image" />
            </div>
          </div>
          <div class="testimonials-section">
            <div class="section-header centered">
              <div class="section-title">What Our Clients Say About Us</div>
              <div class="section-underline centered"></div>
            </div>
           <div class="testimonials-container">
    <div class="testimonials-row">
      <div
        class="testimonial-main"
        v-for="(testimonial, index) in testimonials"
        :key="index"
        v-show="currentSlide === index"
      >
        <div class="testimonial-content">
          <div class="testimonial-image-column">
            <div class="testimonial-image-container">
              <img :src="testimonial.image" class="testimonial-image" />
            </div>
          </div>
          <div class="testimonial-text-column">
            <div class="testimonial-text-container">
              <div class="testimonial-quote">{{ testimonial.quote }}</div>
              <div class="testimonial-author">{{ testimonial.author }}</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="testimonial-indicators">
      <span
        v-for="(dot, index) in testimonials"
        :key="'dot-' + index"
        class="indicator"
        :class="{ active: currentSlide === index }"
        @click="goToSlide(index)"
      ></span>
    </div>
  </div>
          </div>
        </div>
      </div>
      <div class="cta-section">
        <div class="cta-container">
          <div class="cta-column-left">
            <div class="cta-text-container">
              <div class="cta-header">
                <div class="cta-title">Get 80% of your receivables financed</div>
                <div class="cta-subtitle">within 24 hours</div>
                <div class="cta-underline"></div>
              </div>
              <div class="cta-description">
                Take control of when you get paid for your export invoices with our one-click collateral- free financing solution. Apply now to start your journey with Drip Capital.
              </div>
            </div>
          </div>
          <div class="cta-column-right">
            <div class="contact-form">
              <div class="form-container">
                <div class="form-title">A few details to get you started</div>
                <div class="form-fields">
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
                    <div class="form-input">What products do you export?</div>
                  </div>
                  <div class="form-field">
                    <div class="form-input">IEC Number</div>
                  </div>
                  <div class="form-field product-selection">
  <div class="product-label">Select Product</div>
  <div class="product-options">
    <label class="radio-option">
      <input
        type="radio"
        name="product"
        value="Post Shipment Finance"
        v-model="selectedProduct"
      />
      <span class="custom-radio">
        <span class="radio-dot" v-if="selectedProduct === 'Post Shipment Finance'"></span>
      </span>
      <span class="radio-label">Post Shipment Finance</span>
    </label>

    <label class="radio-option">
      <input
        type="radio"
        name="product"
        value="Advance against PO"
        v-model="selectedProduct"
      />
      <span class="custom-radio">
        <span class="radio-dot" v-if="selectedProduct === 'Advance against PO'"></span>
      </span>
      <span class="radio-label">Advance against PO</span>
    </label>
  </div>
</div>

                </div>
              </div>
              <div class="submit-button">
                <div class="submit-text">Submit</div>
                <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/9e6ad3ded5faea1d45dc8fc1de31423a99cabf21?placeholderIfAbsent=true" class="submit-arrow" />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="footer">
        <div class="footer-container">
          <div class="footer-top">
            <div class="footer-columns">
              <div class="footer-column">
                <div class="footer-column-content">
                  <div class="footer-heading">Products</div>
                  <div class="footer-link">Invoice Factoring</div>
                </div>
              </div>
              <div class="footer-column">
                <div class="footer-column-content">
                  <div class="footer-heading">Explore</div>
                  <div class="footer-links">
                    <div class="footer-link">Exporters</div>
                    <div class="footer-link">Importers</div>
                    <div class="footer-link">Investors</div>
                    <div class="footer-link">Partner with Us</div>
                    <div class="footer-link">HSN Code Finder</div>
                    <div class="footer-link">Finance Guides</div>
                    <div class="footer-link">Blog</div>
                  </div>
                </div>
              </div>
              <div class="footer-column">
                <div class="footer-column-content">
                  <div class="footer-heading">Help</div>
                  <div class="footer-link">Charges Calculator</div>
                </div>
              </div>
              <div class="footer-column">
                <div class="footer-column-content">
                  <div class="footer-heading">Company</div>
                  <div class="footer-links">
                    <div class="footer-link">About Us</div>
                    <div class="footer-link">Contact</div>
                    <div class="footer-link">Leadership Team</div>
                    <div class="footer-link">Careers</div>
                    <div class="footer-link">Media Room</div>
                    <div class="footer-link">POSH Guidelines</div>
                  </div>
                </div>
              </div>
            </div>
            <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/f3b60a4267c0034ded36ecf35fb0c260d54635c7?placeholderIfAbsent=true" class="footer-logo" />
          </div>
          <div class="footer-middle">
            <div class="footer-location">
              <div class="location-badge">India</div>
              <div class="location-address">
                <span>Drip Capital Services India LLP</span><br />
                <span>1221, 2nd Floor, Building 12 Solitaire Corporate Park,</span><br />
                <span>Guru Hargovindji Rd, Chakala, Andheri East, Mumbai, Maharashtra 400093</span><br />
                <span>+91-9987-779-334</span><br />
                <span class="location-email">cs@dripcapital.com</span>
              </div>
            </div>
            <div class="footer-certifications">
              <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/21e96f2d4a2bf6cc2a0f3dd3af8e8ea06adb0a62?placeholderIfAbsent=true" class="certification-image" />
              <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/efd107716237d7950d3d47965c73545d59b94521?placeholderIfAbsent=true" class="certification-image" />
            </div>
          </div>
          <div class="footer-bottom">
            <div class="footer-copyright">
              <div class="copyright-text">© 2025 Drip Capital Inc. USA</div>
              <div class="footer-legal">
                <div class="legal-link">Terms of Use</div>
                <div class="legal-link">Privacy Policy</div>
              </div>
            </div>
            <div class="language-selector">
              <div class="language-text">India</div>
              <div class="language-arrow"></div>
            </div>
          </div>
          <div class="social-links">
            <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/11e28975778dfc27b76675879a18e3f2fcdeb13f?placeholderIfAbsent=true" class="social-icon" />
            <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/ecb12c15a0576c65e441d26216022d8fd29b3d27?placeholderIfAbsent=true" class="social-icon" />
            <img src="https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/fd4398fa811b984717e848130410fb7e3256ffff?placeholderIfAbsent=true" class="social-icon" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  data() {
    return {
      mobileMenuOpen: false,
      currentSlide: 0,
      testimonials: [
        {
          image: 'https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/7d08dc29478ad7ec79a9d88aa62382179600ab37?placeholderIfAbsent=true',
          quote: "Drip's portal made the entire documents process very easy, eliminating the need to courier documents every time.",
          author: 'Karthikesan V - Chennai based Manufacturer',
        },
        {
          image: 'https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/7d08dc29478ad7ec79a9d88aa62382179600ab37?placeholderIfAbsent=true',
          quote: 'We were able to significantly increase sales to existing customers by shortening our working capital cycle. Thanks to Drip, we have also added new buyers by offering competitive credit terms.',
          author: 'Karthikesan V - Chennai based Manufacturer',
        },
        {
          image: 'https://cdn.builder.io/api/v1/image/assets/68b224e7ec2b4710b4e10d3d9afee309/83d60a49c66eb05f26c037ad63cf61f82abf0670?placeholderIfAbsent=true',
          quote: 'We were able to significantly increase sales to existing customers by shortening our working capital cycle. Thanks to Drip, we have also added new buyers by offering competitive credit terms.',
          author: 'Karthikesan V - Chennai based Manufacturer',
        },
      ],
    };
  },
  methods: {
    toggleMobileMenu() {
      this.mobileMenuOpen = !this.mobileMenuOpen;
    },
    goToSlide(index) {
      this.currentSlide = index;
    },
  },
};
</script>

<style scoped>
.home-page {
  min-height: 720px;
  min-width: 320px;
  overflow: hidden;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
}

.body-background {
  background-color: #ffffff;
  width: 100%;
}

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
  align-items: center;
  justify-content: space-between;
  padding: 0px 20px;
  max-width: 1440px;
  margin: 0 auto;
}

.logo-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo {
  height:55px;
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
  width:100%;
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
  padding: 20px 0;
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

/* Main Container Styles */
.main-container {
  background-color: transparent;
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: stretch;
}

/* Hero Section Styles */
.hero-section {
  background-color: #f3f3f3;
  display: flex;
  width: 100%;
  padding-top: 68px;
  padding-bottom: 6px;
  flex-direction: column;
  align-items: stretch;
}

.hero-content {
  background-color: transparent;
  width: 100%;
  padding: 30px 80px 68px;
  overflow: hidden;
  display: flex;
  gap: 20px;
}

.hero-column-left {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 60%;
}

.hero-text-container {
  background-color: transparent;
  display: flex;
  margin-top: auto;
  margin-right: -620px;
  margin-bottom: auto;
  width: 100%;
  padding: 0 15px 35px;
  flex-direction: column;
  align-self: stretch;
  align-items: start;
  font-size: 16px;
  color: #0a2e57;
  font-weight: 800;
}

.hero-title {
  font-size: 43px;
  line-height: 60px;
}

.hero-subtitle {
  background-color: transparent;
  align-self: stretch;
  margin-top: 31px;
  padding-bottom: 24px;
  font-weight: 400;
  line-height: 1;
}

.hero-cta {
  border-radius: 3px;
  background-color: #27b67c;
  border: 1px solid #27b67c;
  display: flex;
  margin-top: 23px;
  padding: 19px 53px;
  align-items: stretch;
  gap: 5px;
  color: #ffffff;
  text-align: center;
  line-height: 1;
}

.cta-text {
  margin-top: auto;
  margin-bottom: auto;
}

.cta-arrow {
  aspect-ratio: 0.67;
  object-fit: contain;
  object-position: center;
  width: 8px;
  align-self: start;
  margin-top: 2px;
  flex-shrink: 0;
}

.hero-column-right {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 40%;
  margin-left: 20px;
}

.hero-image {
  aspect-ratio: 1.38;
  object-fit: contain;
  object-position: center;
  width: 100%;
  flex-grow: 1;
}

/* Features Card Styles */
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

/* Content Section Styles */
.content-section {
  align-self: center;
  margin-top: 100px;
  width: 100%;
  max-width: 1440px;
}

/* Finance Cards Container */
.finance-cards-container {
  display: flex;
  justify-content: center;
  gap: 30px;
  margin: 0 64px;
}


/* Finance Card Styles */
.finance-card {
  border-radius: 4px;
  background-color: #ffffff;
  box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.075);
  width: 590px;
  max-width: 100%;
  padding-top: 32px;
  padding-bottom: 22px;
  flex-direction: column;  
}
.finance-card:first-child {
  padding-top: 54px;
}

.finance-card-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.finance-card-highlighter{
  background-color: #F2B13C;
  color: white;
  display: flex;
  justify-content: center;
  max-width: 30%;
}

.finance-header {
  background-color: transparent;
  align-self: stretch;
  display: flex;
  align-items: stretch;
  flex-wrap: wrap;
}

.finance-title {
  background-color: transparent;
  padding: 15px 59px 42px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 28px;
  color: #0a2e57;
  font-weight: 800;
  text-align: center;
  line-height: 1;
  flex-grow: 1;
  flex-shrink: 0;
  flex-basis: 0;
  width: fit-content;
}

.finance-icon-container {
  background-color: transparent;
  display: flex;
  padding: 0 55px 37px;
  flex-direction: column;
  align-items: end;
  flex-grow: 1;
  flex-shrink: 0;
  flex-basis: 0;
  width: fit-content;
}

.finance-description {
  color: #2b2b2b;
  font-size: 20px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 400;
  line-height: 1;
  text-align: center;
  margin-top: 24px;
}

.finance-cta {
  border-radius: 3px;
  background-color: #27b67c;
  border: 1px solid #27b67c;
  margin-top: 78px;
  width: 129px;
  max-width: 100%;
  padding: 14px 20px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 16px;
  color: #f8f9fa;
  font-weight: 400;
  text-align: center;
  line-height: 1;
}
.finance-card:nth-child(2) .finance-cta {
  background-color: transparent;
  border: 1px solid #27b67c;
  color: #27b67c;
  text-decoration: none;
}

/* Advantage Section Styles */
.advantage-section {
  background-color: transparent;
  display: flex;
  margin-top: 149px;
  width: 100%;
  padding: 0 64px;
  flex-direction: column;
}

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

.section-underline {
  background-color: #27b67c;
  display: flex;
  width: 200px;
  flex-shrink: 0;
  height: 4px;
}

.advantage-content {
  align-self: end;
  margin-top: 42px;
  width: 1276px;
  max-width: 100%;
  display: flex;
  gap: 20px;
}

.advantage-column-left {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 45%;
}

.advantage-image-container {
  background-color: transparent;
  flex-grow: 1;
  overflow: hidden;
  width: 100%;
}

.advantage-image {
  aspect-ratio: 1.34;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

.advantage-column-right {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 55%;
  margin-left: 20px;
}

.advantage-text-container {
  background-color: transparent;
  margin-top: auto;
  margin-bottom: auto;
  padding: 0 15px 16px;
  align-self: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 400;
  width: 100%;
}

.advantage-item {
  background-color: transparent;
  display: flex;
  padding: 0 80px 10px 0;
  flex-direction: column;
  align-items: start;
  margin-bottom: 15px;
}

.advantage-item-title {
  color: #0a2e57;
  font-size: 28px;
  line-height: 1.2;
}

.advantage-item-description {
  color: #2b2b2b;
  font-size: 16px;
  line-height: 1;
  margin-top: 8px;
}

/* Process Section Styles */
.process-section {
  background-color: transparent;
  margin-top: 149px;
  width: 100%;
  padding: 0 64px;
}

.process-content {
  margin-top: 23px;
  display: flex;
  gap: 20px;
}

.process-column-left {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 50%;
}

.process-steps {
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

.process-step {
  background-color: transparent;
  display: flex;
  padding: 0 36px 10px;
  flex-direction: column;
  align-items: start;
  color: #0a2e57;
  margin-bottom: 24px;
 
}
.process-step:first-child {
  color: #0a2e57;
   border-left: 3px solid #27b67c;
}

/* All other steps turn gray */
.process-step:not(:first-child) {
  color:rgb(149, 146, 146);
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

.process-cta {
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

.process-column-right {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 50%;
  margin-left: 20px;
}

.process-image-container {
  background-color: transparent;
  overflow: hidden;
  width: 100%;
}

.process-image {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

/* Partners Section Styles */
.partners-section {
  background-color: transparent;
  display: flex;
  margin-top: 104px;
  padding: 0 64px 0;
  flex-direction: column;
  align-items: stretch;
}

.section-header.centered {
  align-self: center;
  display: flex;
  width: 654px;
  max-width: 100%;
  padding: 0 2px;
  flex-direction: column;
  align-items: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 32px;
  color: #0a2e57;
  font-weight: 800;
  text-align: center;
  line-height: 1;
}

.section-underline.centered {
  align-self: center;
  margin-top: 18px;
}

.partners-logos {
  background-color: transparent;
  margin: 38px 15px 0;
  padding-bottom: 7px;
  overflow: hidden;
}

.partners-image {
  aspect-ratio: 6.58;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

.awards-image {
  aspect-ratio: 5.05;
  object-fit: contain;
  object-position: center;
  width: 100%;
  margin-top: 22px;
}

/* News Section Styles */
.news-section {
  background-color: transparent;
  display: flex;
  margin-top: 55px;
  flex-direction: column;
  align-items: stretch;
}

.news-content {
  background-color: transparent;
  display: flex;
  padding: 90px 64px;
  flex-direction: column;
  align-items: stretch;
  justify-content: center;
}

.news-logos {
  background-color: transparent;
  overflow: hidden;
}

.news-image {
  aspect-ratio: 8.33;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

/* Testimonials Section Styles */
.testimonials-section {
  background-color: transparent;
  z-index: 10;
  display: flex;
  margin-top: -42px;
  margin-bottom: -10px;
  padding: 0 64px;
  flex-direction: column;
  align-items: stretch;
}

.testimonials-container {
  background-color: transparent;
  margin-top: 38px;
}

.testimonials-row {
  background-color: transparent;
  width: 100%;
  overflow: hidden;
  display: flex;
  justify-content: center;
  gap: 20px;
}

.testimonial-small {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 16%;
}

.testimonial-small-text {
  border-radius: 3px;
  background-color: #f3f3f3;
  box-shadow: 1px 3px 4px rgba(0, 0, 0, 0.15);
  display: flex;
  margin-top: auto;
  margin-bottom: auto;
  flex-direction: column;
  align-self: stretch;
  align-items: start;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 14px;
  color: #2b2b2b;
  font-weight: 400;
  line-height: 24px;
  justify-content: center;
  aspect-ratio: 1;
  width: 100%;
  padding: 21px;
}

.testimonial-main {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 60%;
  margin-left: 20px;
}

.testimonial-content {
  border-radius: 3px;
  background-color: #f3f3f3;
  box-shadow: 1px 3px 4px rgba(0, 0, 0, 0.15);
  padding: 20px 35px;
  width: 100%;
  display: flex; /* Use flex to align children */
  align-items: center; /* Vertically center */
  justify-content: center; /* Horizontally center */
  gap: 20px;
}


.testimonial-image-column {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 26%;
}

.testimonial-image-container {
  background-color: transparent;
  display: flex;
  margin-left: auto;
  margin-right: auto;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  width: 175px;
  height: 175px;
}

.testimonial-image {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 175px;
}

.testimonial-text-column {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 74%;
  margin-left: 20px;
}

.testimonial-text-container {
  background-color: transparent;
  display: flex;
  flex-grow: 1;
  padding: 24px 17px 51px 0;
  flex-direction: column;
  align-items: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-size: 16px;
  font-weight: 400;
  width: 100%;
}

.testimonial-quote {
  color: #2b2b2b;
  line-height: 24px;
}

.testimonial-author {
  color: #0a2e57;
  align-self: start;
  margin-top: 26px;
}

.testimonial-logo-container {
  border-radius: 3px;
  background-color: #f3f3f3;
  box-shadow: 1px 3px 4px rgba(0, 0, 0, 0.15);
  display: flex;
  margin-top: auto;
  margin-bottom: auto;
  padding: 0 41px;
  flex-direction: column;
  align-self: stretch;
  align-items: start;
  justify-content: center;
  aspect-ratio: 1;
  width: 100%;
}

.testimonial-logo {
  aspect-ratio: 1.29;
  object-fit: contain;
  object-position: center;
  width: 157px;
}

.testimonial-indicators {
  display: flex;
  justify-content: center;
  margin-top: 20px;
  gap: 10px;
}

.indicator {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background-color: #ccc;
  cursor: pointer;
}

.indicator.active {
  background-color: #27b67c;
}

/* CTA Section Styles */
.cta-section {
  background-color: #0a2e57;
  display: flex;
  margin-top: 195px;
  width: 100%;
  padding: 129px 70px;
  flex-direction: column;
  align-items: center;
}

.cta-container {
  z-index: 10;
  margin-top: -147px;
  margin-left: 17px;
  margin-bottom: -70px;
  width: 100%;
  max-width: 1376px;
  display: flex;
  gap: 20px;
}

.cta-column-left {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 57%;
}

.cta-text-container {
  background-color: transparent;
  margin-top: auto;
  margin-bottom: auto;
  padding: 0 15px 26px;
  align-self: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  color: #ffffff;
  width: 100%;
}

.cta-header {
  background-color: transparent;
  display: flex;
  width: 557px;
  max-width: 100%;
  flex-direction: column;
  align-items: start;
  font-weight: 800;
}

.cta-title {
  font-size: 32px;
  line-height: 1;
  align-self: stretch;
}

.cta-subtitle {
  font-size: 31px;
  line-height: 1;
  margin-top: 9px;
}

.cta-underline {
  background-color: #27b67c;
  display: flex;
  margin-top: 24px;
  width: 192px;
  flex-shrink: 0;
  height: 4px;
}

.cta-description {
  font-size: 16px;
  font-weight: 400;
  line-height: 24px;
  margin-top: 23px;
}

.cta-column-right {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 43%;
  margin-left: 20px;
}

.contact-form {
  border-radius: 4px;
  background-color: #ffffff;
  box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.15);
  display: flex;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
  padding: 26px 20px;
  flex-direction: column;
  align-items: stretch;
}

.form-container {
  background-color: transparent;
  padding: 17px 19px;
}

.form-title {
  color: #0a2e57;
  font-size: 28px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 800;
  line-height: 1;
  text-align: center;
}

.form-fields {
  background-color: transparent;
  margin-top: 39px;
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

.product-selection {
  background-color: transparent;
  display: flex;
  margin-top: 41px;
  width: 100%;
  padding-left: 1px;
  padding-right: 62px;
  flex-direction: column;
  align-items: start;
}

.product-label {
  color: #0a2e57;
  font-size: 16px;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  font-weight: 400;
  z-index: 10;
  margin-top: -5px;
}

.product-options {
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
  border: 1px solid #00284B;
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
  height: 18px;
}

.radio-dot {
  border-radius: 50%;
  display: flex;
  width: 10px;
  flex-shrink: 0;
  height: 10px;
  background-color: #00284B;
}

.radio-button:not(.selected) .radio-dot {
  display: none;
}

.radio-label {
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
  margin-top: 27px;
  margin-left: 20px;
  padding: 8px 22px;
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

/* Footer Styles */
.footer {
  background-color: #0a2e57;
  display: flex;
  width: 100%;
  padding: 60px 80px;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.footer-container {
  background-color: transparent;
  display: flex;
  width: 100%;
  max-width: 1440px;
  padding: 0 64px 19px;
  flex-direction: column;
  align-items: stretch;
}

.footer-top {
  background-color: transparent;
  border-bottom: 4px solid #27b67c;
  width: 100%;
  padding: 20px 80px 19px;
  display: flex;
}

.footer-columns {
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: normal;
  width: 77%;
  display: flex;
  gap: 20px;
}

.footer-column {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  line-height: normal;
  width: 25%;
}

.footer-column-content {
  background-color: transparent;
  display: flex;
  padding: 0 41px 7px 0;
  flex-direction: column;
  align-items: start;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
  width: 100%;
}

.footer-heading {
  color: #f8f9fa;
  font-size: 18px;
  font-weight: 800;
  line-height: 1;
}

.footer-links {
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

.footer-link {
  color: #ffffff;
  font-size: 13px;
  font-weight: 400;
  line-height: 1;
  margin-top: 10px;
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

.footer-middle {
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

.footer-location {
  background-color: transparent;
  display: flex;
  padding: 8px 0 26px;
  flex-direction: column;
  align-items: stretch;
  font-family: Nunito Sans, -apple-system, Roboto, Helvetica, sans-serif;
}

.location-badge {
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

.location-address {
  color: #000000;
  font-size: 12px;
  font-weight: 400;
  margin-top: 5px;
}

.location-address span {
  font-size: 13px;
  line-height: 19px;
  color: #f8f9fa;
}

.location-email {
  text-decoration: underline;
}

.footer-certifications {
  align-self: start;
  display: flex;
  margin-top: 8px;
  align-items: stretch;
  gap: 16px;
}

.certification-image {
  aspect-ratio: 0.72;
  object-fit: contain;
  object-position: center;
  width: 102px;
  flex-shrink: 0;
  max-width: 100%;
}

.certification-image:last-child {
  aspect-ratio: 0.58;
  width: 46px;
  margin-top: auto;
  margin-bottom: auto;
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

.footer-legal {
  background-color: transparent;
  display: flex;
  margin-top: 15px;
  padding-bottom: 8px;
  align-items: stretch;
  gap: 20px;
  color: #ffffff;
  justify-content: space-between;
}

.legal-link {
  line-height: 1.5;
  align-self: start;
}

.language-selector {
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

.language-arrow {
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

.social-links {
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
/* Hide image inside each step on desktop */
.step-image-mobile {
  display: none;
}

/* Responsive Styles */
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
  .section-underline {
    width: 100%
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
  .nav-link{
    padding: 8px 0;
  }
  .nav-buttons {
    flex-direction: column;
    width: 100%;
  }
  
  .login-button, .get-started-button {
    width: 100%;
    text-align: center;
    padding: 12px 20px;
  }
  
  .main-container {
    max-width: 100%;
  }
  
  .hero-section {
    max-width: 100%;
    padding-top: 0;
  }
  
  .hero-content {
    max-width: 100%;
    padding-left: 20px;
    flex-direction: column;
  }
  
  .hero-column-left, .hero-column-right {
    width: 100%;
    margin-left: 0;
  }
  
  .hero-text-container {
    max-width: 100%;
    align-items: center;
    margin-top: 40px;
  }
  
  .hero-title {
    max-width: 100%;
  }
  
  .hero-subtitle {
    max-width: 100%;
    padding-right: 20px;
  }
  
  .hero-cta {
    padding-left: 20px;
    padding-right: 20px;
  }
  
  .hero-image {
    max-width: 100%;
    margin-top: 30px;
  }
  
  .features-container {
    max-width: 100%;
  }
  
  .feature-item {
    padding-left: 20px;
    padding-right: 20px;
  }
  
  .content-section {
    max-width: 100%;
    margin-top: 40px;
  }
  
  .finance-card {
    max-width: 100%;
    padding-left: 20px;
    padding-right: 20px;
  }
  
  .finance-cta {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 40px;
  }
  .section-header.centered {
  display: flex;
  flex-direction: column;
  align-items: center; /* horizontally center children */
  justify-content: center;
  text-align: center;
  margin-bottom: 24px; /* optional spacing */
}

.section-title {
  font-size: 24px;
  font-weight: bold;
  color: #0a2e57;
}

.section-underline.centered {
  width: 60px;
  height: 4px;
  background-color: #0a2e57;
  margin-top: 8px;
  border-radius: 2px;
}
  
  .advantage-section {
    max-width: 100%;
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 40px;
  }
  
  .advantage-content {
    max-width: 100%;
    margin-top: 40px;
    flex-direction: column;
  }
  
  .advantage-column-left, .advantage-column-right {
    width: 100%;
    margin-left: 0;
  }
  
  .advantage-image-container {
    max-width: 100%;
    margin-top: 40px;
  }
  
  .advantage-image {
    max-width: 100%;
  }
  
  .advantage-text-container {
    max-width: 100%;
    margin-top: 40px;
  }
  
  .advantage-item {
    max-width: 100%;
    padding-right: 5px;
    align-items: center;
  }
  
  .advantage-item-description {
    max-width: 100%;
    text-align: center;
  }
  .advantage-item-title{
    text-align: center;
  }
  .section-title{
    text-align: center;
  }
  
  .process-section {
    max-width: 100%;
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 40px;
  }
  
  .process-content {
    max-width: 100%;
    flex-direction: column;
  }
  
  .process-column-left, .process-column-right {
    width: 100%;
    margin-left: 0;
  }
  
  .process-steps {
    max-width: 100%;
    margin-top: 15px;
    padding-top: 10px;
    padding-bottom: 10px;
  }
  
  .process-step {
    max-width: 100%;
    padding-left: 20px;
    padding-right: 20px;
  }
  
  .process-cta {
    padding-left: 20px;
    padding-right: 20px;
  }
  
  .process-image-container {
    max-width: 100%;
    margin-top: 15px;
  }
  
  .process-image {
    max-width: 100%;
  }
  
  .partners-section {
    max-width: 100%;
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 40px;
  }
  
  .partners-logos {
    max-width: 100%;
    margin-right: 10px;
  }
  
  .partners-image, .awards-image {
    max-width: 100%;
  }
  
  .news-section {
    max-width: 100%;
    margin-top: 40px;
  }
  
  .news-content {
    max-width: 100%;
    padding-left: 20px;
    padding-right: 20px;
  }
  
  .news-image {
    max-width: 100%;
  }
  
  .testimonials-section {
    max-width: 100%;
    margin-bottom: 10px;
    padding-left: 20px;
    padding-right: 20px;
  }
  
  .testimonials-row {
    flex-direction: column;
  }
  
  .testimonial-small, .testimonial-main {
    width: 100%;
    margin-left: 0;
    margin-top: 40px;
  }
  
  .testimonial-content {
    max-width: 100%;
    margin-top: 31px;
    padding-left: 20px;
    padding-right: 20px;
    flex-direction: column;
  }
  
  .testimonial-image-column, .testimonial-text-column {
    width: 100%;
    margin-left: 0;
  }
  
  .testimonial-image-container {
    margin-top: 40px;
  }
  
  .testimonial-text-container {
    max-width: 100%;
    margin-top: 40px;
  }
  
  .testimonial-quote {
    max-width: 100%;
  }
  
  .testimonial-logo-container {
    margin-top: 40px;
    padding-left: 20px;
  }
  
  .testimonial-indicators {
  display: flex;
  justify-content: center;
  margin-top: 20px;
}

.indicator {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background-color: #ccc;
  margin: 0 6px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.indicator.active {
  background-color: #0a2e57;
}
  
.cta-section {
    max-width: 100%;
    padding-left: 5px;
    padding-right: 20px;
    margin-top: 40px;
  }
  
.cta-container {
    max-width: 100%;
    margin-bottom: 10px;
    flex-direction: column;
  }
  
.cta-column-left, .cta-column-right {
    width: 100%;
    margin-left: 0;
  }
  
.cta-text-container {
    max-width: 100%;
    margin-top: 40px;
    padding-right: 20px;
  }
  
.cta-title, .cta-description {
    max-width: 100%;
  }
  
.contact-form {
    max-width: 100%;
    margin-top: 40px;
  }
  
.product-selection {
    padding-right: 20px;
    margin-top: 40px;
  }
  
.submit-button {
    margin-left: 10px;
    padding-left: 20px;
    padding-right: 20px;
    white-space: initial;
  }
  
.footer {
    max-width: 100%;
    padding-left: 5px;
    padding-right: 20px;
  }
  
.footer-container {
    max-width: 100%;
    padding-left: 5px;
    padding-right: 20px;
  }
  
.footer-top {
    max-width: 100%;
    padding-left: 5px;
    padding-right: 20px;
    flex-direction: column;
  }
  
.footer-columns {
    flex-direction: row;
  }
  
.footer-column {
    width: 100%;
    margin-left: 0;
    margin-top: 19px;
  }
  
.footer-column-content {
    padding-right: 16px;
  }
  
  .footer-links {
    padding-right: 20px;
  }
  
  .footer-logo {
    margin-top: 40px;
  }
  
  .footer-middle {
    max-width: 100%;
    padding-left: 20px;
    padding-right: 20px;
  }
  
  .location-badge {
    white-space: initial;
  }
  
  .footer-bottom {
    flex-direction: column;
  }
  
  .language-selector {
    white-space: initial;
  }
  
  .social-links {
    padding-left: 20px;
    padding-right: 20px;
  }
}
@media (max-width: 768px) {
  .hero-content{
    padding: 0;
  }
  .features-card{
    margin-left: 10px;
    margin-right: 10px;
  }
  .feature-label{
    font-size: 12px;
  }
  .feature-value{
    font-size: 16px;
    margin-top: 22px;
  }
  .finance-cards-container{
    display: block;
    margin: 0 20px;
  }

  .finance-card{
    margin-left: 0px;
    padding-left: 0;
    padding-right :0;
    margin-top: 10px;
  }
  .finance-title{
    font-size: 20px;
  }
  .finance-description{
    font-size: 16px;
  }
  .advantage-item-title{
    font-size: 20px;
  }
  .step-title{
    font-size: 20px;
  }
  .process-column-right {
    display: none;
  }
  .finance-card-highlighter{
    max-width: 45%;
  }
  

  .step-image-mobile {
    display: block;
    aspect-ratio: 1;
    -o-object-fit: contain;
    object-fit: contain;
    -o-object-position: center;
    object-position: center;
    width: 100%;
  }
      .process-step{
                align-items: center;

      }
      .process-column-left[data-v-df02a584] {
    display: block 
      }
  .step-description{
    text-align: center;
    font-size: 16px;

  }

  .process-step:first-child {
  color: #0a2e57;
   border-left: none;
}

/* All other steps turn gray */
.process-step:not(:first-child) {
  color:#0a2e57;
   border-left: none;
}
}


</style>