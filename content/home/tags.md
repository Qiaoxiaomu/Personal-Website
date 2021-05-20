---
# An instance of the Tag Cloud widget.
# Docs: https://wowchemy.com/docs/page-builder/
widget: tag_cloud

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 120

title: Popular Topics
subtitle: ''

content:
# Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy: tags
  # Choose how many tags you would like to display (0 = all tags)
  count: 20
design:
  # Minimum and maximum font sizes (1.0 = 100%).
  font_size_min: 0.7
  font_size_max: 2.0
  background:
    # Name of image in `assets/media/`.
    image: image.jpg
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.6
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true
---
