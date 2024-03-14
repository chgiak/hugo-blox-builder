---
title: 'Active learning of user’s preferences estimation towards a personalized 3D navigation of geo-referenced scenes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Nikolaos Doulamis
  - George Miaoulis

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'


date: '2013-04-04'
doi: '10.1007/s10707-013-0176-0'

# Schedule page publish date (NOT publication's date).
publishDate: '2013-04-12'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: International Journal of Geoinformatica
publication_short: In Journal of Geoinformatica

abstract: The current technological evolutions enter 3D geo-informatics into their digital age, enabling new potential applications in the field of virtual tourism, pleasure, entertainment and cultural heritage. It is argued that 3D information provides the natural way of navigation. However, personalization is a key aspect in a navigation system, since a route that incorporates user preferences is ultimately more suitable than the route with the shortest distance or travel time. Usually, user’s preferences are expressed as a set of weights that regulate the degree of importance of the scene metadata on the route selection process. These weights, however, are defined by the users, setting the complexity to the user’s side, which makes personalization an arduous task. In this paper, we propose an alternative approach in which metadata weights are estimated implicitly and transparently to the users, transferring the complexity to the system side. This is achieved by introducing a relevance feedback on-line learning strategy which automatically adjusts metadata weights by exploiting information fed back to the system about the relevance of user’s preferences judgments given in a form of pair-wise comparisons. Practically implementing a relevance feedback algorithm presents the limitation that several pair-wise comparisons (samples) are required to converge to a set of reliable metadata weights. For this reason, we propose in this paper a weight rectification strategy that improves weight estimation by exploiting metadata interrelations defined through an ontology. In the sequel, a genetic optimization algorithm is incorporated to select the most user preferred routes based on a multi-criteria minimization approach. To increase the degree of personalization in 3D navigation, we have also introduced an efficient algorithm for estimating 3D trajectories around objects of interest by merging best selected 2D projected views that contain faces which are mostly preferred by the users. We have conducted simulations and comparisons with other approaches either in the field of on-line learning or route selection using objective metrics in terms of precision and recall values. The results indicate that our system yields on average a 13.76 % improvement of precision as regards the learning strategy and an improvement of 8.75 % regarding route selection. In addition, we conclude that the ontology driven weight rectification strategy can reduce the number of samples (pair-wise comparisons) required of 76 % to achieve the same precision. Qualitative comparisons have been also performed using a use case route scenario in the city of Athens.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [personalized path planning,
active learning,
3D scene exploration,
GIS systems,
virtual tour,
scene understanding
]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/publication/active-learning-of-users-preferences-estimation-towards-a-personalized-3d--navigation-of-geo-referenced-scenes/journal-article.pdf'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}
