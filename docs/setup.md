# Setup and import

## Requirements

- WordPress 6.0 or newer
- PHP 7.4 or newer
- Astra theme
- Elementor
- Elementor Pro
- Advanced Custom Fields (optional for this homepage export; intended for future project content)

## Import the Elementor template

1. Install and activate Astra, Elementor, and Elementor Pro.
2. In WordPress Admin, go to **Templates > Saved Templates**.
3. Click **Import Templates**.
4. Upload `elementor-template/marija-elementor-portfolio.json`.
5. Create or open a page in Elementor.
6. Click the folder icon on the canvas.
7. Open **My Templates** and insert **Marija Elementor Portfolio**.
8. Set the page layout to **Elementor Full Width**.
9. Hide the Astra page title and primary header for this page.
10. Publish the page and set it as the static homepage under **Settings > Reading**.

## Menu

Create a WordPress menu called **Portfolio Navigation** with these links:

- Home: `#home`
- Projects: `#projects`
- About: `#about`
- GitHub: `https://github.com/lolifoks`

Select this menu in the Elementor WordPress Menu widget.

## Personalization

Before using the template on another site, replace:

- Profile photo
- Contact email
- GitHub URL if needed
- Professional summary and experience dates
- Navigation anchors that do not yet have matching sections

## Notes

Elementor templates do not package WordPress, Elementor Pro, Astra, plugin licenses, or the full database. The receiving site must install its own licensed dependencies.
