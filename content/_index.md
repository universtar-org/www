+++
template = "landing.html"
title = "UniverStar"
sort_by = "weight"

[extra]
# Custom order - sections will render in this sequence
section_order = ["hero", "features", "showcase", "trust", "social_proof", "final_cta"]

[extra.hero]
title = "Welcome to Universtar!"
description = "Universtar is a platform for university students to showcase and promote their projects. "
image = "/images/mountain.png" # Background image
gradient_opacity = 20         # Opacity of the animated gradient background (0-100, default: 20)
image_opacity = 20            # Opacity of the background image (0-100, default: 20)
cta_buttons = [
    { text = "Get Start", url = "/get-start/submit-project", style = "primary" },
    { text = "View on GitHub", url = "https://github.com/universtar-org", style = "secondary" },
]

# Configure the section title and description
[extra.features_section]
title = "Participating Universities"
description = "A growing list of universities currently included in the project."

# Add individual features
[[extra.features_section.features]]
title = "XMUM"
desc = "UniverStar in Xiamen University Malaysia"
icon = "fa-solid fa-book"
url = "https://xmum.universtar.org/"

[extra.social_proof_section]
title = "Why choose Universtar"
testimonials = [
    {
        author = "Career Competitiveness",
	role = "",
        quote = "By sharing your projects, you could gain more star and recognition to falitate your job hunting and career advancement."
    },
    {
        author = "Boarder Perspective",
	role = "",
        quote = "You can explore projects from different courses, gaining insight into courses content and get inspiration for your own assignments or projects."
    },
    {
        author = "Skill Improvement",
	role = "",
        quote = "You will gain skills and experience from others’ project."
    },
]

[extra.final_cta_section]
title = "Contribute to Universtar"
description = "Help us make Universtar better. Contributions are welcome!"
button = { text = "View GitHub", url = "https://github.com/universtar-org" }
# image = "/images/oilpainting.png"
+++
