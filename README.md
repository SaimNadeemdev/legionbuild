# Legion Construction Website

This is the official website for Legion Construction, showcasing services, projects, and company information. This README serves as a comprehensive reference for all pages and their paths to ensure proper maintenance and updates.

## Deployment Information

- **Deployment Platform**: Vercel
- **Repository**: https://github.com/SaimNadeemdev/legionbuild
- **Configuration**: Uses vercel.json for static site deployment

## Page Structure and Paths

### Main Pages

| Page Name | File Path | URL Path | Description |
|-----------|-----------|----------|-------------|
| Home | `/index.html` | `/` | Main landing page with hero section, services overview, and testimonials |
| About Us | `/about.html` | `/about` | Company history, mission, values, and team information |
| Services Overview | `/services.html` | `/services` | Complete list of all construction services offered |
| Gallery | `/gallery.html` | `/gallery` | Portfolio of completed projects with images |
| Contact | `/contact.html` | `/contact` | Contact form, map, and company contact information |
| Testimonials | `/testimonials.html` | `/testimonials` | Client reviews and feedback |

### Service Pages

| Page Name | File Path | URL Path | Description |
|-----------|-----------|----------|-------------|
| Service Details | `/service-details.html` | `/service-details` | Generic service details template |
| Basements | `/service-basements.html` | `/service-basements` | Basement renovation and construction services |
| Decks & Balconies | `/service-decks-balcony.html` | `/service-decks-balcony` | Deck and balcony construction services |
| Home Additions | `/service-home-additions.html` | `/service-home-additions` | Home addition and extension services |
| Kitchens & Bathrooms | `/service-kitchen-bathrooms.html` | `/service-kitchen-bathrooms` | Kitchen and bathroom renovation services |
| Pergolas | `/service-pergolas.html` | `/service-pergolas` | Pergola design and construction services |
| Sunrooms | `/service-sunrooms.html` | `/service-sunrooms` | Sunroom addition services |
| Generic Service | `/service.html` | `/service` | Basic service page template |

### Component Files

| Component Name | File Path | Description |
|----------------|-----------|-------------|
| Header | `/Header.html` | Site header with navigation, included in all pages |
| Footer | `/Footer.html` | Site footer with contact info, included in all pages |

## Asset Structure

### CSS Files

| File Path | Description |
|-----------|-------------|
| `/assets/css/bootstrap.min.css` | Bootstrap framework styles |
| `/assets/css/fontawesome.min.css` | Font Awesome icon styles |
| `/assets/css/magnific-popup.min.css` | Magnific Popup lightbox styles |
| `/assets/css/slick.min.css` | Slick slider styles |
| `/assets/css/select2.min.css` | Select2 dropdown styles |
| `/assets/css/style.css` | Main custom stylesheet |

### JavaScript Files

| File Path | Description |
|-----------|-------------|
| `/assets/js/vendor/jquery-3.6.0.min.js` | jQuery library |
| `/assets/js/bootstrap.min.js` | Bootstrap framework functionality |
| `/assets/js/slick.min.js` | Slick slider functionality |
| `/assets/js/select2.min.js` | Select2 dropdown functionality |
| `/assets/js/jquery.magnific-popup.min.js` | Magnific Popup lightbox functionality |
| `/assets/js/imagesloaded.pkgd.min.js` | ImagesLoaded plugin |
| `/assets/js/isotope.pkgd.min.js` | Isotope filtering and sorting |
| `/assets/js/wow.min.js` | WOW animations |
| `/assets/js/main.js` | Custom site scripts |

## Configuration Files

| File Path | Description |
|-----------|-------------|
| `/vercel.json` | Vercel deployment configuration |
| `/package.json` | Project metadata and dependencies |
| `/.gitignore` | Git ignore rules |
| `/.gitattributes` | Git attributes configuration |

## Update Guidelines

1. **HTML Pages**: When updating content, ensure all internal links use relative paths.
2. **CSS Modifications**: Custom styles should be added to style.css.
3. **Images**: All images should be placed in the appropriate subdirectory under `/assets/img/`.
4. **Deployment**: After changes, commit and push to GitHub. Vercel will automatically redeploy.

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **CSS Framework**: Bootstrap
- **JavaScript Libraries**: jQuery, Slick Slider, Isotope, WOW.js
- **Deployment**: Vercel (serverless)
- **Version Control**: Git/GitHub

## Contact Information

For website maintenance and updates, contact the repository owner.
