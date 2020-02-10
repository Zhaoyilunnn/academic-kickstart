+++

widget = "slider"  # Use the Slider widget
headless = true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Personal"
  content = "I appreciate it a lot to be with my cute girlfriend, "
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/bubbles-wide.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Album by Lulu, 03/03/2019 - forever"
  cta_url = "files/2020-02-14.mp4"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"

# [[item]]
#   title = "Left"
#   content = "I am left aligned 😄"
#   align = "left"
# 
#   overlay_color = "#555"  # An HTML color value.
#   overlay_img = ""  # Image path relative to your `static/img/` folder.
#   overlay_filter = 0.5  # Darken the image. Value in range 0-1.
# 
# [[item]]
#   title = "Right"
#   content = "I am right aligned 😄"
#   align = "right"
# 
#   overlay_color = "#333"  # An HTML color value.
#   overlay_img = ""  # Image path relative to your `static/img/` folder.
#   overlay_filter = 0.5  # Darken the image. Value in range 0-1.

+++
