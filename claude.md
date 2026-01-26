# InnovaTechBiz HTML Project Documentation

## Project Overview

**Project Name:** InnovaTechBiz (ITB) - Global IT Solutions Website
**Template:** Vixan v1.0.0 by Thememarch
**Author:** InnovaTechBiz (Private) Limited
**Type:** Multi-page HTML/CSS/JavaScript Website

### Description
A professional corporate website for InnovaTechBiz, a global IT solutions company providing services including Generative AI, AI agents, machine learning, Microsoft Azure, Microsoft 365, Power Platform, Dynamics 365, bookkeeping, tax filing, and enterprise software solutions for clients worldwide.

## Directory Structure

```
InnovaTechBiz_Html/
├── assets/
│   ├── css/              # Compiled stylesheets
│   │   ├── plugins/      # Third-party CSS (Bootstrap, FontAwesome, etc.)
│   │   └── style.css     # Main compiled stylesheet
│   ├── sass/             # SCSS source files
│   │   ├── common/       # Common components (header, footer, preloader, etc.)
│   │   ├── default/      # Default styles (typography, colors)
│   │   ├── shortcode/    # Component styles (hero, portfolio, blog, etc.)
│   │   └── style.scss    # Main SCSS entry point
│   ├── js/               # JavaScript files
│   │   ├── plugins/      # Third-party libraries
│   │   └── main.js       # Main application logic
│   ├── img/              # Images and media assets
│   └── fonts/            # Custom fonts
├── *.html                # HTML pages (34 pages)
└── README.md             # Basic project readme
```

## HTML Pages

### Main Pages (Light Theme)
- [index.html](index.html) - Digital Agency Homepage
- [about.html](about.html) - About Us
- [service.html](service.html) - Services Listing
- [portfolio.html](portfolio.html) - Portfolio Gallery
- [blog.html](blog.html) - Blog Listing
- [contact.html](contact.html) - Contact Page
- [team.html](team.html) - Team Members
- [faq.html](faq.html) - Frequently Asked Questions

### Alternative Homepages
- [marketing-agency.html](marketing-agency.html) - Marketing Agency Homepage
- [startup-agency.html](startup-agency.html) - Startup Agency Homepage
- [creative-protfolio.html](creative-protfolio.html) - Creative Portfolio Homepage
- [design-studio.html](design-studio.html) - Design Studio Homepage

### Detail Pages
- [service-details.html](service-details.html) - Individual Service Details
- [portfolio-details.html](portfolio-details.html) - Individual Portfolio Item
- [blog-details.html](blog-details.html) - Blog Post Details
- [team-details.html](team-details.html) - Team Member Details

### Utility Pages
- [error-404-page.html](error-404-page.html) - 404 Error Page

### Dark Theme Variants
All main pages have `-dark.html` variants for dark mode versions:
- `index-dark.html`
- `about-dark.html`
- `service-dark.html`
- And more...

## Technology Stack

### Frontend Framework
- **HTML5** - Semantic markup
- **CSS3/SCSS** - Styling with Sass preprocessing
- **JavaScript (jQuery)** - DOM manipulation and interactions

### CSS/Styling
- **Bootstrap 5** - Responsive grid and components
- **SCSS/Sass** - CSS preprocessing
- **FontAwesome** - Icon library
- **Custom SCSS Architecture** - Modular component-based styling

### JavaScript Libraries
- **jQuery 3.7.0** - DOM manipulation
- **GSAP (GreenSock)** - Advanced animations
  - ScrollTrigger - Scroll-based animations
  - ScrollSmoother - Smooth scrolling
  - ScrollToPlugin - Scroll navigation
  - SplitText - Text animation utilities
- **Swiper.js** - Touch slider/carousel
- **Isotope** - Filterable grid layouts
- **LightGallery** - Lightbox gallery
- **Bootstrap Bundle** - Bootstrap JavaScript components

## Key Features

### 1. Animations & Effects
Powered by GSAP with extensive scroll-based animations:

#### Text Animations
- **Hero Text Animation** - Character-by-character reveal on page load
- **Text Typing Animation** (.anim_text_writting) - Typewriter effect on scroll
- **Word Writing Animation** (.anim_word_writting) - Word-by-word reveal
- **Heading Title Animation** (.anim_heading_title) - 3D rotational reveal
- **P Tag Text Animation** (.anim_text) - Paragraph text reveal
- **Text Popup Animation** (.anim_text_popup) - Random scale text appearance
- **Stagger Text Animation** (.anim_text_upanddowns) - Character stagger effect

