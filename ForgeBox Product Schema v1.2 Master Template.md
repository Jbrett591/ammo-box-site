<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Product",

  "name": "[PRODUCT NAME]",
  "description": "[PRODUCT DESCRIPTION]",
  "sku": "[SKU]",
  "url": "https://www.forgeboxco.com/builds/[PAGE].html",

  "image": [
    "https://www.forgeboxco.com/images/gallery/[FOLDER]/hero.webp",
    "https://www.forgeboxco.com/images/gallery/[FOLDER]/[IMAGE-2].webp",
    "https://www.forgeboxco.com/images/gallery/[FOLDER]/[IMAGE-3].webp",
    "https://www.forgeboxco.com/images/gallery/[FOLDER]/[IMAGE-4].webp",
    "https://www.forgeboxco.com/images/gallery/[FOLDER]/[IMAGE-5].webp"

    /* Add additional images here when available.
       Five or more images are recommended. */
  ],

  "brand": {
    "@type": "Brand",
    "name": "ForgeBox Co."
  },

  "manufacturer": {
    "@id": "https://www.forgeboxco.com/#organization"
  },

  "category": "Ammo Storage",

  "material": "PLA Plastic",

  "color": "[BODY COLOR] / [TEXT COLOR]",

  "additionalProperty": [

    {
      "@type": "PropertyValue",
      "name": "Caliber",
      "value": "[CALIBER]"
    }

    /* For shotgun builds use instead:

    {
      "@type": "PropertyValue",
      "name": "Gauge",
      "value": "[GAUGE]"
    }

    */
    ,

    {
      "@type": "PropertyValue",
      "name": "Capacity",
      "value": "[CAPACITY]"
    },

    {
      "@type": "PropertyValue",
      "name": "Body Color",
      "value": "[BODY COLOR]"
    },

    {
      "@type": "PropertyValue",
      "name": "Text Color",
      "value": "[TEXT COLOR]"
    }

    /* Optional custom lid text

    ,
    {
      "@type": "PropertyValue",
      "name": "Custom Text",
      "value": "[CUSTOM TEXT]"
    }

    */

  ]
}
</script>
