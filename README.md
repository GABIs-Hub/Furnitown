# Furnitown
This is a DOM-CSC 206 Group I Project
        PROJECT OVERVIEW
Furnitown is a modern, responsive furniture e-commerce website designed to provide users with a seamless online shopping experience for home furniture. The platform features a clean UI/UX design with intuitive navigation, product showcases, promotional sections, and customer engagement features.
Tagline: Your Home, Our Design


        TABLE OF CONTENTS

# FEATURES
# TECH STACK
# FILE STRUCTURE
# CSS ARCHITECTURE
# COLOR PALLETTE
# TYPOGRAPHY
# LAYOUT
# HOW TO RUN
# LICENSE
# CONTRIBUTORS
        FEATURES
1. Promotional Bar
    Contact information display (Call us: +123-456-789)
    Promotional offer banner with sign-up CTA (GET 25% OFF)
    Social media links (Facebook, Twitter, Pinterest, Instagram, YouTube)
2. Navigation Bar
    Brand Logo with company name
    Main Navigation: Home, Shop, Categories, About, Contact, Blog
    User Action Icons: Search, Wishlist, Cart, User Account
3. Hero Section & Service Benefits
    Hero Badge: "The Best Online Furniture Store"
    Main Headline: "Explore Our Modern Furniture Collection"
    CTA Buttons: "Shop Now" and "View Collection"
    Social Proof: Customer avatars with 4.9 rating and 50K+ trusted customers
    Furniture Carousel: Interactive product cards (Living Room, Bedroom) with navigation arrows
    Features Bar:
    Free Shipping (orders above $180)
    Flexible Payment (multiple secure options)
    24/7 Online Support
4. Featured Product Categories
    Chairs (1500+ items) — Gaming, Lounge, Folding, Dining, Office, Armchair, Bar Stool, Club Chair
    Sofa (750+ items) — Reception, Sectional, Armless, Curved
    Lighting (450+ items) — Table, Floor, Ceiling, Wall lights
5. Our Products Collection
    Product filtering tabs: All Products, Latest Products, Best Seller, Featured Products
    Product Cards displaying:
    Product image
    Category & rating (★)
    Product name
    Price with original price strikethrough for discounts
6. Special Offers / Flash Sale
    Countdown timer (Days, Hours, Minutes, Seconds)
    25% discount promotion
    Side promotional images
7. Deals of the Day
    Discount badges (10%, 20%, 30% off, "Hot")
    Product images with hover effects
    Pricing with old/new comparison
    Star ratings
    "Shop Now" links
8. Testimonials
    Customer review cards with:
    Client photo & name
    Role/occupation
    Star ratings (5.0)
    Review text
    Slider indicators for carousel navigation
9. News & Blog
    Latest articles section with:
    Featured images
    Article titles
    Short descriptions
    "Read More" links
    "View All Blogs" CTA button
10. Additional Sections (Placeholder)
    Social Media section
    FAQ section
    Newsletter subscription
    Footer
    
    TECH STACK

