<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Nini Chocolat - Premium artisan chocolate brand. Follow us on TikTok, Instagram, and Facebook for handcrafted chocolate creations, recipes, and sweet treats.">
<meta name="keywords" content="Nini Chocolat, artisan chocolate, premium chocolate, handcrafted chocolate, chocolate maker, chocolatier, gourmet chocolate, luxury chocolate">
<meta name="author" content="Nini Chocolat">
<meta name="robots" content="index, follow">
<meta name="googlebot" content="index, follow">
<meta name="google-site-verification" content="your-google-verification-code-here">

<!-- Open Graph / Facebook Meta Tags -->
<meta property="og:type" content="website">
<meta property="og:url" content="https://www.yourwebsite.com/">
<meta property="og:title" content="Nini Chocolat - Premium Artisan Chocolate">
<meta property="og:description" content="Handcrafted premium artisan chocolate. Follow our sweet journey on social media.">
<meta property="og:image" content="https://www.yourwebsite.com/nini-chocolat-logo.jpg">

<!-- Twitter Meta Tags -->
<meta property="twitter:card" content="summary_large_image">
<meta property="twitter:url" content="https://www.yourwebsite.com/">
<meta property="twitter:title" content="Nini Chocolat - Premium Artisan Chocolate">
<meta property="twitter:description" content="Handcrafted premium artisan chocolate. Follow our sweet journey on social media.">
<meta property="twitter:image" content="https://www.yourwebsite.com/nini-chocolat-logo.jpg">

<title>Nini Chocolat - Premium Artisan Chocolate | Handcrafted Chocolatier</title>
<link rel="canonical" href="https://www.yourwebsite.com/">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=Cormorant+Garamond:wght@300;400;600&display=swap" rel="stylesheet">
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root {
  --chocolate-dark: #3d2817;
  --chocolate-medium: #5c3d2e;
  --chocolate-light: #8b5a3c;
  --gold: #d4af37;
  --cream: #f5e6d3;
  --rose-gold: #b76e79;
}

