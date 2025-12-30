# Shopify Size Guide Component

A size guide component for Shopify with CM/IN measurement toggle functionality.

## Project Purpose

This component provides a responsive size guide table for Shopify stores, allowing customers to switch between centimeter and inch measurements.

## File Structure

```
/size-guide
├── /src
│   └── index.html          # Main development file - edit here
├── /dist
│   └── size-guide.liquid   # Final Shopify-ready output
└── README.md               # This documentation
```

### `/src/index.html`
The development version of the component. Use this file for local development and testing in a browser.

### `/dist/size-guide.liquid`
The production-ready Shopify Liquid file. This contains the compiled component ready for deployment.

## Copying to Shopify

1. Open `/dist/size-guide.liquid`
2. Copy the entire file contents
3. In your Shopify admin, go to **Online Store > Themes**
4. Click **Actions > Edit code**
5. Under **Sections**, click **Add a new section**
6. Name it `size-guide` and paste the copied content
7. Save the file
8. Add the section to your desired page or template
