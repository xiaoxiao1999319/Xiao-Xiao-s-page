+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `600px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "350px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Welcome to Xiao Xiao's website!"
  content = ""
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "ucla.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Get Academic"
  # cta_url = "https://sourcethemes.com/academic/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
   title = "On *Science Advances* Cover:"
   content = "Ultrathin rechargeable fiber batteries integrates into textiles"
   align = "left"
   cta_label = "Read it"
   cta_url = "https://xiao-xiao.tech/publication/1sa-fiber-battery-for-electronic-textiles/"
   cta_icon_pack = "fas"
   cta_icon = "graduation-cap"
   overlay_color = "#555"  # An HTML color value.
   overlay_img = "IEEE.jpg"  # Image path relative to your `static/img/` folder.
   overlay_filter = 0.5  # Darken the image. Value in range 0-1.
 
 [[item]]
   title = "On *Chemical Reviews* Cover:"
   content = "Electronic textiles for wearable point-of-care systems"
   align = "right"
   cta_label = "Read it"
   cta_url = "https://doi.org/10.1021/acs.chemrev.1c00502"
   cta_icon_pack = "fas"
   cta_icon = "graduation-cap"
   overlay_color = "#333"  # An HTML color value.
   overlay_img = "CR.jpg"  # Image path relative to your `static/img/` folder.
   overlay_filter = 0.5  # Darken the image. Value in range 0-1.

