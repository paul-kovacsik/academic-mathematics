+++
# Slider widget.
widget = "slider"  
headless = true 
active = true
weight = 20 

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = "5000"

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "1000px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = ""
  content = "My lab'"
  align = "center"  # Choose `center`, `left`, or `right`.
  overlay_img = "headers/ICM2.jpg"  # Image path relative to your `static/media/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = ""
  content = "Riemannian Geometry"
  align = "right"
  overlay_img = "headers/RG_illustration.png"  # Image path relative to your `static/media/` folder.
+++