#### Element Animations
- **ShowZoom Animation** (.anim_div_ShowZoom) - Scale from center
- **ShowLeftSide Animation** (.anim_div_ShowLeftSide) - Slide from left
- **ShowRightSide Animation** (.anim_div_ShowRightSide) - Slide from right
- **ShowDown Animation** (.anim_div_ShowDowns) - Slide from bottom
- **ShowUp Animation** (.anim_div_ShowUps) - Slide from top
- **Blog Animation** (.anim_blog) - Diagonal slide-in
- **Startup Agency Animation** (.cs_startup_agency) - Card reveals

#### Special Effects
- **Funfact Counting** (.amin_auto_count) - Animated number counters
- **Reveal Images** (.reveal) - Image reveal with parallax
- **Button Animations** (.cs_btn_anim) - Button entrance animations
- **Button Hover Movement** (.cs_hero_btn) - Parallax button hover effect

### 2. Navigation
- **Sticky Header** - Header appears/disappears on scroll
- **Mobile Menu** - Responsive navigation with toggle
- **Side Header** - Off-canvas navigation panel
- **Dark Mode Toggle** - Theme switching capability
- **Menu Text Split** - Animated navigation links

### 3. Interactive Components
- **Modal Video** - YouTube video popup
- **Light Gallery** - Image lightbox with thumbnails
- **Accordion** - Collapsible content sections
- **Hover Tabs** - Interactive tab switching
- **Social Button Hover** - Social media interactions
- **Scroll Up Button** - Back to top functionality

### 4. Sliders & Carousels
Multiple Swiper.js configurations:
- **cs_slider_1** - Basic loop slider with pagination
- **cs_slider_2** - Slider with navigation and fraction pagination
- **cs_slider_3** - Auto-width slides with spacing
- **cs_slider_4** - Auto-playing slider
- **cs_slider_5** - Centered slides carousel
- **cs_slider_6** - Alternative centered carousel
- **cs_horizontal_scrolls** - Horizontal scrolling section
- **cs_fullscreen_swiper_slider** - Vertical full-screen slider

### 5. Portfolio & Gallery
- **Isotope Filtering** - Filterable portfolio grid
- **Creative Portfolio** - Alternative portfolio layout
- **Dynamic Backgrounds** - Data-driven background images

### 6. Smooth Scrolling
- **ScrollSmoother** - Page-wide smooth scroll effect
- **Normalized Scroll** - Consistent scrolling across devices
- **Custom Cursor** - Animated cursor following mouse

### 7. SEO & Meta
- Comprehensive meta tags
- SEO-optimized title and descriptions
- Extensive keyword targeting
- Favicon support

## SCSS Architecture

### Default Styles
- `_color_variable.scss` - Color scheme variables
- `_typography.scss` - Font styles and text utilities

### Common Components
- `_preloader.scss` - Page loading animation
- `_spacing.scss` - Margin and padding utilities
- `_general.scss` - General utilities and resets
- `_slider.scss` - Slider/carousel styles
- `_video-modal.scss` - Video popup styles
- `_header.scss` - Header navigation styles
- `_footer.scss` - Footer styles
- `_isotope.scss` - Portfolio grid styles
- `_sidebar.scss` - Sidebar/off-canvas styles

### Shortcode Components
- `_hero.scss` - Hero section styles
- `_iconbox.scss` - Icon box components
- `_card.scss` - Card components
- `_post.scss` - Blog post styles
- `_team.scss` - Team member cards
- `_imagebox.scss` - Image box components
- `_cta.scss` - Call-to-action sections
- `_timeline.scss` - Timeline components
- `_testimonial.scss` - Testimonial styles
- `_portfolio.scss` - Portfolio item styles
- `_funfact.scss` - Counter/stats styles
- `_pricing.scss` - Pricing tables
- `_about.scss` - About section styles
- `_story.scss` - Story section styles
- `_newsletter.scss` - Newsletter signup
- `_about_feature.scss` - About features
- `_services.scss` - Service components
- `_workprocess.scss` - Work process sections
- `_blog.scss` - Blog listing styles
- `_accordion.scss` - Accordion components
- `_contact.scss` - Contact form styles

## JavaScript Functions

### Core Functionality ([main.js](assets/js/main.js))

1. **preloader()** - Handles page loading animation fadeout
2. **mainNav()** - Mobile menu initialization and dark mode toggle
3. **stickyHeader()** - Sticky header show/hide on scroll
4. **dynamicBackground()** - Sets background images from data-src
5. **swiperInit()** - Initializes all Swiper sliders
6. **isotopInit()** - Isotope filtering for portfolios
7. **modalVideo()** - YouTube video popup handler
8. **hoverTab()** - Hover tab functionality
9. **lightGalleryInit()** - Image gallery initialization
10. **scrollUp()** - Scroll to top functionality
11. **showScrollUp()** - Show/hide scroll button
12. **fullScreenSwiperSlider()** - Vertical full-screen slider
13. **mousemoveHandler()** - Custom cursor animation
14. **Multiple GSAP Animations** - Various scroll-triggered animations

