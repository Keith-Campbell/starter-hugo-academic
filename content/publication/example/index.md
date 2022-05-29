---
title: 'Gauss--Seidel method for multi-leader--follower games'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Atsushi Hori
  - Masao Fukushima

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2019'
doi: 'https://doi.org/10.1007/s10957-018-1391-5'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Optimization Theory and Applications*, Vol. 180, pp. 651-670, 2019
publication_short: In *JOTA*

abstract: The multi-leader–follower game has many applications such as the bilevel structured market in which two or more enterprises, called leaders, have initiatives, and the other firms, called followers, observe the leaders’ decisions and then decide their own strategies. A special case of the game is the Stackelberg model, or the single-leader–follower game, which has been studied for many years. The Stackelberg game may be reformulated as a mathematical program with equilibrium constraints, which has also been studied extensively in recent years. On the other hand, the multi-leader--follower game may be formulated as an equilibrium problem with equilibrium constraints, in which each leader’s problem is an mathematical program with equilibrium constraints. However, finding an equilibrium point of an equilibrium problem with equilibrium constraints is much more difficult than solving a single mathematical program with equilibrium constraints, because each leader’s problem contains those variables which are common to other players’ problems. Moreover, the constraints of each leader’s problem depend on the other rival leaders’ strategies. In this paper, we propose a Gauss--Seidel type algorithm with a penalty technique for solving an equilibrium problem with equilibrium constraints associated with the multi-leader--follower game, and then suggest a refinement procedure to obtain more accurate solutions. We discuss convergence of the algorithm and report some numerical results to illustrate the behavior of the algorithm.

# Summary. An optional shortened abstract.
summary: We propose a Gauss--Seidel type algorithm with a penalty technique for solving an equilibrium problem with equilibrium constraints associated with the multi-leader--follower game, and then suggest a refinement procedure to obtain more accurate solutions.

tags: ['multi-leader-follower game', 'Stackelberg game', 'Gauss--Seidel method', 'penalty method', 'B-stationary', 'S-stationary']

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
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
