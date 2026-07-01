ForgeBox Web Standards v1.0
Guiding Philosophy

ForgeBox Co. is built on the principle of doing things right from the beginning. Every page should provide value to both visitors and search engines, with the user experience always taking priority. Search Engine Optimization (SEO) should showcase the quality of ForgeBox products and content—not compensate for poor design or weak information.

Every new page should strengthen the website as a whole through consistent structure, clean code, descriptive content, and standardized implementation. These standards exist to ensure that the website remains scalable, maintainable, and technically sound as ForgeBox grows.

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

Purpose

These standards ensure consistency throughout the website while providing search engines with clear signals about page content and structure.

2. SEO Standards
Page Title

Every page shall have a unique title optimized for both users and search engines.

Titles should clearly describe the page while naturally incorporating important keywords.

Avoid keyword stuffing.

Meta Description

Each page shall contain a unique meta description between approximately 140–160 characters.

The description should accurately describe the page and encourage users to click from search results.

Canonical URL

Every indexable page shall contain a canonical tag pointing to its preferred URL.

Example:

https://www.forgeboxco.com/builds/9mm-50-red-white-sinner.html

Purpose

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
Five optimized product images
Internal links to:
Gallery
Builder
Call-to-action directing visitors to build their own ForgeBox
Product Schema v1.0
Breadcrumb Schema
Canonical URL
Unique page title
Unique meta description

Purpose

Build pages serve as searchable examples of completed ForgeBox builds while inspiring customers to create their own custom configuration.

4. Product Schema Standard (v1.0)

Every build page shall include Product schema using JSON-LD.

Required properties:

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

Additional Properties include:

Caliber
Capacity
Body Color
Text Color
Custom Text (when applicable)

Purpose

Provides structured, machine-readable product information to search engines while accurately representing visible page content.

Only information visible on the page shall be included within structured data.

5. Breadcrumb Schema Standard

Every build page shall include BreadcrumbList schema.

Structure:

Home

↓

Gallery

↓

Current Build

Purpose

Helps search engines understand page hierarchy and improves navigation context.

6. Image Standards

Every build shall include five optimized WebP images using the following naming convention:

hero.webp

open-tray.webp

top-down.webp

angled-front.webp

side-detail.webp

Images shall:

Be properly exposed.
Have descriptive alt text.
Use consistent lighting.
Showcase actual ForgeBox products.

Purpose

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

Purpose

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

☐ Product Schema updated

☐ Breadcrumb Schema updated

☐ Alt text completed

☐ Gallery updated

☐ Sitemap updated

☐ Google Search Console indexing requested

☐ Rich Results Test completed

☐ Schema Validator completed

☐ Social media post scheduled
10. Future Enhancements

The following improvements are planned for future versions of the ForgeBox website:

Open Graph metadata
Twitter/X Card metadata
Organization Schema
WebSite Schema
CollectionPage Schema
ItemList Schema for Gallery
ImageObject Schema
FAQ Schema (where appropriate)
VideoObject Schema for product videos
Google Merchant Center integration
Search functionality
Enhanced analytics and event tracking
Version History

Version 1.0 – July 2026

Initial release establishing ForgeBox website standards, including SEO standards, structured data, image conventions, URL conventions, SKU conventions, publishing workflow, and build page architecture.
