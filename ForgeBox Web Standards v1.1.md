ForgeBox Web Standards v1.1
Guiding Philosophy

ForgeBox Co. is built on the principle of doing things right from the beginning. Every page should provide value to both visitors and search engines, with the user experience always taking priority. Search Engine Optimization (SEO) should showcase the quality of ForgeBox products and content—not compensate for poor design or weak information.

Every new page should strengthen the website as a whole through consistent structure, clean code, descriptive content, and standardized implementation. These standards exist to ensure that the website remains scalable, maintainable, and technically sound as ForgeBox grows.

When multiple technically-correct options exist, choose the solution that is:

Most accurate to the real product
Most useful to the customer
Most consistent across the website
Most maintainable over time

Structured data and metadata should accurately represent visible page content and should never be added simply because a field exists.

1. Global Website Standards

Every indexable page on ForgeBox shall include:

A unique, descriptive <title> tag.
A unique meta description that accurately summarizes the page.
A canonical URL referencing the preferred page URL.
One primary H1 heading.
Mobile-responsive design.
HTTPS-only URLs.
Internal navigation linking to major sections of the website.
Descriptive image filenames.
Alt text for all meaningful images.
Valid HTML and CSS.
JSON-LD structured data where appropriate.
Open Graph metadata where appropriate.
Twitter/X Card metadata where appropriate.
Purpose

These standards ensure consistency throughout the website while providing search engines with clear signals about page content and structure.

2. SEO Standards
Page Title

Every page shall have a unique title optimized for both users and search engines.

Titles should clearly describe the page while naturally incorporating important keywords.

Avoid keyword stuffing.

For build pages, use the format:

Custom [Caliber] Ammo Box | [Body Color] & [Text Color] | ForgeBox

When appropriate, a custom build name (such as SINNER) may precede the title.

Meta Description

Each page shall contain a unique meta description between approximately 140–160 characters.

The description should accurately describe the page and encourage users to click from search results.

For build pages, descriptions should generally include:

Caliber or Gauge
Capacity
Color combination
Built-to-order nature
Premium 3D-printed construction
Canonical URL

Every indexable page shall contain a canonical tag pointing to its preferred URL.

Example:

https://www.forgeboxco.com/builds/9mm-50-red-white-sinner.html

Purpose:

Prevents duplicate content issues and clearly identifies the authoritative version of each page.

Headings

Each page shall contain one H1 heading describing the primary topic.

Additional headings should follow a logical H2 → H3 hierarchy.

3. Build Page Standard

Each build page represents a real completed ForgeBox build.

Every build page shall contain:

Product title
Build description
Build specifications
Five or more optimized product images
Internal links to:
Gallery
Builder
Call-to-action directing visitors to build their own ForgeBox
Product Schema
Breadcrumb Schema
Canonical URL
Unique page title
Unique meta description
Open Graph metadata
Twitter/X Card metadata
Purpose

Build pages serve as searchable examples of completed ForgeBox builds while inspiring customers to create their own custom configuration.

4. Product Schema Standard (v1.2)

Every build page shall include Product schema using JSON-LD.

Required properties
Product Name
Description
Brand
Manufacturer
SKU
Category
Material
Color
URL
Image Array
Additional Properties
Manufacturer

Manufacturer shall reference the homepage Organization entity:

"manufacturer": {
  "@id": "https://www.forgeboxco.com/#organization"
}
Material

Standard value:

PLA Plastic
Additional Properties

Rifle & Pistol builds:

Caliber
Capacity
Body Color
Text Color
Custom Text (when applicable)

Shotgun builds:

Gauge
Capacity
Body Color
Text Color
Custom Text (when applicable)
Purpose

Provides structured, machine-readable product information while accurately representing visible page content.

Only information visible on the page shall be included within structured data.

5. Breadcrumb Schema Standard

Every build page shall include BreadcrumbList schema.

Structure:

Home

↓

Gallery

↓

Current Build

Purpose:

Helps search engines understand page hierarchy and improves navigation context.

6. Image Standards

Every build shall include at least five optimized WebP images.

Image filenames should remain descriptive and consistent for each build.

Common examples include:

hero.webp
top-angled.webp
top-zoom.webp
macro-text.webp
macro-bullet.webp
front-angled.webp
side-zoom.webp

Images shall:

Be properly exposed.
Have descriptive alt text.
Use consistent lighting.
Showcase actual ForgeBox products.

Purpose:

Maintains a professional appearance while improving image indexing and consistency throughout the gallery.

7. URL Standards

Build page URLs shall follow the format:

/builds/caliber-capacity-color-color.html

Examples:

9mm-50-red-white-sinner.html

308-win-50-blue-white.html

URLs shall:

Use lowercase.
Separate words with hyphens.
Remain permanent once published.
8. SKU Standard

ForgeBox SKU values shall remain descriptive, unique, and human-readable.

Current format:

CALIBER-CAPACITY-BUILDNAME-BODYCOLOR-TEXTCOLOR

Example:

9MM-50-SINNER-SCARLET-WHITE

Purpose:

SKU values should be instantly recognizable by humans while remaining unique for inventory, analytics, and structured data.

9. Publishing Checklist

Before publishing any new build page, verify:

☐ Photos edited

☐ Images converted to WebP

☐ Images named according to standard

☐ Images uploaded

☐ Build page created

☐ Title updated

☐ Meta description updated

☐ Canonical updated

☐ Open Graph updated

☐ Twitter Cards updated

☐ Product Schema updated

☐ Breadcrumb Schema updated

☐ Alt text completed

☐ Gallery updated

☐ Sitemap updated

☐ Google Search Console indexing requested

☐ Rich Results Test completed

☐ Schema Validator completed

☐ Verify Open Graph preview image

☐ Social media post scheduled

10. Future Enhancements

The following improvements are planned for future versions of the ForgeBox website:

CollectionPage Schema
ItemList Schema for Gallery
ImageObject Schema
FAQ Schema (where appropriate)
VideoObject Schema for product videos
Google Merchant Center integration
Search functionality
Enhanced analytics and event tracking
Version History
Version 1.1 – July 2026

Completed standardization of all existing ForgeBox build pages.

Added:

Open Graph metadata standard
Twitter/X Card standard
Manufacturer Organization reference (@id)
Standardized PLA Plastic material
Gauge support for shotgun Product Schema
Updated build-page publishing checklist
Finalized build-page architecture used for all future ForgeBox product pages
