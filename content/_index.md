+++
template = "landing.html"
title = "Goyo"
[extra]
# Custom order - sections will render in this sequence
section_order = ["hero", "features", "showcase", "trust", "social_proof", "final_cta"]

[extra.hero]
title = "Welcome to Universtar!"
description = "Universtar aims to help students be more competitive in future job searching. By using universtar, you can get inspiration for your own projects, improve you skills, and gain competitveness in career"
image = "/images/mountain.png" # Background image
gradient_opacity = 20         # Opacity of the animated gradient background (0-100, default: 20)
image_opacity = 20            # Opacity of the background image (0-100, default: 20)
cta_buttons = [
    { text = "Demo", url = "http://demo.unvierstar.org/", style = "primary" },
    { text = "View on GitHub", url = "https://github.com/universtar-org", style = "secondary" },
]

# Configure the section title and description
[extra.features_section]
title = "Universities"
description = "Where the student-created projects come from"

# Add individual features
[[extra.features_section.features]]
title = "XMUM"
desc = "Universtar in Xiamen University Malaysia"
icon = "fa-solid fa-book"
url = "https://xmum.universtar.org/"

[[extra.features_section.features]]
title = "TBD"
desc = "To be determined"
icon = "fa-solid fa-minimize"

[[extra.features_section.features]]
title = "TBD"
desc = "To be determined"
icon = "fa-solid fa-bolt"

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
