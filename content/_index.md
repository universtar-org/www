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


[extra.trust_section]
title = "Trusted by the Best"
logos = [
    { src = "/images/logo1.svg", alt = "Company One" },
    { src = "/images/logo2.svg", alt = "Company Two" },
    { src = "/images/logo3.svg", alt = "Company Three" },
    { src = "/images/logo4.svg", alt = "Company Four" },
]


[extra.showcase_section]
title = "Theme Showcase"
subtitle = "Explore different aspects of Goyo theme"

# Tab with image
[[extra.showcase_section.tabs]]
name = "Documentation"
title = "Clean Documentation"
description = "Experience beautiful and readable documentation pages with Goyo's minimalist design approach."
image = "/images/doc-preview.jpg"

# Tab with text only
[[extra.showcase_section.tabs]]
name = "Customization"
title = "Easy Customization"
description = "Customize your site with simple configuration options. No complex setup required."

# Another tab with image
[[extra.showcase_section.tabs]]
name = "Multilingual"
title = "Multilingual Support"
description = "Built-in support for multiple languages."
image = "/images/multilingual.jpg"


[extra.social_proof_section]
title = "What Our Users Say"
testimonials = [
    {
        author = "Jane Doe",
        role = "Developer at TechCorp",
        quote = "Goyo has transformed our documentation process. It's simple, elegant, and incredibly fast.",
        avatar = "/images/avatars/jane.png"
    },
    {
        author = "John Smith",
        role = "Project Manager at Innovate LLC",
        quote = "The best Zola theme for documentation out there. The setup was a breeze.",
        avatar = "/images/avatars/john.png"
    },
    {
        author = "Alice Johnson",
        role = "Technical Writer",
        quote = "Clean design and easy to use. Perfect for our documentation needs."
    },
]

[extra.final_cta_section]
title = "Contribute to Goyo"
description = "Help us make Goyo better. Contributions are welcome!"
button = { text = "View GitHub", url = "https://github.com/hahwul/goyo" }
image = "/images/contribute.png"
+++
