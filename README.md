<!DOCTYPE html>
<html lang="en-US">
<head>
    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=AW-17147516072"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());
      gtag('config', 'AW-17147516072');
    </script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Web Developer West Palm Beach | Palm Beach Websites - Transform Your Business Online</title>
    <meta name="description" content="Stop losing customers to outdated websites. Professional web development that makes you look as good as you are. Based in West Palm Beach, serving businesses everywhere. Call (561) 718-6725.">
    <meta name="keywords" content="web developer west palm beach, website design palm beach county, web development florida, professional websites, business transformation, web design services">
    <link rel="canonical" href="https://zacharyvorsteg.com">
    
    <!-- Preconnect to external resources -->
    <link rel="preconnect" href="https://www.googletagmanager.com">
    <link rel="dns-prefetch" href="https://www.googletagmanager.com">
    
    <!-- Open Graph -->
    <meta property="og:title" content="Palm Beach Websites - Your Website Should Work As Hard As You Do">
    <meta property="og:description" content="Professional websites that give you the confidence to compete. Unlimited revisions until you love it.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://zacharyvorsteg.com">
    <meta property="og:image" content="https://zacharyvorsteg.com/og-image.jpg">
    
    <!-- Twitter Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Palm Beach Websites - Web Developer">
    <meta name="twitter:description" content="Your business deserves a website that opens doors, not closes them.">
    
    <!-- Local Business Schema -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "LocalBusiness",
      "name": "Palm Beach Websites Web Development",
      "url": "https://zacharyvorsteg.com",
      "telephone": "+15617186725",
      "address": {
        "@type": "PostalAddress",
        "addressLocality": "The Acreage",
        "addressRegion": "FL",
        "postalCode": "33470",
        "addressCountry": "US"
      },
      "geo": {
        "@type": "GeoCoordinates",
        "latitude": 26.7586,
        "longitude": -80.2781
      },
      "openingHoursSpecification": {
        "@type": "OpeningHoursSpecification",
        "dayOfWeek": ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday"],
        "opens": "09:00",
        "closes": "18:00"
      },
      "priceRange": "$$$",
      "serviceArea": {
        "@type": "GeoCircle",
        "geoMidpoint": {
          "@type": "GeoCoordinates",
          "latitude": 26.7586,
          "longitude": -80.2781
        },
        "geoRadius": "50"
      }
    }
    </script>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --black: #000000;
            --white: #FFFFFF;
            --gray-100: #F7F7F7;
            --gray-200: #E5E5E5;
            --gray-300: #D4D4D4;
            --gray-400: #A3A3A3;
            --gray-500: #737373;
            --gray-600: #525252;
            --gray-700: #404040;
            --gray-800: #262626;
            --gray-900: #171717;
            --accent: #0066CC;
            --accent-hover: #0052A3;
            --success: #10B981;
            --warning: #F59E0B;
            --error: #EF4444;
            --max-width: 1200px;
            --transition: cubic-bezier(0.4, 0, 0.2, 1);
            --section-padding: 80px;
            --mobile-section-padding: 60px;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'SF Pro Text', 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            font-size: 16px;
            line-height: 1.6;
            color: var(--gray-900);
            background: var(--white);
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            overflow-x: hidden;
        }

        /* Typography - Optimized */
        h1, h2, h3, h4, h5, h6 {
            font-weight: 600;
            letter-spacing: -0.02em;
            line-height: 1.2;
            margin: 0;
        }

        /* Base Elements */
        img {
            max-width: 100%;
            height: auto;
            display: block;
        }

        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
            -webkit-overflow-scrolling: touch;
        }

        /* Selection */
        ::selection {
            background: var(--accent);
            color: var(--white);
        }

        /* Focus States for Accessibility */
        a:focus,
        button:focus,
        input:focus,
        select:focus,
        textarea:focus {
            outline: 2px solid var(--accent);
            outline-offset: 2px;
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 10px;
        }

        ::-webkit-scrollbar-track {
            background: var(--gray-100);
        }

        ::-webkit-scrollbar-thumb {
            background: var(--gray-400);
            border-radius: 5px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: var(--gray-500);
        }

        /* Header */
        header {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: 1000;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border-bottom: 1px solid rgba(0, 0, 0, 0.1);
            transition: all 0.3s var(--transition);
        }

        header.scrolled {
            background: rgba(255, 255, 255, 1);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
        }

        .header-container {
            max-width: var(--max-width);
            margin: 0 auto;
            padding: 0 24px;
            height: 72px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .logo {
            font-size: 18px;
            font-weight: 600;
            letter-spacing: -0.03em;
            color: var(--black);
        }

        nav {
            display: flex;
            gap: 40px;
            align-items: center;
        }

        nav a {
            color: var(--gray-700);
            text-decoration: none;
            font-size: 15px;
            font-weight: 500;
            transition: color 0.2s var(--transition);
            position: relative;
            padding: 5px 0;
        }

        nav a:hover {
            color: var(--black);
        }

        .header-cta {
            background: var(--black);
            color: var(--white);
            padding: 10px 20px;
            border-radius: 6px;
            text-decoration: none;
            font-size: 15px;
            font-weight: 500;
            transition: all 0.2s var(--transition);
            white-space: nowrap;
        }

        .header-cta:hover {
            background: var(--gray-800);
            transform: translateY(-1px);
        }

        /* Mobile Menu Toggle */
        .mobile-menu-toggle {
            display: none;
            background: none;
            border: none;
            cursor: pointer;
            padding: 8px;
            position: relative;
            z-index: 1001;
            width: 44px;
            height: 44px;
            align-items: center;
            justify-content: center;
        }

        .mobile-menu-toggle span {
            display: block;
            width: 24px;
            height: 2px;
            background: var(--black);
            margin: 5px auto;
            transition: all 0.3s var(--transition);
            position: relative;
        }

        .mobile-menu-toggle.active span:nth-child(1) {
            transform: rotate(45deg) translate(5px, 5px);
        }

        .mobile-menu-toggle.active span:nth-child(2) {
            opacity: 0;
        }

        .mobile-menu-toggle.active span:nth-child(3) {
            transform: rotate(-45deg) translate(7px, -6px);
        }

        /* Mobile Menu - FIXED */
        .mobile-menu {
            position: fixed;
            top: 72px;
            left: 0;
            right: 0;
            bottom: 0;
            background: var(--white);
            z-index: 999;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.3s ease, visibility 0.3s ease;
            padding: 24px;
            overflow-y: auto;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            -webkit-overflow-scrolling: touch; /* Smooth scrolling on iOS */
        }

        .mobile-menu.active {
            opacity: 1;
            visibility: visible;
        }

        @media (max-width: 768px) {
            .mobile-menu {
                top: 64px;
                height: calc(100vh - 64px); /* Explicit height */
            }
        }

        .mobile-nav {
            display: flex;
            flex-direction: column;
            gap: 8px;
            opacity: 1;
            visibility: visible;
        }

        .mobile-nav-link {
            font-size: 18px;
            font-weight: 500;
            color: var(--black);
            padding: 16px;
            border-radius: 8px;
            text-decoration: none;
            transition: background-color 0.2s ease, padding-left 0.2s ease;
            background: transparent;
            display: block;
        }

        .mobile-nav-link:hover,
        .mobile-nav-link:active {
            background: var(--gray-100);
            padding-left: 24px;
        }

        .mobile-nav-cta {
            margin-top: 24px;
            text-align: center;
            font-size: 18px;
            font-weight: 600;
            padding: 16px 32px;
            background: var(--black);
            color: var(--white);
            border-radius: 6px;
            text-decoration: none;
            display: block;
            transition: background-color 0.2s ease, transform 0.2s ease;
        }

        .mobile-nav-cta:hover,
        .mobile-nav-cta:active {
            background: var(--gray-800);
            transform: translateY(-1px);
        }

        /* Hero Section */
        .hero {
            padding: 140px 0 var(--section-padding);
            background: var(--white);
            overflow: hidden;
            min-height: 600px;
        }

        .container {
            max-width: var(--max-width);
            margin: 0 auto;
            padding: 0 24px;
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }

        .hero-badge {
            display: inline-block;
            padding: 6px 16px;
            background: var(--gray-100);
            border-radius: 100px;
            font-size: 14px;
            font-weight: 500;
            color: var(--gray-700);
            margin-bottom: 24px;
            opacity: 0;
            animation: fadeInDown 0.6s ease forwards;
        }

        .hero h1 {
            font-size: clamp(36px, 6vw, 72px);
            font-weight: 700;
            line-height: 1.1;
            letter-spacing: -0.04em;
            margin-bottom: 24px;
            color: var(--black);
            opacity: 0;
            animation: fadeInUp 0.8s ease forwards;
            animation-delay: 0.1s;
        }

        .hero-subtitle {
            font-size: clamp(18px, 2.5vw, 24px);
            font-weight: 400;
            color: var(--gray-600);
            margin-bottom: 48px;
            opacity: 0;
            animation: fadeInUp 0.8s ease forwards;
            animation-delay: 0.2s;
            line-height: 1.6;
        }

        .hero-cta {
            display: flex;
            gap: 16px;
            justify-content: center;
            align-items: center;
            opacity: 0;
            animation: fadeInUp 0.8s ease forwards;
            animation-delay: 0.3s;
            flex-wrap: wrap;
        }

        .cta-note {
            width: 100%;
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
            color: var(--gray-600);
            opacity: 0;
            animation: fadeIn 0.8s ease forwards;
            animation-delay: 0.4s;
        }

        .cta-note a {
            color: var(--accent);
            text-decoration: none;
            font-weight: 500;
        }

        .cta-note a:hover {
            text-decoration: underline;
        }

        .hero-trust {
            margin-top: 32px;
            display: flex;
            gap: 24px;
            justify-content: center;
            align-items: center;
            opacity: 0;
            animation: fadeIn 0.8s ease forwards;
            animation-delay: 0.5s;
            flex-wrap: wrap;
        }

        .trust-badge {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 14px;
            color: var(--gray-600);
        }

        .btn {
            padding: 14px 28px;
            border-radius: 6px;
            text-decoration: none;
            font-size: 16px;
            font-weight: 500;
            transition: all 0.2s var(--transition);
            display: inline-block;
            cursor: pointer;
            border: none;
            white-space: nowrap;
            min-height: 44px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }

        .btn-primary {
            background: var(--black);
            color: var(--white);
        }

        .btn-primary:hover {
            background: var(--gray-800);
            transform: translateY(-1px);
        }

        .btn-secondary {
            background: var(--white);
            color: var(--black);
            border: 1px solid var(--gray-300);
        }

        .btn-secondary:hover {
            background: var(--gray-100);
            border-color: var(--gray-400);
        }

        .btn-accent {
            background: var(--accent);
            color: var(--white);
        }

        .btn-accent:hover {
            background: var(--accent-hover);
            transform: translateY(-1px);
        }

        /* Trust Bar */
        .trust-bar {
            background: var(--gray-100);
            padding: 48px 0;
            border-top: 1px solid var(--gray-200);
            border-bottom: 1px solid var(--gray-200);
        }

        .trust-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
            gap: 24px;
            text-align: center;
        }

        .trust-item {
            opacity: 0;
            animation: fadeIn 0.6s ease forwards;
            padding: 10px;
        }

        .trust-item:nth-child(1) { animation-delay: 0.1s; }
        .trust-item:nth-child(2) { animation-delay: 0.2s; }
        .trust-item:nth-child(3) { animation-delay: 0.3s; }
        .trust-item:nth-child(4) { animation-delay: 0.4s; }

        .trust-number {
            font-size: clamp(24px, 3vw, 36px);
            font-weight: 700;
            letter-spacing: -0.03em;
            color: var(--black);
            display: block;
            margin-bottom: 8px;
        }

        .trust-label {
            font-size: 14px;
            color: var(--gray-600);
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }

        /* Pricing Section */
        .pricing-section {
            padding: var(--section-padding) 0;
            background: linear-gradient(to bottom, var(--white) 0%, var(--gray-100) 100%);
            position: relative;
        }

        .pricing-header {
            text-align: center;
            margin-bottom: 60px;
        }

        .pricing-header h2 {
            font-size: clamp(28px, 4vw, 48px);
            font-weight: 700;
            margin-bottom: 16px;
            color: var(--black);
        }

        .pricing-header p {
            font-size: clamp(16px, 2vw, 20px);
            color: var(--gray-600);
            max-width: 600px;
            margin: 0 auto;
        }

        .pricing-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 32px;
            max-width: 1000px;
            margin: 0 auto;
        }

        .pricing-card {
            background: var(--white);
            border-radius: 16px;
            padding: 48px 40px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            position: relative;
            transition: transform 0.3s var(--transition), box-shadow 0.3s var(--transition), opacity 0.6s ease, border-color 0.3s var(--transition);
            border: 2px solid transparent;
            opacity: 0;
            transform: translateY(30px);
        }

        .pricing-card.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .pricing-card:nth-child(1) { transition-delay: 0.1s; }
        .pricing-card:nth-child(2) { transition-delay: 0.2s; }
        .pricing-card:nth-child(3) { transition-delay: 0.3s; }

        .pricing-card.featured {
            border-color: var(--accent);
            transform: scale(1.05);
        }

        .pricing-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 40px rgba(0, 0, 0, 0.12);
        }

        .pricing-card.featured:hover {
            transform: scale(1.05) translateY(-4px);
        }

        .pricing-badge {
            position: absolute;
            top: -14px;
            left: 50%;
            transform: translateX(-50%);
            background: var(--accent);
            color: var(--white);
            padding: 6px 20px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }

        .pricing-title {
            font-size: 24px;
            font-weight: 600;
            margin-bottom: 12px;
            color: var(--black);
        }

        .pricing-price {
            font-size: 48px;
            font-weight: 600;
            color: var(--black);
            margin-bottom: 8px;
            letter-spacing: -0.02em;
        }

        .pricing-price span {
            font-size: 20px;
            font-weight: 400;
            color: var(--gray-600);
        }

        .pricing-description {
            font-size: 16px;
            color: var(--gray-600);
            margin-bottom: 32px;
            line-height: 1.6;
        }

        .pricing-features {
            list-style: none;
            margin-bottom: 40px;
        }

        .pricing-features li {
            padding: 12px 0;
            display: flex;
            align-items: flex-start;
            gap: 12px;
            font-size: 16px;
            color: var(--gray-700);
            border-bottom: 1px solid var(--gray-200);
        }

        .pricing-features li:last-child {
            border-bottom: none;
        }

        .pricing-features .check {
            color: var(--success);
            font-size: 20px;
            flex-shrink: 0;
            margin-top: -2px;
        }

        .pricing-cta {
            width: 100%;
            text-align: center;
            padding: 16px;
            font-size: 18px;
            font-weight: 600;
        }

        .guarantee-section {
            background: var(--gray-900);
            color: var(--white);
            padding: 60px 0;
            margin-top: 80px;
            text-align: center;
        }

        .guarantee-content {
            max-width: 800px;
            margin: 0 auto;
        }

        .guarantee-badge {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            background: rgba(255, 255, 255, 0.1);
            padding: 12px 24px;
            border-radius: 100px;
            margin-bottom: 24px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            font-size: 14px;
        }

        .guarantee-title {
            font-size: clamp(24px, 3vw, 36px);
            font-weight: 700;
            margin-bottom: 16px;
        }

        .guarantee-text {
            font-size: 18px;
            opacity: 0.9;
            line-height: 1.6;
            margin-bottom: 32px;
        }

        /* Social Proof Section */
        .social-proof {
            padding: 60px 0;
            background: var(--white);
            border-top: 1px solid var(--gray-200);
            border-bottom: 1px solid var(--gray-200);
        }

        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 32px;
            margin-top: 40px;
        }

        .testimonial-card {
            background: var(--gray-100);
            padding: 32px;
            border-radius: 12px;
            position: relative;
            opacity: 0;
            transform: translateY(20px);
        }

        .testimonial-card.visible {
            opacity: 1;
            transform: translateY(0);
            transition: all 0.6s var(--transition);
        }

        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: 16px;
            left: 24px;
            font-size: 60px;
            color: var(--accent);
            opacity: 0.2;
            font-family: Georgia, serif;
        }

        .testimonial-text {
            font-size: 16px;
            line-height: 1.6;
            color: var(--gray-700);
            margin-bottom: 24px;
            font-style: italic;
        }

        .testimonial-author {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .author-avatar {
            width: 48px;
            height: 48px;
            background: var(--gray-300);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 600;
            color: var(--gray-600);
        }

        .author-info h4 {
            font-size: 16px;
            font-weight: 600;
            color: var(--black);
            margin-bottom: 2px;
        }

        .author-info p {
            font-size: 14px;
            color: var(--gray-600);
        }

        .rating {
            color: var(--warning);
            margin-bottom: 12px;
        }

        /* Problem Section */
        .problem-section {
            background: var(--black);
            color: var(--white);
            padding: var(--section-padding) 0;
            text-align: center;
        }

        .problem-content h2 {
            font-size: clamp(24px, 4vw, 36px);
            font-weight: 600;
            margin-bottom: 24px;
            letter-spacing: -0.02em;
        }

        .problem-content p {
            font-size: clamp(16px, 2vw, 20px);
            opacity: 0.9;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto 20px;
        }

        .problem-content p strong {
            color: var(--white);
            font-weight: 600;
        }

        /* Discovery Call Form Section */
        .discovery-form-section {
            background: linear-gradient(135deg, var(--gray-900) 0%, var(--black) 100%);
            color: var(--white);
            padding: var(--section-padding) 0;
            position: relative;
            overflow: hidden;
        }

        .discovery-form-section::before {
            content: '';
            position: absolute;
            top: -50%;
            right: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.05) 0%, transparent 70%);
            animation: pulse 20s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }

        .form-container {
            max-width: 600px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }

        .form-header {
            text-align: center;
            margin-bottom: 48px;
        }

        .form-header h2 {
            font-size: clamp(28px, 4vw, 48px);
            margin-bottom: 16px;
            letter-spacing: -0.03em;
        }

        .form-header p {
            font-size: 18px;
            opacity: 0.9;
            line-height: 1.6;
        }

        .discovery-form {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border-radius: 12px;
            padding: 48px;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .form-group {
            margin-bottom: 24px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            opacity: 0.9;
        }

        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 14px 20px;
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 6px;
            color: var(--white);
            font-size: 16px;
            transition: all 0.3s var(--transition);
            min-height: 48px;
        }

        .form-group input::placeholder,
        .form-group textarea::placeholder {
            color: rgba(255, 255, 255, 0.5);
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            outline: none;
            background: rgba(255, 255, 255, 0.15);
            border-color: rgba(255, 255, 255, 0.5);
            box-shadow: 0 0 0 2px rgba(255, 255, 255, 0.1);
        }

        .form-group select {
            cursor: pointer;
        }

        .form-group select option {
            background: var(--gray-900);
            color: var(--white);
        }

        .form-group textarea {
            resize: vertical;
            min-height: 120px;
        }

        .form-submit {
            text-align: center;
            margin-top: 32px;
        }

        .form-submit .btn {
            font-size: 18px;
            padding: 16px 48px;
            width: 100%;
            min-height: 52px;
        }

        .form-note {
            text-align: center;
            margin-top: 16px;
            font-size: 14px;
            opacity: 0.7;
        }

        /* Success Message */
        .form-success {
            background: var(--success);
            color: var(--white);
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 24px;
            display: none;
        }

        .form-success.show {
            display: block;
            animation: fadeInUp 0.5s ease;
        }

        /* Transformation Section */
        .transformation {
            padding: var(--section-padding) 0;
            background: var(--white);
        }

        .section-header {
            max-width: 600px;
            margin: 0 auto 60px;
            text-align: center;
        }

        .section-header h2 {
            font-size: clamp(28px, 4vw, 48px);
            font-weight: 700;
            margin-bottom: 16px;
            letter-spacing: -0.03em;
            color: var(--black);
        }

        .section-header p {
            font-size: clamp(16px, 2vw, 20px);
            color: var(--gray-600);
            line-height: 1.6;
        }

        .transformation-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 32px;
        }

        .transformation-card {
            text-align: center;
            padding: 24px;
            opacity: 0;
            transform: translateY(20px);
        }

        .transformation-card.visible {
            opacity: 1;
            transform: translateY(0);
            transition: all 0.6s var(--transition);
        }

        .transformation-icon {
            font-size: 48px;
            margin-bottom: 24px;
            display: block;
        }

        .transformation-card h3 {
            font-size: 24px;
            font-weight: 600;
            margin-bottom: 16px;
            color: var(--black);
        }

        .transformation-card p {
            font-size: 16px;
            color: var(--gray-600);
            line-height: 1.6;
        }

        /* Services Section */
        .services {
            padding: var(--section-padding) 0;
            background: var(--gray-100);
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 32px;
        }

        .service-card {
            background: var(--white);
            padding: 40px;
            border-radius: 12px;
            transition: all 0.3s var(--transition);
            cursor: pointer;
            opacity: 0;
            transform: translateY(20px);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
        }

        .service-card.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .service-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
        }

        .service-icon {
            font-size: 32px;
            margin-bottom: 24px;
            display: block;
        }

        .service-card h3 {
            font-size: 24px;
            font-weight: 600;
            margin-bottom: 16px;
            color: var(--black);
        }

        .service-card p {
            font-size: 16px;
            color: var(--gray-600);
            line-height: 1.6;
            margin-bottom: 12px;
        }

        /* Portfolio Section */
        .portfolio {
            padding: var(--section-padding) 0;
            background: var(--white);
        }

        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 32px;
            margin-top: 60px;
        }

        .portfolio-item {
            background: var(--gray-100);
            border-radius: 12px;
            overflow: hidden;
            transition: all 0.4s var(--transition);
            opacity: 0;
            transform: scale(0.95);
            cursor: pointer;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
        }

        .portfolio-item.visible {
            opacity: 1;
            transform: scale(1);
        }

        .portfolio-item:hover {
            transform: scale(1.02);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
        }

        .portfolio-image-container {
            position: relative;
            height: 240px;
            background: var(--gray-200);
            overflow: hidden;
            aspect-ratio: 16 / 9;
        }

        .portfolio-content {
            padding: 32px;
        }

        .portfolio-title {
            font-size: 20px;
            font-weight: 600;
            margin-bottom: 8px;
            color: var(--black);
        }

        .portfolio-description {
            font-size: 16px;
            color: var(--gray-600);
            margin-bottom: 24px;
            line-height: 1.6;
        }

        .portfolio-cta {
            color: var(--accent);
            text-decoration: none;
            font-weight: 500;
            font-size: 15px;
            transition: all 0.2s var(--transition);
        }

        .portfolio-cta:hover {
            color: var(--accent-hover);
        }

        /* Process Section */
        .process {
            padding: var(--section-padding) 0;
            background: var(--gray-100);
        }

        .process-timeline {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 32px;
            margin-top: 60px;
        }

        .process-step {
            text-align: center;
            position: relative;
            opacity: 0;
            transform: translateY(20px);
            padding: 20px;
        }

        .process-step.visible {
            opacity: 1;
            transform: translateY(0);
            transition: all 0.6s var(--transition);
        }

        .step-number {
            width: 48px;
            height: 48px;
            background: var(--black);
            color: var(--white);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 24px;
            font-weight: 600;
            font-size: 18px;
        }

        .process-step h3 {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 12px;
            color: var(--black);
        }

        .process-step p {
            font-size: 15px;
            color: var(--gray-600);
            line-height: 1.6;
        }

        /* CTA Section */
        .cta-section {
            padding: var(--section-padding) 0;
            background: var(--black);
            color: var(--white);
            text-align: center;
        }

        .cta-content h2 {
            font-size: clamp(28px, 4vw, 48px);
            font-weight: 700;
            margin-bottom: 16px;
            letter-spacing: -0.03em;
        }

        .cta-content p {
            font-size: clamp(16px, 2vw, 20px);
            opacity: 0.8;
            margin-bottom: 48px;
        }

        .phone-number {
            font-size: clamp(20px, 3vw, 36px);
            font-weight: 700;
            letter-spacing: -0.02em;
            margin-bottom: 48px;
            display: block;
        }

        .btn-white {
            background: var(--white);
            color: var(--black);
            padding: 16px 32px;
            border-radius: 6px;
            text-decoration: none;
            font-size: 16px;
            font-weight: 500;
            transition: all 0.2s var(--transition);
            display: inline-block;
            min-height: 52px;
            display: inline-flex;
            align-items: center;
        }

        .btn-white:hover {
            background: var(--gray-100);
            transform: translateY(-1px);
        }

        /* Footer */
        footer {
            background: var(--gray-100);
            padding: 48px 0;
            border-top: 1px solid var(--gray-200);
        }

        .footer-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 24px;
        }

        .footer-text {
            color: var(--gray-600);
            font-size: 14px;
        }

        .footer-contact {
            display: flex;
            gap: 24px;
            align-items: center;
            flex-wrap: wrap;
        }

        .footer-contact a {
            color: var(--gray-700);
            text-decoration: none;
            font-size: 14px;
            font-weight: 500;
            transition: color 0.2s var(--transition);
            padding: 5px 0;
        }

        .footer-contact a:hover {
            color: var(--black);
        }

        /* Floating Action Container */
        .floating-actions {
            position: fixed;
            bottom: 30px;
            right: 30px;
            display: flex;
            flex-direction: column;
            gap: 16px;
            align-items: flex-end;
            z-index: 990;
        }

        /* Floating Book Button */
        .floating-book-btn {
            background: var(--black);
            color: var(--white);
            padding: 12px 24px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            font-size: 14px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
            transition: all 0.3s var(--transition);
            animation: floatIn 0.6s ease-out 0.8s both;
            display: flex;
            align-items: center;
            gap: 8px;
            white-space: nowrap;
        }

        .floating-book-btn:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 30px rgba(0, 0, 0, 0.4);
            background: var(--gray-800);
        }

        /* Floating Call Button */
        .floating-call-btn {
            width: 60px;
            height: 60px;
            background: var(--accent);
            color: var(--white);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            box-shadow: 0 4px 20px rgba(0, 102, 204, 0.3);
            transition: all 0.3s var(--transition);
            animation: floatIn 0.6s ease-out 1s both;
        }

        .floating-call-btn::before {
            content: "Quick Call";
            position: absolute;
            right: 70px;
            background: var(--accent);
            color: var(--white);
            padding: 8px 16px;
            border-radius: 6px;
            font-size: 14px;
            font-weight: 500;
            white-space: nowrap;
            opacity: 0;
            pointer-events: none;
            transition: all 0.3s var(--transition);
            transform: translateX(10px);
            box-shadow: 0 2px 10px rgba(0, 102, 204, 0.3);
        }

        .floating-call-btn:hover::before {
            opacity: 1;
            transform: translateX(0);
        }

        .floating-call-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 30px rgba(0, 102, 204, 0.5);
        }

        .floating-call-btn svg {
            width: 24px;
            height: 24px;
            fill: var(--white);
        }

        /* Animations - Optimized */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translate3d(0, 20px, 0);
            }
            to {
                opacity: 1;
                transform: translate3d(0, 0, 0);
            }
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translate3d(0, -20px, 0);
            }
            to {
                opacity: 1;
                transform: translate3d(0, 0, 0);
            }
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes floatIn {
            0% {
                opacity: 0;
                transform: scale(0.5) translate3d(0, 20px, 0);
            }
            100% {
                opacity: 1;
                transform: scale(1) translate3d(0, 0, 0);
            }
        }

        /* Responsive Tablet */
        @media (max-width: 1024px) {
            :root {
                --section-padding: 60px;
            }

            .pricing-card.featured {
                transform: scale(1);
            }

            .hero h1 {
                font-size: clamp(40px, 5vw, 56px);
            }
        }

        /* Responsive Mobile */
        @media (max-width: 768px) {
            :root {
                --section-padding: 60px;
                --mobile-section-padding: 40px;
            }

            /* Hide desktop navigation */
            .header-container nav {
                display: none !important;
            }

            .header-cta {
                display: none !important;
            }

            /* Show mobile menu toggle */
            .mobile-menu-toggle {
                display: flex;
            }

            .header-container {
                height: 64px;
                padding: 0 16px;
            }

            /* Mobile Menu Position */
            .mobile-menu {
                top: 64px;
            }

            .hero {
                padding: 100px 0 var(--mobile-section-padding);
                min-height: auto;
            }

            .hero h1 {
                font-size: clamp(32px, 8vw, 40px);
                margin-bottom: 20px;
            }

            .hero-subtitle {
                margin-bottom: 32px;
            }

            .hero-cta {
                width: 100%;
            }

            .hero-cta .btn {
                width: 100%;
                text-align: center;
            }

            .hero-trust {
                gap: 16px;
            }

            .trust-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: 16px;
            }

            .section-header {
                margin-bottom: 40px;
            }

            .discovery-form {
                padding: 32px 20px;
            }

            .problem-section,
            .transformation,
            .services,
            .portfolio,
            .process,
            .cta-section,
            .discovery-form-section,
            .pricing-section,
            .social-proof {
                padding: var(--mobile-section-padding) 0;
            }

            .footer-content {
                text-align: center;
                justify-content: center;
            }

            .footer-contact {
                justify-content: center;
            }

            /* Pricing cards mobile */
            .pricing-cards {
                gap: 24px;
            }

            .pricing-card {
                padding: 32px 24px;
            }

            .pricing-card.featured {
                transform: scale(1);
            }

            .pricing-card.featured:hover {
                transform: translateY(-4px);
            }

            .pricing-price {
                font-size: 36px;
            }

            .guarantee-section {
                padding: 40px 0;
                margin-top: 60px;
            }

            /* Mobile floating buttons */
            .floating-actions {
                bottom: 20px;
                right: 20px;
                gap: 12px;
            }

            .floating-call-btn {
                width: 56px;
                height: 56px;
            }
            
            .floating-book-btn {
                padding: 10px 20px;
                font-size: 13px;
            }

            .floating-call-btn::before {
                display: none;
            }

            /* Testimonials mobile */
            .testimonials-grid {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 16px;
            }

            .hero h1 {
                font-size: 32px;
            }

            .btn {
                font-size: 15px;
                padding: 12px 24px;
            }

            .transformation-grid,
            .services-grid,
            .portfolio-grid,
            .process-timeline {
                grid-template-columns: 1fr;
            }

            .service-card {
                padding: 32px 24px;
            }

            .pricing-cards {
                grid-template-columns: 1fr;
            }

            .pricing-card {
                padding: 32px 20px;
            }

            .guarantee-badge {
                font-size: 12px;
                padding: 10px 20px;
            }

            .trust-grid {
                grid-template-columns: 1fr;
                text-align: center;
            }

            /* Mobile menu specific */
            .mobile-nav-link {
                font-size: 16px;
                padding: 14px;
            }

            .mobile-nav-cta {
                font-size: 16px;
                padding: 14px 24px;
            }
        }

        /* Fade-in-up utility class */
        .fade-in-up {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.6s var(--transition), transform 0.6s var(--transition);
        }

        .fade-in-up.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Body menu open styles handled by JavaScript for better scroll position preservation */
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="header-container">
            <div class="logo">Palm Beach Websites</div>
            <nav>
                <a href="#pricing">Pricing</a>
                <a href="#portfolio">Our Work</a>
                <a href="#process">How It Works</a>
                <a href="#book-discovery">Let's Talk</a>
            </nav>
            <a href="tel:5617186725" class="header-cta">Call (561) 718-6725</a>
            <button class="mobile-menu-toggle" aria-label="Menu">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </div>
    </header>

    <!-- Mobile Menu -->
    <div class="mobile-menu" id="mobileMenu">
        <nav class="mobile-nav">
            <a href="#pricing" class="mobile-nav-link">Pricing</a>
            <a href="#portfolio" class="mobile-nav-link">Our Work</a>
            <a href="#process" class="mobile-nav-link">How It Works</a>
            <a href="#book-discovery" class="mobile-nav-link">Book Discovery Call</a>
            <a href="tel:5617186725" class="mobile-nav-cta">Call (561) 718-6725</a>
        </nav>
    </div>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <span class="hero-badge">Based in West Palm Beach • Working With Businesses Everywhere</span>
                <h1>Your Website Should Work As Hard As You Do</h1>
                <p class="hero-subtitle">Whether you need to fix an outdated site or build your first one, we create professional websites that give you the confidence to compete—and win.</p>
                <div class="hero-cta">
                    <a href="#book-discovery" class="btn btn-primary">Book Your Free Consultation</a>
                    <a href="#pricing" class="btn btn-secondary">See Simple Pricing</a>
                </div>
                <p class="cta-note">No tech talk. No confusing jargon. <a href="#process">Just results you can see →</a></p>
                <div class="hero-trust">
                    <span class="trust-badge">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="var(--success)" stroke-width="2">
                            <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/>
                            <polyline points="22 4 12 14.01 9 11.01"/>
                        </svg>
                        100% Money-Back Guarantee
                    </span>
                    <span class="trust-badge">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="var(--success)" stroke-width="2">
                            <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/>
                            <polyline points="22 4 12 14.01 9 11.01"/>
                        </svg>
                        Unlimited Revisions
                    </span>
                </div>
            </div>
        </div>
    </section>

    <!-- Trust Bar -->
    <section class="trust-bar">
        <div class="container">
            <div class="trust-grid">
                <div class="trust-item">
                    <span class="trust-number">Real</span>
                    <span class="trust-label">Human Support</span>
                </div>
                <div class="trust-item">
                    <span class="trust-number">Clear</span>
                    <span class="trust-label">Upfront Pricing</span>
                </div>
                <div class="trust-item">
                    <span class="trust-number">∞</span>
                    <span class="trust-label">Revisions</span>
                </div>
                <div class="trust-item">
                    <span class="trust-number">Direct</span>
                    <span class="trust-label">Communication</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section class="pricing-section" id="pricing">
        <div class="container">
            <div class="pricing-header">
                <h2>Simple, Transparent Pricing</h2>
                <p>No hidden fees. No surprises. Just honest pricing for quality work.</p>
            </div>
            
            <div class="pricing-cards">
                <div class="pricing-card fade-in-up">
                    <h3 class="pricing-title">Single Page Website</h3>
                    <div class="pricing-price">$350</div>
                    <p class="pricing-description">Perfect for getting started with a professional online presence</p>
                    
                    <ul class="pricing-features">
                        <li>
                            <span class="check">✓</span>
                            <span>Beautiful, modern single-page design</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Mobile-responsive on all devices</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>SEO-optimized for search engines</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Contact form integration</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Fast loading speed (under 3 seconds)</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span><strong>Unlimited revisions</strong> until you love it</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>30-day post-launch support</span>
                        </li>
                    </ul>
                    
                    <a href="#book-discovery" class="btn btn-primary pricing-cta">Start Your Website Today</a>
                </div>
                
                <div class="pricing-card featured fade-in-up">
                    <span class="pricing-badge">Most Popular</span>
                    <h3 class="pricing-title">Multi-Page Website</h3>
                    <div class="pricing-price">$1,250<span> starting</span></div>
                    <p class="pricing-description">Full website for businesses ready to compete professionally</p>
                    
                    <ul class="pricing-features">
                        <li>
                            <span class="check">✓</span>
                            <span>Up to 5 professionally designed pages</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Custom design matched to your brand</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Advanced SEO implementation</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Google Analytics & tracking setup</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Blog or news section (optional)</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span><strong>Unlimited revisions</strong> until perfect</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>60-day post-launch support</span>
                        </li>
                    </ul>
                    
                    <a href="#book-discovery" class="btn btn-accent pricing-cta">Book Your Free Consultation</a>
                </div>
                
                <div class="pricing-card fade-in-up">
                    <h3 class="pricing-title">Custom Solution</h3>
                    <div class="pricing-price">Let's Talk</div>
                    <p class="pricing-description">For unique requirements or larger projects</p>
                    
                    <ul class="pricing-features">
                        <li>
                            <span class="check">✓</span>
                            <span>E-commerce functionality</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Custom web applications</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Database integration</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>API connections</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Advanced functionality</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span><strong>Unlimited revisions</strong> included</span>
                        </li>
                        <li>
                            <span class="check">✓</span>
                            <span>Extended support options</span>
                        </li>
                    </ul>
                    
                    <a href="#book-discovery" class="btn btn-primary pricing-cta">Discuss Your Project</a>
                </div>
            </div>
            
            <div class="guarantee-section">
                <div class="container">
                    <div class="guarantee-content">
                        <div class="guarantee-badge">
                            <span>🛡️</span>
                            <span>100% Satisfaction Guarantee</span>
                        </div>
                        <h3 class="guarantee-title">Your Success Is Our Only Goal</h3>
                        <p class="guarantee-text">
                            We stand behind every website we build. If you're not completely thrilled with your new website, we'll work with you until you are—or you'll get your money back. No questions asked. That's how confident we are in delivering results you'll love.
                        </p>
                        <a href="#book-discovery" class="btn btn-accent">Start Risk-Free Today</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Social Proof Section -->
    <section class="social-proof">
        <div class="container">
            <div class="section-header">
                <h2>What Our Clients Say</h2>
                <p>Real businesses. Real results. Real testimonials.</p>
            </div>
            
            <div class="testimonials-grid">
                <div class="testimonial-card fade-in-up">
                    <div class="rating">★★★★★</div>
                    <p class="testimonial-text">
                        "Finally, a website I'm proud to share! Zachary took my outdated site and transformed it into something that actually brings in customers. Best investment I've made this year."
                    </p>
                    <div class="testimonial-author">
                        <div class="author-avatar">MR</div>
                        <div class="author-info">
                            <h4>Michael Rodriguez</h4>
                            <p>Rodriguez Landscaping, West Palm Beach</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card fade-in-up">
                    <div class="rating">★★★★★</div>
                    <p class="testimonial-text">
                        "I was nervous about getting my first website, but the process was so simple. No confusing tech talk, just clear communication and amazing results. Highly recommend!"
                    </p>
                    <div class="testimonial-author">
                        <div class="author-avatar">ST</div>
                        <div class="author-info">
                            <h4>Sarah Thompson</h4>
                            <p>Coastal Wellness Studio, Jupiter</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card fade-in-up">
                    <div class="rating">★★★★★</div>
                    <p class="testimonial-text">
                        "The unlimited revisions promise is real. We went through several iterations until it was perfect. Now our website converts visitors into clients consistently."
                    </p>
                    <div class="testimonial-author">
                        <div class="author-avatar">JW</div>
                        <div class="author-info">
                            <h4>James Williams</h4>
                            <p>Williams Law Group, Wellington</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Problem Section -->
    <section class="problem-section">
        <div class="container">
            <div class="problem-content">
                <h2>Let's Be Honest About Your Online Presence</h2>
                <p><strong>Have a website?</strong> You know that feeling when a potential customer mentions they "checked it out"? That slight cringe? The quick explanation about how you've been meaning to update it?</p>
                <p><strong>No website yet?</strong> You're tired of saying "I'm working on it" or watching customers choose competitors simply because they look more established online.</p>
                <p style="font-size: 22px; font-weight: 500;">Either way, your business deserves better. You deserve to feel confident every time someone googles you.</p>
                <a href="#book-discovery" class="btn btn-accent" style="margin-top: 32px;">Let's Fix This Together</a>
            </div>
        </div>
    </section>

    <!-- Discovery Form Section -->
    <section class="discovery-form-section" id="book-discovery">
        <div class="container">
            <div class="form-container">
                <div class="form-header">
                    <h2>Let's Talk About Your Project</h2>
                    <p>Book a free 15-minute discovery call. No pressure, just a conversation about your goals.</p>
                </div>
                
                <div class="form-success" id="formSuccess">
                    <h3>🎉 Success! We'll be in touch within 24 hours.</h3>
                    <p>Check your email for confirmation and next steps.</p>
                </div>
                
                <form name="discovery-call" method="POST" data-netlify="true" netlify-honeypot="bot-field" class="discovery-form" id="discoveryForm">
                    <input type="hidden" name="form-name" value="discovery-call">
                    <p style="display:none;">
                        <label>Don't fill this out: <input name="bot-field"></label>
                    </p>
                    
                    <div class="form-group">
                        <label for="name">Your Name *</label>
                        <input type="text" id="name" name="name" required placeholder="John Smith">
                    </div>
                    
                    <div class="form-group">
                        <label for="email">Email Address *</label>
                        <input type="email" id="email" name="email" required placeholder="john@example.com">
                    </div>
                    
                    <div class="form-group">
                        <label for="phone">Phone Number *</label>
                        <input type="tel" id="phone" name="phone" required placeholder="(561) 555-0123">
                    </div>
                    
                    <div class="form-group">
                        <label for="business">Business Name</label>
                        <input type="text" id="business" name="business" placeholder="Your Business Name">
                    </div>
                    
                    <div class="form-group">
                        <label for="project-type">Project Type *</label>
                        <select id="project-type" name="project-type" required>
                            <option value="">Select Project Type</option>
                            <option value="new-website">Brand New Website</option>
                            <option value="redesign">Website Redesign</option>
                            <option value="fix-issues">Fix Current Website Issues</option>
                            <option value="not-sure">Not Sure Yet</option>
                        </select>
                    </div>
                    
                    <div class="form-group">
                        <label for="timeline">Ideal Timeline</label>
                        <select id="timeline" name="timeline">
                            <option value="">Select Timeline</option>
                            <option value="asap">ASAP</option>
                            <option value="1-month">Within 1 Month</option>
                            <option value="2-3-months">2-3 Months</option>
                            <option value="flexible">I'm Flexible</option>
                        </select>
                    </div>
                    
                    <div class="form-group">
                        <label for="message">Tell Me About Your Project</label>
                        <textarea id="message" name="message" placeholder="What's your biggest challenge with your current website? What would success look like?"></textarea>
                    </div>
                    
                    <div class="form-submit">
                        <button type="submit" class="btn btn-accent">Book My Free Discovery Call</button>
                    </div>
                    
                    <p class="form-note">
                        🔒 Your information is 100% secure and will never be shared.<br>
                        <small style="color: rgba(255,255,255,0.6);">We typically respond within 2-4 hours during business hours.</small>
                    </p>
                </form>
            </div>
        </div>
    </section>

    <!-- Transformation Section -->
    <section class="transformation" id="transformation">
        <div class="container">
            <div class="section-header">
                <h2>Imagine Having a Website You're Proud to Share</h2>
                <p>Whether it's your first or a fresh start, let's build something that represents you properly</p>
            </div>
            
            <div class="transformation-grid">
                <div class="transformation-card fade-in-up">
                    <span class="transformation-icon">😌</span>
                    <h3>Finally Feel Professional</h3>
                    <p>No more apologizing for not having a website or explaining why yours is outdated. Just pride in how you present your business online.</p>
                </div>
                
                <div class="transformation-card fade-in-up">
                    <span class="transformation-icon">💪</span>
                    <h3>Compete With Anyone</h3>
                    <p>Stop losing to competitors just because they "look" more established online. Level the playing field with a professional presence.</p>
                </div>
                
                <div class="transformation-card fade-in-up">
                    <span class="transformation-icon">🚀</span>
                    <h3>Open New Doors</h3>
                    <p>A professional website doesn't guarantee success—but not having one guarantees missed opportunities. Remove the barrier.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services">
        <div class="container">
            <div class="section-header">
                <h2>We Build the Foundation. You Build the Business.</h2>
                <p>Here's what we actually control (and what we don't)</p>
            </div>
            
            <div class="services-grid">
                <div class="service-card fade-in-up">
                    <span class="service-icon">✅</span>
                    <h3>What We Deliver</h3>
                    <p><strong>A website that works (finally)</strong> - Whether built from scratch or redesigned completely</p>
                    <p><strong>Professional design that fits</strong> - Modern, clean, and matched to your brand</p>
                    <p><strong>Lightning-fast performance</strong> - Under 3-second load times, every time</p>
                    <p><strong>Works on every device</strong> - Perfect on phones, tablets, and desktops</p>
                    <p><strong>Built to be found</strong> - SEO-ready structure so customers can find you</p>
                    <p><strong>Easy for customers to use</strong> - Clear navigation, obvious next steps</p>
                </div>
                
                <div class="service-card fade-in-up">
                    <span class="service-icon">🤝</span>
                    <h3>What You Control</h3>
                    <p><strong>Your business operations</strong> - How you serve customers once they contact you</p>
                    <p><strong>Your marketing efforts</strong> - Driving traffic through ads, social media, networking</p>
                    <p><strong>Your sales process</strong> - Converting inquiries into paying customers</p>
                    <p><strong>Your reputation</strong> - The reviews and word-of-mouth you earn</p>
                    <p><strong>Your growth</strong> - How you scale and expand your business</p>
                </div>
            </div>
            
            <div style="text-align: center; margin-top: 48px;">
                <p style="font-size: 18px; color: var(--gray-700); font-style: italic; margin-bottom: 24px;">
                    "We give you the professional foundation. You bring the business expertise. Together, we create possibility."
                </p>
                <a href="#book-discovery" class="btn btn-primary">Start Your Foundation Today</a>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section class="portfolio" id="portfolio">
        <div class="container">
            <div class="section-header">
                <h2>Real Websites. Real Possibilities.</h2>
                <p>See what a professional website could look like for your business</p>
            </div>
            
            <div class="portfolio-grid">
                <div class="portfolio-item fade-in-up">
                    <div class="portfolio-image-container" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); position: relative; display: flex; align-items: center; justify-content: center;">
                        <div style="text-align: center; color: white;">
                            <div style="width: 80px; height: 80px; background: rgba(255,255,255,0.2); border-radius: 12px; margin: 0 auto 20px; display: flex; align-items: center; justify-content: center;">
                                <svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2">
                                    <path d="M20 7H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2z"/>
                                    <path d="M16 3H8c-1.1 0-2 .9-2 2v2h12V5c0-1.1-.9-2-2-2z"/>
                                    <circle cx="12" cy="14" r="2"/>
                                </svg>
                            </div>
                            <h4 style="font-size: 20px; font-weight: 600; margin-bottom: 8px;">Service Business</h4>
                            <p style="font-size: 14px; opacity: 0.8;">Professional & Trustworthy</p>
                        </div>
                    </div>
                    <div class="portfolio-content">
                        <h3 class="portfolio-title">Service-Based Business</h3>
                        <p class="portfolio-description">Clean, trustworthy design that tells your story and makes it easy for customers to reach out. Built to showcase expertise and build confidence.</p>
                        <a href="#book-discovery" class="portfolio-cta">Let's Build Yours →</a>
                    </div>
                </div>
                
                <div class="portfolio-item fade-in-up">
                    <div class="portfolio-image-container" style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); position: relative; display: flex; align-items: center; justify-content: center;">
                        <div style="text-align: center; color: white;">
                            <div style="width: 80px; height: 80px; background: rgba(255,255,255,0.2); border-radius: 12px; margin: 0 auto 20px; display: flex; align-items: center; justify-content: center;">
                                <svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2">
                                    <path d="M9 2L3 7v9c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V7l-6-5"/>
                                    <polyline points="9 22 9 12 15 12 15 22"/>
                                    <rect x="5" y="9" width="4" height="4"/>
                                    <rect x="15" y="9" width="4" height="4"/>
                                </svg>
                            </div>
                            <h4 style="font-size: 20px; font-weight: 600; margin-bottom: 8px;">E-commerce</h4>
                            <p style="font-size: 14px; opacity: 0.8;">Built to Sell Online</p>
                        </div>
                    </div>
                    <div class="portfolio-content">
                        <h3 class="portfolio-title">Retail & E-commerce</h3>
                        <p class="portfolio-description">Showcase products beautifully. Make purchasing simple. Built for businesses ready to sell online and compete with anyone.</p>
                        <a href="#book-discovery" class="portfolio-cta">Start Selling Online →</a>
                    </div>
                </div>
                
                <div class="portfolio-item fade-in-up">
                    <div class="portfolio-image-container" style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); position: relative; display: flex; align-items: center; justify-content: center;">
                        <div style="text-align: center; color: white;">
                            <div style="width: 80px; height: 80px; background: rgba(255,255,255,0.2); border-radius: 12px; margin: 0 auto 20px; display: flex; align-items: center; justify-content: center;">
                                <svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2">
                                    <path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/>
                                    <circle cx="9" cy="7" r="4"/>
                                    <path d="M23 21v-2a4 4 0 0 0-3-3.87"/>
                                    <path d="M16 3.13a4 4 0 0 1 0 7.75"/>
                                </svg>
                            </div>
                            <h4 style="font-size: 20px; font-weight: 600; margin-bottom: 8px;">Professional Services</h4>
                            <p style="font-size: 14px; opacity: 0.8;">Authority & Credibility</p>
                        </div>
                    </div>
                    <div class="portfolio-content">
                        <h3 class="portfolio-title">Professional Services</h3>
                        <p class="portfolio-description">Establish authority. Build trust. Perfect for consultants, lawyers, accountants, and other professionals who need to look the part.</p>
                        <a href="#book-discovery" class="portfolio-cta">Build Your Authority →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="process" id="process">
        <div class="container">
            <div class="section-header">
                <h2>Simple, Honest Process</h2>
                <p>No mysteries. No surprises. Here's exactly how we work together.</p>
            </div>
            
            <div class="process-timeline">
                <div class="process-step fade-in-up">
                    <div class="step-number">1</div>
                    <h3>We Talk (Really Talk)</h3>
                    <p>About your business, your customers, and what success looks like. Whether you need a new site or a complete redesign.</p>
                </div>
                
                <div class="process-step fade-in-up">
                    <div class="step-number">2</div>
                    <h3>Clear Proposal</h3>
                    <p>You'll know exactly what you're getting and what it costs. No contracts full of fine print. Just a clear agreement.</p>
                </div>
                
                <div class="process-step fade-in-up">
                    <div class="step-number">3</div>
                    <h3>We Build, You Guide</h3>
                    <p>Watch your website come to life. Give feedback. Request changes. We iterate until it's exactly right.</p>
                </div>
                
                <div class="process-step fade-in-up">
                    <div class="step-number">4</div>
                    <h3>Launch & Support</h3>
                    <p>Your website goes live, and we stick around. Questions? Changes? We're here. Your success is our success.</p>
                </div>
            </div>
            
            <div style="text-align: center; margin-top: 48px;">
                <a href="#book-discovery" class="btn btn-primary">Start Your Project Today</a>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="cta-section" id="contact">
        <div class="container">
            <div class="cta-content">
                <h2>Ready to Finally Have a Website That Works?</h2>
                <p>Whether you're starting fresh or starting over, let's talk about where you want to be.</p>
                <span class="phone-number">(561) 718-6725</span>
                <a href="#book-discovery" class="btn-white">Book Your Free Discovery Call</a>
                <p style="margin-top: 24px; font-size: 16px; opacity: 0.8;">
                    No pressure. No obligations. Just a real conversation about your business.
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-text">
                    © 2024 Palm Beach Websites | Building websites that open doors for businesses everywhere
                </div>
                <div class="footer-contact">
                    <a href="tel:5617186725">Call: (561) 718-6725</a>
                    <a href="#portfolio">See Examples</a>
                    <a href="#book-discovery">Start a Conversation</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Floating Actions Container -->
    <div class="floating-actions">
        <a href="#book-discovery" class="floating-book-btn" aria-label="Book Discovery Call">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                <rect x="3" y="4" width="18" height="18" rx="2" ry="2"/>
                <line x1="16" y1="2" x2="16" y2="6"/>
                <line x1="8" y1="2" x2="8" y2="6"/>
                <line x1="3" y1="10" x2="21" y2="10"/>
            </svg>
            Book Discovery Call
        </a>
        
        <a href="tel:5617186725" class="floating-call-btn" aria-label="Call us" title="Call (561) 718-6725">
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/>
            </svg>
        </a>
    </div>

    <script>
        // Optimized Intersection Observer for consistent animations
        const isMobile = window.innerWidth <= 768;
        const observerOptions = {
            threshold: 0.05, // Very low threshold for early triggering
            rootMargin: '50px 0px' // Positive margin to trigger before element is visible
        };

        const animationObserver = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    // Add visible class immediately
                    entry.target.classList.add('visible');
                    // Stop observing after animation
                    animationObserver.unobserve(entry.target);
                }
            });
        }, observerOptions);

        // Observe all animated elements
        const animatedElements = document.querySelectorAll('.fade-in-up, .transformation-card, .service-card, .portfolio-item, .process-step, .pricing-card, .testimonial-card');
        animatedElements.forEach(el => {
            animationObserver.observe(el);
        });

        // Smooth scroll for anchor links using event delegation
        document.addEventListener('click', function(e) {
            const link = e.target.closest('a[href^="#"]');
            if (!link) return;
            
            const href = link.getAttribute('href');
            if (href === '#' || !href) return;
            
            e.preventDefault();
            const target = document.querySelector(href);
            if (target) {
                const offsetTop = target.offsetTop - 80;
                window.scrollTo({
                    top: offsetTop,
                    behavior: 'smooth'
                });
                
                // Close mobile menu if open
                const mobileMenu = document.querySelector('.mobile-menu');
                const mobileToggle = document.querySelector('.mobile-menu-toggle');
                if (mobileMenu && mobileToggle && mobileMenu.classList.contains('active')) {
                    mobileMenu.classList.remove('active');
                    mobileToggle.classList.remove('active');
                    document.body.classList.remove('menu-open');
                }
            }
        });

        // Optimized scroll handling with throttle
        function throttle(func, limit) {
            let inThrottle;
            return function() {
                const args = arguments;
                const context = this;
                if (!inThrottle) {
                    func.apply(context, args);
                    inThrottle = true;
                    setTimeout(() => inThrottle = false, limit);
                }
            }
        }
        
        // Header background on scroll - optimized
        const header = document.querySelector('header');
        const updateHeader = throttle(() => {
            if (window.pageYOffset > 100) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
        }, 100);
        
        window.addEventListener('scroll', updateHeader, { passive: true });

        // Mobile menu toggle - FIXED
        const mobileMenuToggle = document.querySelector('.mobile-menu-toggle');
        const mobileMenu = document.querySelector('.mobile-menu');
        const body = document.body;
        
        if (mobileMenuToggle && mobileMenu) {
            // Toggle menu function
            function toggleMenu(open) {
                if (open === undefined) {
                    open = !mobileMenu.classList.contains('active');
                }
                
                if (open) {
                    mobileMenuToggle.classList.add('active');
                    mobileMenu.classList.add('active');
                    body.classList.add('menu-open');
                    // Save scroll position
                    const scrollY = window.scrollY;
                    body.style.position = 'fixed';
                    body.style.top = `-${scrollY}px`;
                    body.style.width = '100%';
                } else {
                    mobileMenuToggle.classList.remove('active');
                    mobileMenu.classList.remove('active');
                    body.classList.remove('menu-open');
                    // Restore scroll position
                    const scrollY = body.style.top;
                    body.style.position = '';
                    body.style.top = '';
                    body.style.width = '';
                    if (scrollY) {
                        window.scrollTo(0, parseInt(scrollY || '0') * -1);
                    }
                }
            }
            
            // Toggle button click
            mobileMenuToggle.addEventListener('click', (e) => {
                e.preventDefault();
                e.stopPropagation();
                toggleMenu();
            });

            // Close menu when clicking on links
            const mobileLinks = mobileMenu.querySelectorAll('.mobile-nav-link, .mobile-nav-cta');
            mobileLinks.forEach(link => {
                link.addEventListener('click', () => {
                    toggleMenu(false);
                });
            });
            
            // Close menu when clicking outside
            document.addEventListener('click', (e) => {
                if (mobileMenu.classList.contains('active') && 
                    !mobileMenu.contains(e.target) && 
                    !mobileMenuToggle.contains(e.target)) {
                    toggleMenu(false);
                }
            });
            
            // Close menu on escape key
            document.addEventListener('keydown', (e) => {
                if (e.key === 'Escape' && mobileMenu.classList.contains('active')) {
                    toggleMenu(false);
                }
            });
        }

        // Form handling with improved error handling
        const discoveryForm = document.getElementById('discoveryForm');
        const formSuccess = document.getElementById('formSuccess');
        
        if (discoveryForm) {
            // Safe localStorage handling
            const safeLocalStorage = {
                getItem: (key) => {
                    try {
                        return localStorage.getItem(key);
                    } catch (e) {
                        return null;
                    }
                },
                setItem: (key, value) => {
                    try {
                        localStorage.setItem(key, value);
                    } catch (e) {
                        // Silently fail
                    }
                },
                removeItem: (key) => {
                    try {
                        localStorage.removeItem(key);
                    } catch (e) {
                        // Silently fail
                    }
                }
            };
            
            // Save form data to localStorage as user types
            const formInputs = discoveryForm.querySelectorAll('input, select, textarea');
            formInputs.forEach(input => {
                // Load saved data
                const savedValue = safeLocalStorage.getItem(`form_${input.name}`);
                if (savedValue) {
                    input.value = savedValue;
                }
                
                // Save on input with debounce
                let saveTimeout;
                input.addEventListener('input', () => {
                    clearTimeout(saveTimeout);
                    saveTimeout = setTimeout(() => {
                        safeLocalStorage.setItem(`form_${input.name}`, input.value);
                    }, 500);
                });
            });
            
            // Add real-time validation
            const emailInput = discoveryForm.querySelector('#email');
            const phoneInput = discoveryForm.querySelector('#phone');
            
            if (emailInput) {
                emailInput.addEventListener('blur', function() {
                    const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
                    if (this.value && !emailRegex.test(this.value)) {
                        this.style.borderColor = 'var(--error)';
                    } else {
                        this.style.borderColor = '';
                    }
                });
            }
            
            if (phoneInput) {
                phoneInput.addEventListener('blur', function() {
                    const phoneRegex = /^[\d\s\-\(\)]+$/;
                    if (this.value && (!phoneRegex.test(this.value) || this.value.length < 10)) {
                        this.style.borderColor = 'var(--error)';
                    } else {
                        this.style.borderColor = '';
                    }
                });
            }
            
            discoveryForm.addEventListener('submit', function(e) {
                e.preventDefault();
                
                // Basic validation
                const requiredFields = discoveryForm.querySelectorAll('[required]');
                let isValid = true;
                
                requiredFields.forEach(field => {
                    if (!field.value.trim()) {
                        field.style.borderColor = 'var(--error)';
                        isValid = false;
                    } else {
                        field.style.borderColor = '';
                    }
                });
                
                if (!isValid) {
                    const firstError = discoveryForm.querySelector('[style*="var(--error)"]');
                    if (firstError) {
                        firstError.focus();
                    }
                    return;
                }
                
                // Create FormData object
                const formData = new FormData(discoveryForm);
                
                // Submit form using fetch
                fetch('/', {
                    method: 'POST',
                    headers: { "Content-Type": "application/x-www-form-urlencoded" },
                    body: new URLSearchParams(formData).toString()
                })
                .then(response => {
                    if (!response.ok) {
                        throw new Error('Network response was not ok');
                    }
                    
                    // Clear saved form data
                    formInputs.forEach(input => {
                        safeLocalStorage.removeItem(`form_${input.name}`);
                    });
                    
                    // Show success message
                    formSuccess.classList.add('show');
                    discoveryForm.reset();
                    
                    // Scroll to success message
                    formSuccess.scrollIntoView({ behavior: 'smooth', block: 'center' });
                    
                    // Track conversion if analytics is available
                    if (typeof gtag !== 'undefined') {
                        gtag('event', 'form_submit', {
                            'event_category': 'engagement',
                            'event_label': 'discovery_call'
                        });
                    }
                    
                    // Hide success message after 10 seconds
                    setTimeout(() => {
                        formSuccess.classList.remove('show');
                    }, 10000);
                })
                .catch((error) => {
                    // Show user-friendly error message
                    const errorMsg = 'We\'re having trouble submitting your form. Please call us directly at (561) 718-6725 or try again later.';
                    const firstInput = discoveryForm.querySelector('input');
                    if (firstInput) {
                        firstInput.setCustomValidity(errorMsg);
                        firstInput.reportValidity();
                        setTimeout(() => {
                            firstInput.setCustomValidity('');
                        }, 5000);
                    } else {
                        alert(errorMsg);
                    }
                });
            });
        }
        
        // Track scroll depth
        let maxScroll = 0;
        let scrollTicking = false;
        const scrollMilestones = [25, 50, 75, 90];
        const trackedMilestones = new Set();
        
        function trackScrollDepth() {
            const scrollPercentage = Math.round((window.scrollY / (document.documentElement.scrollHeight - window.innerHeight)) * 100);
            
            if (scrollPercentage > maxScroll) {
                maxScroll = scrollPercentage;
                
                // Track milestones
                scrollMilestones.forEach(milestone => {
                    if (maxScroll >= milestone && !trackedMilestones.has(milestone)) {
                        trackedMilestones.add(milestone);
                        if (typeof gtag !== 'undefined') {
                            gtag('event', 'scroll_depth', {
                                'event_category': 'engagement',
                                'event_label': `${milestone}%`
                            });
                        }
                    }
                });
            }
            scrollTicking = false;
        }
        
        window.addEventListener('scroll', () => {
            if (!scrollTicking) {
                window.requestAnimationFrame(trackScrollDepth);
                scrollTicking = true;
            }
        }, { passive: true });
        
        // Performance tracking
        window.addEventListener('load', () => {
            if ('performance' in window && performance.timing) {
                const loadTime = performance.timing.loadEventEnd - performance.timing.navigationStart;
                
                if (typeof gtag !== 'undefined' && loadTime > 0) {
                    gtag('event', 'timing_complete', {
                        'name': 'load',
                        'value': loadTime,
                        'event_category': 'performance'
                    });
                }
            }
        });
        
        // Debounce function for better performance
        function debounce(func, wait) {
            let timeout;
            return function executedFunction(...args) {
                const later = () => {
                    clearTimeout(timeout);
                    func(...args);
                };
                clearTimeout(timeout);
                timeout = setTimeout(later, wait);
            };
        }
        
        // Handle resize events efficiently
        let currentIsMobile = window.innerWidth <= 768;
        const handleResize = debounce(() => {
            const newIsMobile = window.innerWidth <= 768;
            // Only update if crossing mobile/desktop boundary
            if (newIsMobile !== currentIsMobile) {
                currentIsMobile = newIsMobile;
                // You could update animation thresholds here if needed
            }
        }, 250);
        
        window.addEventListener('resize', handleResize, { passive: true });
    </script>
</body>
</html>
