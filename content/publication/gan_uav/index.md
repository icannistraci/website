---
draft: false
title: "A Novel GAN-Based Anomaly Detection and Localization Method for Aerial Video Surveillance at Low Altitude"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Danilo Avola
- admin
- Marco Cascio
- Luigi Cinque
- Anxhelo Diko
- Alessio Fagioli
- Gian Luca Foresti
- Romeo Lanzino
- Maurizio Mancini
- Alessio Mecca
- Daniele Pannone

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-08-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: MDPI Remote Sensing 
publication_short: MDPI Remote Sensing

abstract: The last two decades have seen an incessant growth in the use of Unmanned Aerial Vehicles (UAVs) equipped with HD cameras for developing aerial vision-based systems to support civilian and military tasks, including land monitoring, change detection, and object classification. To perform most of these tasks, the artificial intelligence algorithms usually need to know, a priori, what to look for, identify. or recognize. Actually, in most operational scenarios, such as war zones or post-disaster situations, areas and objects of interest are not decidable a priori since their shape and visual features may have been altered by events or even intentionally disguised (e.g., improvised explosive devices (IEDs)). For these reasons, in recent years, more and more research groups are investigating the design of original anomaly detection methods, which, in short, are focused on detecting samples that differ from the others in terms of visual appearance and occurrences with respect to a given environment. In this paper, we present a novel two-branch Generative Adversarial Network (GAN)-based method for low-altitude RGB aerial video surveillance to detect and localize anomalies. We have chosen to focus on the low-altitude sequences as we are interested in complex operational scenarios where even a small object or device can represent a reason for danger or attention. The proposed model was tested on the UAV Mosaicking and Change Detection (UMCD) dataset, a one-of-a-kind collection of challenging videos whose sequences were acquired between 6 and 15 m above sea level on three types of ground (i.e., urban, dirt, and countryside). Results demonstrated the effectiveness of the model in terms of Area Under the Receiving Operating Curve (AUROC) and Structural Similarity Index (SSIM), achieving an average of 97.2% and 95.7%, respectively, thus suggesting that the system can be deployed in real-world applications.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mdpi.com/2072-4292/14/16/4110'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