## Animation Classes Reference

Use these classes in HTML to trigger animations:

### Text Animations
- `.anim_banner_text_left` - Hero text left animation
- `.anim_banner_text_right` - Hero text right animation
- `.anim_subtext` - Subtext animation
- `.anim_text_writting` - Character typing animation
- `.anim_word_writting` - Word typing animation
- `.anim_heading_title` - Heading 3D reveal
- `.anim_text` - Paragraph text reveal
- `.anim_text_popup` - Random popup text
- `.anim_text_upanddowns` - Character stagger

### Element Animations
- `.anim_div_ShowZoom` - Zoom from center
- `.anim_div_ShowLeftSide` - Slide from left
- `.anim_div_ShowRightSide` - Slide from right
- `.anim_div_ShowDowns` - Slide from bottom
- `.anim_div_ShowUps` - Slide from top
- `.anim_blog` - Blog card animation
- `.cs_startup_agency.cs_card` - Startup card animation
- `.cs_btn_anim` - Button entrance animation

### Special Classes
- `.reveal` - Image reveal animation
- `.amin_auto_count` - Animated counters
- `.cs_hero_btn` - Button hover parallax

## Configuration & Customization

### GSAP Configuration
```javascript
gsap.registerPlugin(ScrollTrigger, ScrollToPlugin, ScrollSmoother);
gsap.config({ nullTargetWarn: false });
```

### ScrollSmoother Settings
- Smooth: 1.2
- NormalizeScroll: Enabled on mobile (<991px)
- Effects: Enabled on desktop (>991px)
- SmoothTouch: Enabled

### Swiper Default Settings
- Loop: true (most sliders)
- Speed: 1000ms
- Autoplay: Varies by slider
- Responsive breakpoints as needed

## SEO Keywords

The website targets the following key terms:
- Global IT solutions
- Best IT software house
- Enterprise software development
- Generative AI, AI agents, machine learning
- Microsoft services (Azure, 365, Power Platform, Dynamics 365)
- Bookkeeping and tax filing services
- Regional focus: USA, Europe, Gulf, Dubai, Pakistan

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- Touch-enabled slider interactions
- Fallbacks for older browsers

## Performance Considerations

### JavaScript Execution
- jQuery-based with modern ES6+ libraries
- GSAP for performant animations
- Lazy loading with ScrollTrigger
- Conditional animation execution based on viewport

### CSS/SCSS
- Modular SCSS architecture
- Minified production CSS
- Bootstrap grid for responsive layouts

### Assets
- Minified plugin files
- Optimized image loading
- Dynamic background images

## Development Workflow

### Prerequisites
- SASS compiler for SCSS changes
- Local web server for testing
- Modern code editor

### File Organization
- Keep HTML pages in root
- All assets in `/assets` directory
- SCSS source files in `/assets/sass`
- Compile to `/assets/css/style.css`

### Customization Guide

#### Colors
Edit [assets/sass/default/_color_variable.scss](assets/sass/default/_color_variable.scss)

#### Typography
Edit [assets/sass/default/_typography.scss](assets/sass/default/_typography.scss)

#### Component Styles
Edit respective files in `assets/sass/shortcode/`

#### Animations
Edit [assets/js/main.js](assets/js/main.js) GSAP configurations

## Git Status

Current branch: `main`

Modified files:
- `.DS_Store`
- `assets/.DS_Store`
- `assets/sass/.DS_Store`

Untracked:
- `.vscode/`
- `Archive.zip`

Recent commits:
- "working on pages heades anf dooter"
- "working on services blogs portfolio"
- "push code"

## Notes

### Preloader
The preloader is currently commented out in the HTML. Uncomment to enable loading animation.

### Dark Mode
- Dark theme variants are separate HTML files
- JavaScript toggle switches `.cs_dark` class on body
- Theme switcher available via `.cs_mode_btn`

### Custom Cursor
Custom animated cursor elements:
- `.cs_cursor_1` - Main cursor
- `.cs_cursor_2` - Following cursor

### Menu System
- Desktop navigation in header
- Mobile hamburger menu
- Off-canvas side panel
- Animated menu text with character splitting

## Contact & Support

**Company:** InnovaTechBiz (Private) Limited
**Website:** [index.html](index.html)
**Template:** Vixan by Thememarch

## License

Template: Vixan v1.0.0 by Thememarch
Implementation: InnovaTechBiz (Private) Limited

---

*Last Updated: December 26, 2025*
