---
title: "Fractional order control in haptics"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2015-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2015-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: Fractional order (FO) calculus—a generalization of the traditional calculus to arbitrary order differointegration—is an effective mathematical tool that broadens the modeling boundaries of the familiar integer order calculus. The effectiveness of this remarkable mathematical tool has been observed in many practical applications. For instance, FO models enable faithful representation of viscoelastic materials that exhibit frequency dependent stiffness and damping characteristics within a single mechanical element.

In this dissertation, we propose and analyze the use of FO controllers in haptic systems and provide a systematic analysis of this new control method in the light of the fundamental trade-off between the stability robustness and the transparency performance. FO controllers provide a promising generalization that allows one to better shape the frequency response of a system to achieve more favorable robustness and performance characteristics. In particular, the use of FO calculus in systems and control applications provides the user with an extra design variable, the order of differointegration, which can be tuned to improve the desired behavior of the overall system.

We introduce a generalized FO nondimensionalized sampled-data model for the haptic system and study its frequency dependent behaviour. Then, we analyze the stability of this system with and without a human operator in the loop. Moreover, we experimentally verify the stability analysis and demonstrate that the experiments capture the essence of the stability behaviour between different differentiation orders.

The passivity analysis is conducted for two cases, the first approach takes the environment model into account and ensures the passivity of the haptic system together with the virtual environment, while the second approach assumes the presence of a passive environment model in the control loop and introduces a controller to the closed-loop system that acts like a buffer between the haptic display and the virtual environment. The second approach is more suitable for complex environments as it investigates the passivity properties of the two-port haptic system together with a virtual coupler.

After characterizing the stability boundaries for the FO haptic system, we analyse the performance of the system by studying the transparency performance of the haptic rendering with such controllers. In particular, we employ effective impedance analysis to decompose the closed-loop impedance of a haptic system into its parts and study the contribution of FO elements on the stiffness and damping rendering characteristics of the system.

Finally, we apply the theoretical results to a novel haptic rendering scenario, haptic rendering of viscoelastic materials. A fractional order mathematical model for the human prostate tissue with history depended stress and deflection behavior, is chosen as the viscoelastic physical system to be rendered. The stress relaxation of the haptic rendering is verified against the experimental data, indicating a high fidelity rendering.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
