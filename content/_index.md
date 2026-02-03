+++
template = "landing.html"
title = "Goyo"
[extra]
# Custom order - sections will render in this sequence
section_order = ["hero", "features", "showcase", "trust", "social_proof", "final_cta"]

[extra.hero]
title = "Welcome to Universtar!"
description = "..Description of Universtar.."
image = "/images/mountain.png" # Background image
gradient_opacity = 20         # Opacity of the animated gradient background (0-100, default: 20)
image_opacity = 20            # Opacity of the background image (0-100, default: 20)
cta_buttons = [
    { text = "Demo", url = "http://demo.unvierstar.org/", style = "primary" },
    { text = "View on GitHub", url = "https://github.com/universtar-org", style = "secondary" },
]

# Configure the section title and description
[extra.features_section]
title = "Essential Features"
description = "Clean, minimal, and focused on content"

# Add individual features
[[extra.features_section.features]]
title = "XMUM"
desc = "Universtar in Xiamen University Malaysia"
icon = "fa-solid fa-book"
url = "https://xmum.universtar.org/"

[[extra.features_section.features]]
title = "Simple Design"
desc = "A theme that pursues minimalism."
icon = "fa-solid fa-minimize"

[[extra.features_section.features]]
title = "Fast Performance"
desc = "Built with performance in mind."
icon = "fa-solid fa-bolt"



[extra.final_cta_section]
title = "Contribute to Universtar"
description = "Help us make Universtar better. Contributions are welcome!"
button = { text = "View GitHub", url = "https://github.com/universtar-org" }
image = "/images/contribute.png"
+++
