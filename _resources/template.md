---
published: false #Defaults to true. Remove this line when using the template.
title: "Resource Template" # A title is required.
excerpt: "The short description placeholder for the resource template." # A short description is required.
date: 2015-10-13 # The original (or earliest) publication date is required.
modified: 2015-10-15 # The most recent (or earliest) modification date is optional.
difficulty: Beginner # Difficulty is required: Beginner, Intermediate, Advanced
state: "experimental" # State is required. Options are listed in state.yml
license: PD # Use spdx-id (See https://github.com/stdarg/spdx-licenses/blob/master/spdx.json) Update licenses.yml to add new license options.
publisher: # Required. Add new publishers to publishers.yml
  - Local Preservation School
creator: # Optional but encouraged.
  - Eli Pousson
audience: # Optional but encouraged. Modify or add audiences to audiences.yml
educational_use: # Workshop, online training, K-12 class, undergraduate/graduate course
interactivity: # Expository, active, or mixed
resource_type: # Not standardized yet.
based_url:
url: &cta_url "https://localpreservation.github.io/about/" # Required for resources that are not published on the main website.
header:
  teaser: /assets/images/2016-10-31-alexsnowschool-timeline-screenshot.png # Required
  overlay_image: /assets/images/4a31635u-1280-square.jpg # Optional but encouraged. Caption required.
  overlay_filter: .5 # This is the standard but can be changed.
  cta_label: Explore this resource. # Use a verb in the call to action.
  cta_url: *cta_url
topic:
  - History  # Required. Update topics.yml to add new topics.
---