body {
  background: linear-gradient(145deg, #1a0f08 0%, #2d1810 50%, #1a0f08 100%);
  color: var(--cream);
  font-family: 'Cormorant Garamond', serif;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  padding: 20px;
  position: relative;
  overflow-x: hidden;
}

/* Chocolate texture overlay */
body::before {
  content: '';
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: 
    radial-gradient(circle at 20% 30%, rgba(212, 175, 55, 0.03) 0%, transparent 50%),
    radial-gradient(circle at 80% 70%, rgba(183, 110, 121, 0.04) 0%, transparent 50%),
    repeating-linear-gradient(90deg, transparent, transparent 2px, rgba(212, 175, 55, 0.02) 2px, rgba(212, 175, 55, 0.02) 4px);
  pointer-events: none;
  z-index: 0;
}

/* Animated cocoa particles */
.cocoa-particles {
  position: fixed;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  pointer-events: none;
  z-index: 1;
}

.particle {
  position: absolute;
  background: radial-gradient(circle, rgba(212, 175, 55, 0.4) 0%, rgba(212, 175, 55, 0) 70%);
  border-radius: 50%;
  animation: float-particle 20s infinite ease-in-out;
  opacity: 0.3;
}

@keyframes float-particle {
  0%, 100% {
    transform: translate(0, 0) scale(1);
    opacity: 0.3;
  }
  25% {
    transform: translate(40px, -60px) scale(1.2);
    opacity: 0.5;
  }
  50% {
    transform: translate(-30px, -120px) scale(0.8);
    opacity: 0.2;
  }
  75% {
    transform: translate(50px, -80px) scale(1.1);
    opacity: 0.4;
  }
}

.container {
  position: relative;
  z-index: 2;
  text-align: center;
  background: linear-gradient(135deg, rgba(61, 40, 23, 0.5) 0%, rgba(45, 24, 16, 0.7) 100%);
  backdrop-filter: blur(20px);
  padding: 60px 50px;
  border-radius: 30px;
  width: 100%;
  max-width: 480px;
  box-shadow: 
    0 30px 80px rgba(0, 0, 0, 0.6),
    inset 0 1px 1px rgba(212, 175, 55, 0.2),
    0 0 100px rgba(212, 175, 55, 0.1);
  border: 1px solid rgba(212, 175, 55, 0.15);
  animation: fadeInUp 1s ease-out;
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(40px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Decorative corner elements */
.container::before,
.container::after {
  content: '';
  position: absolute;
  width: 100px;
  height: 100px;
  background: radial-gradient(circle, rgba(212, 175, 55, 0.1) 0%, transparent 70%);
  border-radius: 50%;
}

.container::before {
  top: -50px;
  left: -50px;
}

.container::after {
  bottom: -50px;
  right: -50px;
}

/* Logo section */
.logo-wrapper {
  position: relative;
  margin: 0 auto 40px;
  width: 160px;
  height: 160px;
  animation: logoFloat 1.5s ease-out;
}

@keyframes logoFloat {
  0% {
    opacity: 0;
    transform: scale(0.8) translateY(-20px);
  }
  60% {
    transform: scale(1.05) translateY(0);
  }
  100% {
    opacity: 1;
    transform: scale(1) translateY(0);
  }
}

.logo-glow {
  position: absolute;
  width: 100%;
  height: 100%;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(212, 175, 55, 0.3) 0%, transparent 70%);
  animation: pulseGlow 3s ease-in-out infinite;
}

@keyframes pulseGlow {
  0%, 100% {
    transform: scale(1);
    opacity: 0.5;
  }
  50% {
    transform: scale(1.2);
    opacity: 0.8;
  }
}

.logo {
  position: relative;
  width: 160px;
  height: 160px;
  border-radius: 50%;
  overflow: hidden;
  border: 3px solid var(--gold);
  box-shadow: 
    0 15px 40px rgba(0, 0, 0, 0.4),
    0 0 60px rgba(212, 175, 55, 0.3),
    inset 0 0 20px rgba(212, 175, 55, 0.1);
  transition: transform 0.5s cubic-bezier(0.34, 1.56, 0.64, 1);
}

.logo:hover {
  transform: scale(1.08) rotate(5deg);
  box-shadow: 
    0 20px 60px rgba(0, 0, 0, 0.6),
    0 0 80px rgba(212, 175, 55, 0.5),
    inset 0 0 30px rgba(212, 175, 55, 0.2);
}

.logo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.logo:hover img {
  transform: scale(1.1);
}

/* Brand name with chocolate drip effect */
.brand-name {
  position: relative;
  margin-bottom: 50px;
  animation: fadeIn 1.2s ease-out 0.3s both;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.brand-name h1 {
  font-family: 'Playfair Display', serif;
  font-size: 56px;
  font-weight: 900;
  letter-spacing: 3px;
  background: linear-gradient(135deg, var(--gold) 0%, #f4e4c1 50%, var(--rose-gold) 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-shadow: 0 4px 20px rgba(212, 175, 55, 0.3);
  margin-bottom: 8px;
  position: relative;
  animation: shimmer 3s ease-in-out infinite;
}

@keyframes shimmer {
  0%, 100% {
    filter: brightness(1);
  }
  50% {
    filter: brightness(1.2);
  }
}

/* Chocolate drip decoration */
.drip {
  position: absolute;
  bottom: -15px;
  left: 50%;
  transform: translateX(-50%);
  width: 60px;
  height: 20px;
  background: linear-gradient(180deg, var(--gold) 0%, transparent 100%);
  border-radius: 0 0 50% 50%;
  opacity: 0.6;
}

.brand-name .tagline {
  font-size: 16px;
  letter-spacing: 4px;
  text-transform: uppercase;
  color: var(--gold);
  font-weight: 300;
  opacity: 0.9;
}

/* Social links container */
.social-links {
  display: flex;
  flex-direction: column;
  gap: 20px;
  margin-top: 40px;
}

.social-link {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px 35px;
  border-radius: 16px;
  text-decoration: none;
  color: var(--cream);
  font-size: 19px;
  font-weight: 600;
  letter-spacing: 1px;
  transition: all 0.4s cubic-bezier(0.34, 1.56, 0.64, 1);
  overflow: hidden;
  border: 2px solid transparent;
  animation: slideIn 0.6s ease-out both;
}

.social-link:nth-child(1) { animation-delay: 0.5s; }
.social-link:nth-child(2) { animation-delay: 0.6s; }
.social-link:nth-child(3) { animation-delay: 0.7s; }

@keyframes slideIn {
  from {
    opacity: 0;
    transform: translateX(-50px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

.social-link i {
  margin-right: 15px;
  font-size: 26px;
  transition: all 0.4s cubic-bezier(0.34, 1.56, 0.64, 1);
}

/* TikTok button */
.tiktok {
  background: linear-gradient(135deg, #000000 0%, #1a1a1a 100%);
  border: 2px solid rgba(255, 255, 255, 0.3);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.4);
}

.tiktok:hover {
  transform: translateY(-6px) scale(1.02);
  border-color: #ffffff;
  box-shadow: 
    0 15px 50px rgba(255, 255, 255, 0.2),
    0 0 40px rgba(255, 255, 255, 0.3);
  background: linear-gradient(135deg, #1a1a1a 0%, #2a2a2a 100%);
}

/* Instagram button */
.instagram {
  background: linear-gradient(135deg, #f58529 0%, #dd2a7b 50%, #8134af 100%);
  box-shadow: 0 8px 25px rgba(221, 42, 123, 0.4);
  position: relative;
}

.instagram::before {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, #515bd4 0%, #8134af 50%, #dd2a7b 100%);
  opacity: 0;
  transition: opacity 0.4s ease;
  border-radius: 16px;
}

.instagram:hover {
  transform: translateY(-6px) scale(1.02);
  box-shadow: 
    0 15px 50px rgba(221, 42, 123, 0.5),
    0 0 40px rgba(245, 133, 41, 0.4);
}

.instagram:hover::before {
  opacity: 1;
}

.instagram span {
  position: relative;
  z-index: 1;
}

/* Facebook button */
.facebook {
  background: linear-gradient(135deg, #1877f2 0%, #0d5fc7 100%);
  box-shadow: 0 8px 25px rgba(24, 119, 242, 0.4);
}

.facebook:hover {
  transform: translateY(-6px) scale(1.02);
  box-shadow: 
    0 15px 50px rgba(24, 119, 242, 0.5),
    0 0 40px rgba(13, 95, 199, 0.4);
  background: linear-gradient(135deg, #1d85ff 0%, #1877f2 100%);
}

/* Icon animation on hover */
.social-link:hover i {
  transform: rotate(15deg) scale(1.2);
}

/* Shimmer effect */
.social-link::after {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
  transition: left 0.6s ease;
}

.social-link:hover::after {
  left: 100%;
}

/* Footer */
.footer {
  margin-top: 45px;
  padding-top: 35px;
  border-top: 1px solid rgba(212, 175, 55, 0.2);
  font-size: 14px;
  color: rgba(245, 230, 211, 0.6);
  letter-spacing: 1px;
  animation: fadeIn 1.4s ease-out 0.8s both;
}

.footer i {
  color: var(--rose-gold);
  margin: 0 6px;
  animation: heartBeat 1.5s ease-in-out infinite;
}

@keyframes heartBeat {
  0%, 100% {
    transform: scale(1);
  }
  10%, 30% {
    transform: scale(1.15);
  }
  20%, 40% {
    transform: scale(1);
  }
}

/* Responsive design */
@media (max-width: 520px) {
  .container {
    padding: 45px 30px;
    max-width: 380px;
  }
  
  .brand-name h1 {
    font-size: 44px;
    letter-spacing: 2px;
  }
  
  .brand-name .tagline {
    font-size: 13px;
    letter-spacing: 3px;
  }
  
  .logo-wrapper {
    width: 140px;
    height: 140px;
  }
  
  .logo {
    width: 140px;
    height: 140px;
  }
  
  .social-link {
    padding: 18px 28px;
    font-size: 17px;
  }
  
  .social-link i {
    font-size: 24px;
  }
}

/* Click effect */
.social-link:active {
  transform: translateY(-2px) scale(0.98);
}
</style>
</head>
<body>

<!-- Cocoa particles background -->
<div class="cocoa-particles">
  <div class="particle" style="width: 25px; height: 25px; top: 10%; left: 15%; animation-delay: 0s;"></div>
  <div class="particle" style="width: 18px; height: 18px; top: 70%; left: 85%; animation-delay: 3s;"></div>
  <div class="particle" style="width: 30px; height: 30px; top: 40%; left: 8%; animation-delay: 6s;"></div>
  <div class="particle" style="width: 22px; height: 22px; top: 80%; left: 60%; animation-delay: 2s;"></div>
  <div class="particle" style="width: 20px; height: 20px; top: 20%; left: 75%; animation-delay: 5s;"></div>
  <div class="particle" style="width: 28px; height: 28px; top: 55%; left: 25%; animation-delay: 4s;"></div>
</div>

<div class="container">
  <!-- Logo with glow effect -->
  <div class="logo-wrapper">
    <div class="logo-glow"></div>
    <div class="logo">
      <img src="nini-chocolat-logo.jpg" alt="Nini Chocolat - Premium Artisan Chocolate">
    </div>
  </div>
  
  <!-- Brand name -->
  <div class="brand-name">
    <h1>NINI CHOCOLAT</h1>
    <div class="drip"></div>
    <p class="tagline">Artisan Chocolatier</p>
  </div>
  
  <!-- Social media links -->
  <div class="social-links">
    <a class="social-link tiktok" href="https://www.tiktok.com/@nini.chocolat?_r=1&_t=ZS-93VAu3WE3O5" target="_blank" rel="noopener noreferrer">
      <i class="fab fa-tiktok"></i>
      <span>TikTok</span>
    </a>
    
    <a class="social-link instagram" href="https://www.instagram.com/cho_co_nini?igsh=Mzc3OHhkbmF1ejR3" target="_blank" rel="noopener noreferrer">
      <i class="fab fa-instagram"></i>
      <span>Instagram</span>
    </a>
    
    <a class="social-link facebook" href="https://www.facebook.com/share/1E7E4Ggbtd/?mibextid=wwXIfr" target="_blank" rel="noopener noreferrer">
      <i class="fab fa-facebook-f"></i>
      <span>Facebook</span>
    </a>
  </div>
  
  <!-- Footer -->
  <div class="footer">
    Handcrafted with <i class="fas fa-heart"></i> & cocoa
  </div>
</div>

<script>
// Add ripple effect on click
document.querySelectorAll('.social-link').forEach(link => {
  link.addEventListener('click', function(e) {
    const ripple = document.createElement('span');
    const rect = this.getBoundingClientRect();
    const size = Math.max(rect.width, rect.height);
    const x = e.clientX - rect.left - size / 2;
    const y = e.clientY - rect.top - size / 2;
    
    ripple.style.cssText = `
      position: absolute;
      width: ${size}px;
      height: ${size}px;
      left: ${x}px;
      top: ${y}px;
      background: rgba(255, 255, 255, 0.5);
      border-radius: 50%;
      transform: scale(0);
      animation: ripple-effect 0.6s ease-out;
      pointer-events: none;
    `;
    
    this.appendChild(ripple);
    setTimeout(() => ripple.remove(), 600);
  });
});

// Add CSS animation for ripple
const style = document.createElement('style');
style.textContent = `
  @keyframes ripple-effect {
    to {
      transform: scale(4);
      opacity: 0;
    }
  }
`;
document.head.appendChild(style);

// Parallax effect on mouse move
document.addEventListener('mousemove', (e) => {
  const particles = document.querySelectorAll('.particle');
  const mouseX = e.clientX / window.innerWidth;
  const mouseY = e.clientY / window.innerHeight;
  
  particles.forEach((particle, index) => {
    const speed = (index + 1) * 0.5;
    const x = (mouseX - 0.5) * speed * 20;
    const y = (mouseY - 0.5) * speed * 20;
    particle.style.transform = `translate(${x}px, ${y}px)`;
  });
});
</script>

<!-- Structured Data for Google (JSON-LD) -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "Nini Chocolat",
  "description": "Premium artisan chocolate and handcrafted chocolatier",
  "url": "https://www.yourwebsite.com",
  "logo": "https://www.yourwebsite.com/nini-chocolat-logo.jpg",
  "image": "https://www.yourwebsite.com/nini-chocolat-logo.jpg",
  "sameAs": [
    "https://www.tiktok.com/@nini.chocolat",
    "https://www.instagram.com/cho_co_nini",
    "https://www.facebook.com/share/1E7E4Ggbtd/"
  ],
  "priceRange": "$$",
  "@id": "https://www.yourwebsite.com",
  "address": {
    "@type": "PostalAddress",
    "addressCountry": "DZ"
  }
}
</script>

</body>
</html>