| TECHNOLOGY             | PURPOSE                                     |
| ---------------------- | ------------------------------------------- |
| **HTML5**              | Page structure and semantic markup          |
| **CSS3**               | Styling and responsive design               |
| **Font Awesome 6.4.0** | Icons (social media, UI elements, features) |
| **CDN (cdnjs)**        | External library hosting                    |

        FILE STRUCTURE

    furnitown/
    │
    ├── index.html                  # Main HTML file
    │
    ├── css/
    │   ├── global.css                      # Global styles & variables
    │   ├── promotionalbar.css              # Top promo bar styles
    │   ├── navbar.css                      # Navigation styling
    │   ├── hero&services.css               # Hero section & features bar
    │   ├── featuredproductcategories.css   # Category cards
    │   ├── ourproduct.css                  # Product grid & cards
    │   ├── specialoffers.css               # Flash sale section
    │   ├── deals.css                       # Deals of the day
    │   ├── testimonials.css                # Customer reviews
    │   ├── news&blog.css                   # Blog section
    │   ├── newsletter.css                  # Newsletter signup
    │   ├── socialmedia.css                 # Social media section
    |    ├── faq.css                         # Frequently asked Questions section
    │   └── footer.css                      # Footer styling
    │
    └── assets/
        ├── icons/
        │   └── logo.png            # Brand logo
        └── images/
            ├── herochair.png
            ├── herochairmain.png
            ├── herobedmain.png
            ├── john.png
            ├── blckjohn.png
            ├── blckjane.png
            ├── whtjane.png
            ├── feat-chair.png
            ├── feat-sofa.png
            ├── feat-lighting.png
            ├── Wooden Sofa Chair.png
            ├── Circular Sofa Chair.png
            ├── Woden Nightstand.png
            ├── Bean Bag.png
            ├── flash-sale-img1.png
            ├── flash-sale-img2.png
            ├── deals-img1.png
            ├── deals-img2.png
            ├── deals-img3.png
            ├── deals-img4.png
            ├── Black lady.png
            ├── White lady.png
            ├── Blog Image Placeholder.jpg
            ├── Photo base.png
            └── Photo base (1).png

     CSS ARCHITECTURE

The project uses a modular CSS approach with separate stylesheets for each component:
| Stylesheet                      | Component                                |
| ------------------------------- | ---------------------------------------- |
| `global.css`                    | Base styles, typography, color variables |
| `promotionalbar.css`            | Top announcement bar                     |
| `navbar.css`                    | Header navigation                        |
| `hero&services.css`             | Hero banner & service features           |
| `featuredproductcategories.css` | Category showcase cards                  |
| `ourproduct.css`                | Product listing grid                     |
| `specialoffers.css`             | Flash sale countdown                     |
| `deals.css`                     | Daily deals grid                         |
| `testimonials.css`              | Review cards                             |
| `news&blog.css`                 | Blog article cards                       |
| `newsletter.css`                | Email signup                             |
| `socialmedia.css`               | Social feed integration                  |
| `faq.css`                       | Customer Feedback Service                |     
| `footer.css`                    | Site footer                              |

Key Design Elements

        COLOR PALLETTE

    /* Color Palette derived from Figma */
        --primary-color: #005B35;       /* Deep Forest Green */
        --primary-light: #1ba050;       /* Lighter green for hovers */
        --accent-color: #FC0;           /* Yellow accent */
        --accent-hover: #836400;        /* Darker gold for hovers */
        --text-dark: #222222;           /* Main headings & body text */
        --text-muted: #666666;          /* Secondary/sub-text */
        --bg-light: #F3F4F3;            /* Off-white background used in sections */
        --bg-white: #FFFFFF;            /* Pure white background */
        --border-color: #E7EAE7;        /* Light gray border for lines/cards */

         TYPOGRAPHY

Inter and Sans-serif
Clean, modern sans-serif font family
Hierarchical heading structure (H1 → H6)
Emphasis on readability and visual hierarchy

    LAYOUT

Container-based max-width layout
Flexbox & Grid for component alignment
Responsive design considerations for mobile/tablet
    
    HOW TO RUN

Clone or download the project files
Ensure all assets (images, CSS files) are in their correct directories
Open index.html in any modern web browser or use a Live server Extension to run
No build process required — pure HTML/CSS project

    LICENSE
This project is licensed by MIT, so anyone can edit or enhance or revamp the code

    CONTRIBUTORs
  FRONTEND TEAM
  
• Ogabi David (Leader)

• Jeremiah Awojinrin

• Armand Akhabue

• Kanu favour

• Adeoba Adekoya

• Havilah Joshua 

  UI/UX TEAM
  
• Israel Olashore (Leader)

• Semilore Adedeji

• Moses Bolarinwa

• Emannuel Folorunsho

• Somefun Olaoluwa

• Ajayi Taiye Steven

• Onafuwa Emmanuel

• Mafe Paul

  DOCUMENTATION TEAM
  
• Tomiwa Akindele (Leader)

• Sanni Tomiwa

• Ricketts Bolanle

• Olatunji Fawas

• Godspower Joshua

• Ojo Moyomade Elizabeth
