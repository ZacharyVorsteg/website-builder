<!DOCTYPE html>
<html lang="en-US"><!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-17147516072">
</script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'AW-17147516072');
</script>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Developer West Palm Beach | Palm Beach Websites - Transform Your Business Online</title>
    <meta name="description" content="Stop losing customers to outdated websites. Professional web development that makes you look as good as you are. Based in West Palm Beach, serving businesses everywhere. Call (561) 718-6725.">
    <meta name="keywords" content="web developer west palm beach, website design palm beach county, web development florida, professional websites, business transformation, web design services">
    <link rel="canonical" href="https://zacharyvorsteg.com">
    
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

        /* Typography */
        h1, h2, h3, h4, h5, h6 {
            font-weight: 600;
            letter-spacing: -0.02em;
            line-height: 1.2;
        }

        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
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

        /* Mobile Menu */
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
            margin: 5px 0;
            transition: all 0.3s var(--transition);
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

        /* Mobile Menu Overlay */
        .mobile-menu {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: var(--white);
            z-index: 999;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.3s var(--transition), visibility 0.3s var(--transition);
            padding: 100px 24px 24px;
            overflow-y: auto;
        }

        .mobile-menu.active {
            opacity: 1;
            visibility: visible;
        }

        .mobile-menu nav {
            flex-direction: column;
            gap: 24px;
            align-items: flex-start;
        }

        .mobile-menu nav a {
            font-size: 24px;
            font-weight: 600;
            color: var(--black);
            padding: 10px 0;
            width: 100%;
        }

        .mobile-menu .header-cta {
            margin-top: 32px;
            display: inline-block;
            font-size: 18px;
            padding: 16px 32px;
        }

        /* Hero Section */
        .hero {
            padding: 160px 0 var(--section-padding);
            background: var(--white);
            overflow: hidden;
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
            font-size: clamp(32px, 6vw, 72px);
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

        /* Blog Section */
        .blog-section {
            padding: var(--section-padding) 0;
            background: var(--white);
        }

        .blog-header {
            text-align: center;
            margin-bottom: 60px;
        }

        .blog-header h2 {
            font-size: clamp(28px, 4vw, 48px);
            font-weight: 700;
            margin-bottom: 16px;
            color: var(--black);
        }

        .blog-header p {
            font-size: clamp(16px, 2vw, 20px);
            color: var(--gray-600);
            max-width: 600px;
            margin: 0 auto;
        }

        .blog-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
            gap: 32px;
            margin-bottom: 48px;
        }

        .blog-card {
            background: var(--white);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 2px 20px rgba(0, 0, 0, 0.08);
            transition: all 0.3s var(--transition);
            opacity: 0;
            transform: translateY(20px);
        }

        .blog-card.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .blog-card.expanded {
            grid-column: 1 / -1;
            max-width: 800px;
            margin: 0 auto;
            width: 100%;
        }

        .blog-image {
            height: 220px;
            background: var(--gray-200);
            position: relative;
            overflow: hidden;
            cursor: pointer;
            transition: height 0.3s var(--transition);
        }

        .blog-card.expanded .blog-image {
            height: 280px;
            opacity: 0.9;
        }

        .blog-category {
            position: absolute;
            top: 16px;
            left: 16px;
            background: var(--accent);
            color: var(--white);
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }

        .blog-content {
            padding: 32px;
        }

        .blog-date {
            font-size: 14px;
            color: var(--gray-500);
            margin-bottom: 12px;
        }

        .blog-title {
            font-size: 22px;
            font-weight: 600;
            margin-bottom: 12px;
            color: var(--black);
            line-height: 1.3;
        }

        .blog-card.expanded .blog-title {
            font-size: 28px;
            margin-bottom: 20px;
        }

        .blog-excerpt {
            font-size: 16px;
            color: var(--gray-600);
            line-height: 1.6;
            margin-bottom: 20px;
        }

        .blog-full-content {
            display: none;
            font-size: 16px;
            color: var(--gray-700);
            line-height: 1.8;
            margin-top: 24px;
        }

        .blog-card.expanded .blog-full-content {
            display: block;
            animation: fadeIn 0.4s ease;
        }

        .blog-full-content h4 {
            font-size: 20px;
            font-weight: 600;
            margin: 24px 0 16px;
            color: var(--black);
        }

        .blog-full-content p {
            margin-bottom: 16px;
        }

        .blog-full-content ul {
            margin: 16px 0 16px 24px;
        }

        .blog-full-content li {
            margin-bottom: 8px;
            color: var(--gray-700);
        }

        .blog-full-content .highlight {
            background: var(--gray-100);
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
            border-left: 4px solid var(--accent);
        }

        .blog-toggle {
            color: var(--accent);
            background: none;
            border: none;
            text-decoration: none;
            font-weight: 500;
            font-size: 15px;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            cursor: pointer;
            transition: gap 0.2s var(--transition);
            padding: 8px 0;
            min-height: 44px;
        }

        .blog-toggle:hover {
            gap: 10px;
        }

        .blog-toggle svg {
            transition: transform 0.3s var(--transition);
        }

        .blog-card.expanded .blog-toggle svg {
            transform: rotate(180deg);
        }

        .blog-cta-box {
            background: var(--gray-100);
            padding: 24px;
            border-radius: 8px;
            margin-top: 32px;
            text-align: center;
            display: none;
        }

        .blog-card.expanded .blog-cta-box {
            display: block;
        }

        .blog-cta-box h5 {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 12px;
            color: var(--black);
        }

        .blog-cta-box p {
            font-size: 16px;
            color: var(--gray-600);
            margin-bottom: 16px;
        }

        .blog-cta-section {
            text-align: center;
            margin-top: 60px;
            padding: 48px;
            background: var(--gray-100);
            border-radius: 12px;
        }

        .blog-cta-section h3 {
            font-size: 28px;
            font-weight: 600;
            margin-bottom: 16px;
            color: var(--black);
        }

        .blog-cta-section p {
            font-size: 18px;
            color: var(--gray-600);
            margin-bottom: 24px;
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
            transition: all 0.3s var(--transition);
            border: 2px solid transparent;
        }

        .pricing-card.featured {
            border-color: var(--accent);
            transform: scale(1.05);
            animation: subtleGlow 3s ease-in-out infinite;
        }

        @keyframes subtleGlow {
            0%, 100% {
                box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            }
            50% {
                box-shadow: 0 8px 30px rgba(0, 102, 204, 0.2);
            }
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

        /* Process Section */
        .process {
            padding: var(--section-padding) 0;
            background: var(--white);
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

        /* Location Section */
        .location {
            padding: var(--section-padding) 0;
            background: var(--gray-100);
        }

        .location-content {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }

        .location-content h2 {
            font-size: clamp(28px, 4vw, 48px);
            font-weight: 700;
            margin-bottom: 24px;
            color: var(--black);
        }

        .location-content p {
            font-size: 18px;
            color: var(--gray-600);
            line-height: 1.6;
            margin-bottom: 48px;
        }

        .location-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 16px;
            justify-content: center;
            margin-bottom: 48px;
        }

        .location-item {
            background: var(--white);
            padding: 12px 24px;
            border-radius: 8px;
            font-weight: 500;
            color: var(--gray-700);
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
            transition: all 0.2s var(--transition);
        }

        .location-item:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
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
            z-index: 998;
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
            animation: floatIn 0.6s ease-out 1s both, subtlePulse 2s infinite 1.6s;
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
            animation-play-state: paused;
        }

        .floating-call-btn svg {
            width: 24px;
            height: 24px;
            fill: var(--white);
        }

        /* Notification Toast */
        .notification-toast {
            position: fixed;
            bottom: 30px;
            left: 30px;
            background: var(--white);
            padding: 16px 24px;
            border-radius: 8px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);
            display: flex;
            align-items: center;
            gap: 12px;
            transform: translateX(-400px);
            transition: transform 0.4s var(--transition);
            z-index: 997;
            max-width: 320px;
        }

        .notification-toast.show {
            transform: translateX(0);
        }

        .notification-icon {
            width: 40px;
            height: 40px;
            background: var(--gray-100);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }

        .notification-content {
            flex: 1;
        }

        .notification-title {
            font-size: 14px;
            font-weight: 600;
            color: var(--black);
            margin-bottom: 2px;
        }

        .notification-text {
            font-size: 13px;
            color: var(--gray-600);
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
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

        @keyframes subtlePulse {
            0% {
                box-shadow: 0 4px 20px rgba(0, 102, 204, 0.3);
            }
            50% {
                box-shadow: 0 4px 30px rgba(0, 102, 204, 0.6);
            }
            100% {
                box-shadow: 0 4px 20px rgba(0, 102, 204, 0.3);
            }
        }

        @keyframes floatIn {
            0% {
                opacity: 0;
                transform: scale(0.5) translateY(20px);
            }
            100% {
                opacity: 1;
                transform: scale(1) translateY(0);
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
                font-size: clamp(36px, 5vw, 56px);
            }
        }

        /* Responsive Mobile */
        @media (max-width: 768px) {
            :root {
                --section-padding: 60px;
                --mobile-section-padding: 40px;
            }

            .header-container {
                height: 64px;
                padding: 0 16px;
            }

            nav {
                display: none;
            }

            .header-cta {
                display: none;
            }

            .mobile-menu-toggle {
                display: flex;
            }

            .hero {
                padding: 100px 0 var(--mobile-section-padding);
            }

            .hero h1 {
                font-size: clamp(28px, 8vw, 40px);
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
            .blog-section,
            .location {
                padding: var(--mobile-section-padding) 0;
            }

            .blog-grid {
                grid-template-columns: 1fr;
                gap: 24px;
            }

            .blog-card {
                border-radius: 8px;
            }

            .blog-card.expanded {
                margin: 0;
            }

            .blog-cta-section {
                padding: 32px 20px;
                margin-top: 40px;
            }

            .blog-full-content .highlight {
                padding: 16px;
            }

            .blog-cta-box {
                padding: 20px;
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

            /* Mobile notification */
            .notification-toast {
                left: 16px;
                right: 16px;
                max-width: none;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 16px;
            }

            .hero h1 {
                font-size: 28px;
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

            .blog-content {
                padding: 24px 20px;
            }

            .trust-grid {
                grid-template-columns: 1fr;
                text-align: center;
            }

            .location-grid {
                gap: 12px;
            }

            .location-item {
                padding: 10px 20px;
                font-size: 14px;
            }

            /* Hide floating book button on very small screens */
            .floating-book-btn {
                display: none;
            }
        }

        /* Fade-in-up utility class */
        .fade-in-up {
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.6s var(--transition);
        }

        .fade-in-up.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="header-container">
            <div class="logo">Palm Beach Websites</div>
            <nav>
                <a href="#transformation">Why It Matters</a>
                <a href="#portfolio">See Our Work</a>
                <a href="#blog">Resources</a>
                <a href="#pricing">Pricing</a>
                <a href="#book-discovery">Book Discovery Call</a>
            </nav>
            <a href="#book-discovery" class="header-cta">Book Free Call</a>
            <button class="mobile-menu-toggle" aria-label="Menu">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </div>
    </header>

    <!-- Mobile Menu -->
    <div class="mobile-menu">
        <nav>
            <a href="#transformation">Why It Matters</a>
            <a href="#portfolio">See Our Work</a>
            <a href="#blog">Resources</a>
            <a href="#pricing">Pricing</a>
            <a href="#book-discovery">Book Discovery Call</a>
            <a href="tel:5617186725" class="header-cta">Call Now</a>
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
                    <a href="#book-discovery" class="btn btn-primary">Book Your Free Discovery Call</a>
                    <a href="#portfolio" class="btn btn-secondary">See What's Possible</a>
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
                
                <div class="portfolio-item fade-in-up">
                    <div class="portfolio-image-container" style="background: linear-gradient(135deg, #fa709a 0%, #fee140 100%); position: relative; display: flex; align-items: center; justify-content: center;">
                        <div style="text-align: center; color: white;">
                            <div style="width: 80px; height: 80px; background: rgba(255,255,255,0.2); border-radius: 12px; margin: 0 auto 20px; display: flex; align-items: center; justify-content: center;">
                                <svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2">
                                    <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/>
                                    <circle cx="12" cy="10" r="3"/>
                                </svg>
                            </div>
                            <h4 style="font-size: 20px; font-weight: 600; margin-bottom: 8px;">Local Business</h4>
                            <p style="font-size: 14px; opacity: 0.8;">Community Focused</p>
                        </div>
                    </div>
                    <div class="portfolio-content">
                        <h3 class="portfolio-title">Local Business</h3>
                        <p class="portfolio-description">Connect with your community. Show up in local searches. Built for businesses that serve their neighbors and need to be found.</p>
                        <a href="#book-discovery" class="portfolio-cta">Get Found Locally →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section class="blog-section" id="blog">
        <div class="container">
            <div class="blog-header">
                <h2>Website Tips & Business Growth</h2>
                <p>Practical advice to help your business succeed online in Palm Beach County and beyond</p>
            </div>
            
            <div class="blog-grid">
                <article class="blog-card fade-in-up" data-blog="1">
                    <div class="blog-image" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);">
                        <span class="blog-category">Local SEO</span>
                    </div>
                    <div class="blog-content">
                        <time class="blog-date">January 2025</time>
                        <h3 class="blog-title">5 Ways West Palm Beach Businesses Can Dominate Local Search</h3>
                        <p class="blog-excerpt">
                            Learn how to optimize your website for "near me" searches, Google Maps, and local directories. These proven strategies help Palm Beach County businesses get found by customers in their area.
                        </p>
                        <button class="blog-toggle" aria-label="Read full article">
                            <span>Read Full Article</span>
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <polyline points="6 9 12 15 18 9"></polyline>
                            </svg>
                        </button>
                        
                        <div class="blog-full-content">
                            <p>
                                If you're a business owner in West Palm Beach, Wellington, or anywhere in Palm Beach County, showing up in local search results isn't optional—it's essential. Here's how to make sure your business appears when potential customers are looking for what you offer.
                            </p>
                            
                            <h4>1. Claim and Optimize Your Google Business Profile</h4>
                            <p>
                                Your Google Business Profile (formerly Google My Business) is your most powerful local SEO tool. It's free, and it's what makes you appear in "near me" searches and Google Maps.
                            </p>
                            <ul>
                                <li>Verify your business location</li>
                                <li>Add high-quality photos (storefront, products, team)</li>
                                <li>Keep hours updated, especially for holidays</li>
                                <li>Respond to reviews within 24-48 hours</li>
                                <li>Post weekly updates about offers or events</li>
                            </ul>
                            
                            <h4>2. Target Location-Based Keywords</h4>
                            <p>
                                Instead of competing for generic terms like "plumber," focus on "plumber in West Palm Beach" or "emergency plumbing Wellington FL." These longer, location-specific keywords are easier to rank for and bring more qualified leads.
                            </p>
                            
                            <div class="highlight">
                                <strong>Pro Tip:</strong> Include neighborhood names too. "Royal Palm Beach dentist" or "Jupiter hair salon" can capture hyper-local searches.
                            </div>
                            
                            <h4>3. Build Local Citations</h4>
                            <p>
                                Citations are mentions of your business name, address, and phone number (NAP) on other websites. Consistency is key—make sure your information is identical everywhere.
                            </p>
                            <ul>
                                <li>Yelp, Facebook, and industry directories</li>
                                <li>Chamber of Commerce listings</li>
                                <li>Local business associations</li>
                                <li>Palm Beach County business directories</li>
                            </ul>
                            
                            <h4>4. Create Location-Specific Content</h4>
                            <p>
                                Write about local events, sponsor community activities, or create guides relevant to your area. "Best Coffee Shops Near CityPlace" or "Preparing Your West Palm Beach Home for Hurricane Season" shows search engines you're truly local.
                            </p>
                            
                            <h4>5. Mobile Optimization Is Non-Negotiable</h4>
                            <p>
                                Over 76% of people who search for something nearby on their smartphone visit a related business within 24 hours. If your site isn't mobile-friendly, you're literally turning away customers at your digital door.
                            </p>
                            
                            <div class="blog-cta-box">
                                <h5>Ready to Dominate Local Search?</h5>
                                <p>We specialize in creating websites that Palm Beach County customers can actually find.</p>
                                <a href="#book-discovery" class="btn btn-accent">Get Your Local SEO Strategy</a>
                            </div>
                        </div>
                    </div>
                </article>
                
                <article class="blog-card fade-in-up" data-blog="2">
                    <div class="blog-image" style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);">
                        <span class="blog-category">Web Design</span>
                    </div>
                    <div class="blog-content">
                        <time class="blog-date">December 2024</time>
                        <h3 class="blog-title">Why Your Florida Business Needs a Mobile-First Website in 2025</h3>
                        <p class="blog-excerpt">
                            With 70% of local searches happening on mobile devices, your website must deliver a flawless mobile experience. Discover what mobile-first really means and why it matters for your bottom line.
                        </p>
                        <button class="blog-toggle" aria-label="Read full article">
                            <span>Read Full Article</span>
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <polyline points="6 9 12 15 18 9"></polyline>
                            </svg>
                        </button>
                        
                        <div class="blog-full-content">
                            <p>
                                Picture this: A potential customer in downtown West Palm Beach searches for your service on their phone. They click your website, and... it's a desktop site crammed onto a tiny screen. Pinching, zooming, squinting. Within seconds, they hit the back button and call your competitor instead.
                            </p>
                            
                            <h4>The Mobile Reality Check</h4>
                            <p>
                                Here in South Florida, where people are always on the go—from the beach to business meetings—mobile browsing dominates. Recent data shows:
                            </p>
                            <ul>
                                <li>70% of local searches happen on mobile devices</li>
                                <li>53% of mobile users abandon sites that take over 3 seconds to load</li>
                                <li>88% of consumers who search for a local business on mobile call or visit within 24 hours</li>
                            </ul>
                            
                            <h4>What Mobile-First Actually Means</h4>
                            <p>
                                Mobile-first isn't about shrinking your desktop site. It's about designing for mobile users from the start, then expanding for larger screens. This approach ensures the best experience for the majority of your visitors.
                            </p>
                            
                            <div class="highlight">
                                <strong>Key Mobile-First Features:</strong><br>
                                • Thumb-friendly navigation<br>
                                • Click-to-call buttons<br>
                                • Simplified forms<br>
                                • Fast-loading images<br>
                                • Easy-to-read text without zooming
                            </div>
                            
                            <h4>The Business Impact</h4>
                            <p>
                                A mobile-first website isn't just about looking modern—it directly impacts your bottom line:
                            </p>
                            <ul>
                                <li><strong>Higher conversions:</strong> Mobile-optimized sites see 5x higher conversion rates</li>
                                <li><strong>Better SEO:</strong> Google uses mobile-first indexing, meaning it primarily looks at your mobile site for rankings</li>
                                <li><strong>Increased trust:</strong> Professional mobile experience = professional business</li>
                                <li><strong>Competitive advantage:</strong> Many Florida businesses still have outdated mobile sites</li>
                            </ul>
                            
                            <h4>Testing Your Mobile Experience</h4>
                            <p>
                                Pull out your phone right now and visit your website. Can you easily:
                            </p>
                            <ul>
                                <li>Find your phone number and tap to call?</li>
                                <li>Navigate without zooming?</li>
                                <li>Fill out a contact form with one hand?</li>
                                <li>Load pages in under 3 seconds?</li>
                            </ul>
                            
                            <p>
                                If you answered "no" to any of these, you're losing customers to competitors with better mobile experiences.
                            </p>
                            
                            <div class="blog-cta-box">
                                <h5>Is Your Website Driving Customers Away?</h5>
                                <p>Let's build a mobile-first website that converts visitors into customers.</p>
                                <a href="#book-discovery" class="btn btn-accent">Get Your Free Mobile Audit</a>
                            </div>
                        </div>
                    </div>
                </article>
                
                <article class="blog-card fade-in-up" data-blog="3">
                    <div class="blog-image" style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);">
                        <span class="blog-category">Business Growth</span>
                    </div>
                    <div class="blog-content">
                        <time class="blog-date">December 2024</time>
                        <h3 class="blog-title">From Zero to Hero: Building Your First Business Website (Without the Stress)</h3>
                        <p class="blog-excerpt">
                            Starting from scratch doesn't have to be overwhelming. This guide walks through everything you need to know about creating your first professional website, from choosing a domain to going live.
                        </p>
                        <button class="blog-toggle" aria-label="Read full article">
                            <span>Read Full Article</span>
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <polyline points="6 9 12 15 18 9"></polyline>
                            </svg>
                        </button>
                        
                        <div class="blog-full-content">
                            <p>
                                So you've decided it's time for a website. Maybe you've been putting it off, worried about the complexity, the cost, or simply not knowing where to start. Take a deep breath—creating your first business website is easier than you think when you have the right roadmap.
                            </p>
                            
                            <h4>Step 1: Define Your Website's Purpose</h4>
                            <p>
                                Before anything else, be crystal clear about what you want your website to achieve:
                            </p>
                            <ul>
                                <li><strong>Generate leads?</strong> Focus on contact forms and calls-to-action</li>
                                <li><strong>Sell products?</strong> You'll need e-commerce functionality</li>
                                <li><strong>Build credibility?</strong> Showcase your work and testimonials</li>
                                <li><strong>Provide information?</strong> Organize content for easy navigation</li>
                            </ul>
                            
                            <h4>Step 2: Choose Your Domain Name</h4>
                            <p>
                                Your domain is your digital address. Keep it:
                            </p>
                            <ul>
                                <li>Short and memorable</li>
                                <li>Easy to spell and pronounce</li>
                                <li>Related to your business name</li>
                                <li>.com if possible (people assume .com)</li>
                            </ul>
                            
                            <div class="highlight">
                                <strong>Budget Alert:</strong> Domains cost $10-15/year. Hosting runs $5-25/month. That's less than your monthly coffee budget for a 24/7 salesperson!
                            </div>
                            
                            <h4>Step 3: Plan Your Content</h4>
                            <p>
                                Most small business websites need these essential pages:
                            </p>
                            <ul>
                                <li><strong>Home:</strong> Clear value proposition and what you do</li>
                                <li><strong>About:</strong> Your story and why customers should trust you</li>
                                <li><strong>Services/Products:</strong> What you offer with clear pricing (if applicable)</li>
                                <li><strong>Contact:</strong> Multiple ways to reach you</li>
                                <li><strong>Testimonials:</strong> Social proof from happy customers</li>
                            </ul>
                            
                            <h4>Step 4: Design for Your Customers</h4>
                            <p>
                                Your website isn't for you—it's for your customers. Consider:
                            </p>
                            <ul>
                                <li>What questions do they have?</li>
                                <li>What problems need solving?</li>
                                <li>What would make them choose you?</li>
                                <li>How can you make their decision easy?</li>
                            </ul>
                            
                            <h4>Step 5: Launch and Learn</h4>
                            <p>
                                Perfect is the enemy of done. Your first website doesn't need to be perfect—it needs to exist. You can always improve it later. The important thing is to start connecting with customers online.
                            </p>
                            
                            <h4>Common First Website Mistakes to Avoid</h4>
                            <ul>
                                <li><strong>Too much text:</strong> People scan, they don't read novels</li>
                                <li><strong>Hidden contact info:</strong> Make it easy to reach you</li>
                                <li><strong>Stock photos of strangers:</strong> Use real photos of your business</li>
                                <li><strong>Ignoring mobile:</strong> Test on phones before launching</li>
                                <li><strong>No clear next step:</strong> Tell visitors what to do</li>
                            </ul>
                            
                            <div class="blog-cta-box">
                                <h5>Ready to Build Your First Website?</h5>
                                <p>Skip the learning curve. We'll build your professional website for just $350 with unlimited revisions.</p>
                                <a href="#pricing" class="btn btn-accent">See Our Simple Pricing</a>
                            </div>
                        </div>
                    </div>
                </article>
            </div>
            
            <div class="blog-cta-section">
                <h3>Ready to Put These Tips Into Action?</h3>
                <p>Let's build a website that actually drives results for your business.</p>
                <a href="#book-discovery" class="btn btn-primary">Get Your Free Website Strategy Call</a>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section class="pricing-section" id="pricing">
        <div class="container">
            <div class="pricing-header">
                <h2>Simple, Transparent Pricing</h2>
                <p>No hidden fees. No surprises. Just honest pricing for quality work.</p>
                <p style="margin-top: 16px; font-size: 16px; color: var(--accent); font-weight: 500;">
                    
                </p>
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

    <!-- Location Section -->
    <section class="location">
        <div class="container">
            <div class="location-content">
                <h2>Based in West Palm Beach. Working With Businesses Everywhere.</h2>
                <p>
                    We're proud to serve our local Palm Beach County community with in-person consultations and the understanding that comes from being neighbors. But great websites know no borders—we work with ambitious businesses across the country who value quality and personal service.
                </p>
                
                <div class="location-grid">
                    <div class="location-item">West Palm Beach</div>
                    <div class="location-item">Wellington</div>
                    <div class="location-item">Royal Palm Beach</div>
                    <div class="location-item">Jupiter</div>
                    <div class="location-item">The Acreage</div>
                    <div class="location-item">Loxahatchee</div>
                    <div class="location-item">& Beyond</div>
                </div>
                
                <p style="margin-top: 32px; font-size: 16px;">
                    <strong>Local?</strong> Let's meet for coffee.<br>
                    <strong>Not local?</strong> Let's build something great together anyway.
                </p>
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
    
    <!-- Notification Toast -->
    <div class="notification-toast" id="notificationToast">
        <div class="notification-icon">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="var(--accent)" stroke-width="2">
                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2z"/>
                <path d="M12 6v6l4 2"/>
            </svg>
        </div>
        <div class="notification-content">
            <div class="notification-title" id="notificationTitle">New Project Started</div>
            <div class="notification-text" id="notificationText">We don’t just build websites. We build confidence.</div>
        </div>
    </div>

    <script>
        // Intersection Observer for fade-in animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        // Observe all fade-in elements
        document.querySelectorAll('.fade-in-up, .transformation-card, .service-card, .portfolio-item, .process-step, .pricing-card, .blog-card').forEach(el => {
            observer.observe(el);
        });

        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                const href = this.getAttribute('href');
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
                    if (mobileMenu && mobileToggle) {
                        mobileMenu.classList.remove('active');
                        mobileToggle.classList.remove('active');
                    }
                }
            });
        });

        // Blog toggle functionality
        document.querySelectorAll('.blog-toggle').forEach(button => {
            button.addEventListener('click', function(e) {
                e.preventDefault();
                const card = this.closest('.blog-card');
                const isExpanded = card.classList.contains('expanded');
                
                // Close all other expanded cards
                document.querySelectorAll('.blog-card.expanded').forEach(expandedCard => {
                    if (expandedCard !== card) {
                        expandedCard.classList.remove('expanded');
                        expandedCard.querySelector('.blog-toggle span').textContent = 'Read Full Article';
                    }
                });
                
                // Toggle current card
                card.classList.toggle('expanded');
                
                // Update button text
                if (isExpanded) {
                    this.querySelector('span').textContent = 'Read Full Article';
                } else {
                    this.querySelector('span').textContent = 'Close Article';
                    // Smooth scroll to card
                    setTimeout(() => {
                        card.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
                    }, 100);
                }
            });
        });

        // Handle CTA buttons within blog posts
        document.querySelectorAll('.blog-cta-box a').forEach(link => {
            link.addEventListener('click', function(e) {
                // Let the smooth scroll handler take care of it
                const href = this.getAttribute('href');
                if (href && href.startsWith('#')) {
                    // Close the blog post
                    const card = this.closest('.blog-card');
                    if (card) {
                        card.classList.remove('expanded');
                        card.querySelector('.blog-toggle span').textContent = 'Read Full Article';
                    }
                }
            });
        });

        // Header background on scroll
        let lastScroll = 0;
        window.addEventListener('scroll', () => {
            const currentScroll = window.pageYOffset;
            const header = document.querySelector('header');
            
            if (currentScroll > 100) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
            
            lastScroll = currentScroll;
        });

        // Mobile menu toggle
        const mobileMenuToggle = document.querySelector('.mobile-menu-toggle');
        const mobileMenu = document.querySelector('.mobile-menu');
        
        mobileMenuToggle.addEventListener('click', () => {
            mobileMenuToggle.classList.toggle('active');
            mobileMenu.classList.toggle('active');
            
            // Prevent body scroll when menu is open
            if (mobileMenu.classList.contains('active')) {
                document.body.style.overflow = 'hidden';
            } else {
                document.body.style.overflow = '';
            }
        });

        // Form handling with validation
        const discoveryForm = document.getElementById('discoveryForm');
        const formSuccess = document.getElementById('formSuccess');
        
        if (discoveryForm) {
            // Add real-time validation
            const emailInput = discoveryForm.querySelector('#email');
            const phoneInput = discoveryForm.querySelector('#phone');
            
            emailInput.addEventListener('blur', function() {
                const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
                if (!emailRegex.test(this.value)) {
                    this.style.borderColor = 'var(--error)';
                } else {
                    this.style.borderColor = '';
                }
            });
            
            phoneInput.addEventListener('blur', function() {
                const phoneRegex = /^[\d\s\-\(\)]+$/;
                if (!phoneRegex.test(this.value) || this.value.length < 10) {
                    this.style.borderColor = 'var(--error)';
                } else {
                    this.style.borderColor = '';
                }
            });
            
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
                    alert('Please fill in all required fields.');
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
                .then(() => {
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
                    alert('There was an error submitting the form. Please try again or call us directly at (561) 718-6725.');
                    console.error('Error:', error);
                });
            });
        }
        
        // Show notification toast after delay
       setTimeout(() => {
    const toast = document.getElementById('notificationToast');
    const notifications = [
      { title: 'New Project Started', text: 'Most businesses lose leads due to outdated websites—ours don’t.' },
      { title: 'Client Update', text: 'Clients expect modern, fast experiences. We’re making sure they get it.' },
      { title: 'Just Launched', text: 'A slow or unclear site costs trust. This one builds it from the first click.' }
    ];
    const randomNotification = notifications[Math.floor(Math.random() * notifications.length)];
    document.getElementById('notificationTitle').textContent = randomNotification.title;
    document.getElementById('notificationText').textContent = randomNotification.text;

    toast.classList.add('show');

    setTimeout(() => {
        toast.classList.remove('show');
    }, 5000);
}, 8000);
    </script>
</body>
</html>
