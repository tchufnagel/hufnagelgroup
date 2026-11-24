---
# ---- Confirmed in layouts/single.html ----
title: Autonomous experimentation
date: 2026-11-08
summary: Getting robots to do our work for us.

show_breadcrumb: true
show_date: true          # set false to hide the date
reading_time: false      # hide the "N min read" label

authors:
  - harrison-park
  - gannon-murray
  - alex-dejong
  - ethan-bernstein
  - tim-long
  - michael-wall

links:
  - type: site
    url: https://aimd.jhu.edu/

# Setting an abstract turns on the details grid for a project page.
# abstract: Robots, x-rays, and lasers. Oh my!

funding:
  - funder: National Science Foundation
    grant: Award No. 2607526, 1921959
    url: https://www.nsf.gov/

  - funder: DEVCOM ARL (Army Research Laboratory)
    grant: Award Nos. W911NF-22-2-0014, W911NF-23-2-0062, W911NF-22-2-0121
    url: https://arl.devcom.army.mil

#license: CC BY 4.0

share: false             # hide share buttons in the footer

# ---- Not confirmed for this Hugo Blox version: uncomment one at a time to test ----
# toc: true              # table of contents

image:                 # featured-image settings (traditional Hugo Blox keys)
   placement: 2         # 1 = ~720 px (default), 2 = ~1200 px, 3 = full width
   caption: HELIX target chamber
   preview_only: true  # true = show on cards only, not on this page

# cover:                 # banner at top of page
#   icon:
#     emoji: "💥"
#     position: inline   # or overlap

# awards:                # structure not confirmed
#   - name: Best Paper Award
---

{{< video src="maxima-delay.mp4" poster="maxima_poster.jpg" >}}

From the earliest days of science, experiments have been performed by humans. Humans are intelligent, creative, adaptable, and dextrous - all extremely valuable for an experimentalist. But humans are not perfect. They can get tired, bored, or distracted, leading to errors. There are limits to the precision and reproducibility of their motions. And some jobs are too hazardous to ask them to do.

Recent developments in robotics are making it possible to turn some experiments over to machines, which can run them faster and with greater reproducibility than humans, improving both the quantity and quality of the data.

Marrying automated experiments with AI produces even greater advantages. In a robotic lab every experiment is systematically tracked and recorded, including all of the metadata - information that provides context for data, such as the identity of the sample, which instrument was used, and what the experimental conditions were. The result is data sets that are consistent, reliable, and less in need of subjective interpretation.

These data enable closed-loop decision-making, in which an algorithm chooses the experiments to be run based on the results of what has been learned so far. Although humans have expert knowledge, there are limits to how information they can hold in memory  and they have a hard time visualizing the many variables involved in a complex experimental campaign. AI can assist by assessing the results of the current experiment and placing it in the context of an entire data set as well the results of prior experiments and what is known from the scientific literature.

{{< project-pubs >}}

{{< arl agreement="W911NF-22-2-0014, W911NF-23-2-0062, W911NF-22-2-0121" >}}
{{< nsf award="1921959" >}}
{{< nsf-pcl >}}


