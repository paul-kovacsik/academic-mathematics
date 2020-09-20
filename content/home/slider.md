+++
# Slider widget.
widget = "slider"  
headless = true 
active = true
weight = 20 

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Paris Brain Institute"
  content = ""
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = ""  # An HTML color value. eg: #666
  overlay_img = "headers/ICM.png"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "Paris Brain Institute"
  content = ""
  align = "left"

  overlay_color = ""  # An HTML color value. eg: #555
  overlay_img = "headers/ICM2.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "Riemannian Geometry"
  content = ""
  align = "right"

  overlay_color = ""  # An HTML color value. eg: #333
  overlay_img = "headers/RG_illustration.png"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
