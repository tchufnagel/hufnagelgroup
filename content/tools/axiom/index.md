---
# ---- Confirmed in layouts/single.html ----
title: AXIOM
date: 2026-11-22
summary: AXIOM is a unique instrument for x-ray phase contrast imaging (XPCI) and high-energy diffraction microscopy (HEDM) in the laboratory

# show_breadcrumb: true
show_date: true          # set false to hide the date
reading_time: false      # hide the "N min read" label

authors:
  - ethan-bernstein
  - jeevan-dalip
  - tim-long
  - michael-wall
  - me
  
#links:
#  - type: site
#    url: https://hemi.jhu.edu/

# Setting an abstract turns on the details grid for a project page.
#abstract: AXIOM is a custom instrument for x-ray phase contrast imaging (XPCI) and high-energy diffraction microscopy (HEDM) in the laboratory

#funding:
#  - funder: National Science Foundation
#    grant: Award No. 0000000
#    url: https://www.nsf.gov/
#
#  - funder: JHU Whiting School of Engineering
#    url: https://wse.jhu.edu/

#license: CC BY 4.0

share: false             # hide share buttons in the footer

# ---- Not confirmed for this Hugo Blox version: uncomment one at a time to test ----
# toc: true              # table of contents

# image:                 # featured-image settings (traditional Hugo Blox keys)
#   placement: 2         # 1 = ~720 px (default), 2 = ~1200 px, 3 = full width
#   caption: HELIX target chamber
#   preview_only: false  # true = show on cards only, not on this page

# cover:                 # banner at top of page
#   icon:
#     emoji: "💥"
#     position: inline   # or overlap

# awards:                # structure not confirmed
#   - name: Best Paper Award
---

AXIOM is a unique laboratory instrument for studying the structure of materials using x-ray phase contrast imaging (XPCI), computed tomography (CT), and far-field high-energy x-ray diffraction microscopy (HEDM).

The primary source of contrast in most laboratory x-ray imaging experiments is differential absorption of the x-rays by the sample. A familiar example is x-ray radiography to diagnose a broken bone. The dense bone absorbs x-rays more strongly than soft tissue, making the bone visible on the image. Radiography is often used in materials science, including CT for 3D visualization, but has some important limitations. It doesn't work well if the sample doesn't absorb x-rays strongly, and it has trouble seeing small defects in the material.

But there is another source of contrast due not to absorption but by the deflection of x-rays as they pass through the sample. This "phase contrast" is caused by local variations in electron density -- such as the interface between solid material and empty space. For example, a crack in a solid has two faces that can make the crack visible via phase contrast even if weak absorption means that it is invisible in ordinary radiography. This makes XPCI ideal for studying fracture.

{{< figure src="broad_view.jpg" alt="Photo of AXIOM" caption="The Advanced X-ray Imaging of Materials (AXIOM) system features a liquid metal x-ray source, advanced detectors, and a large hutch for x-ray phase contrast imaging (XPCI)." >}}

XPCI requires a coherent source of x-rays, because coherency makes it possible for small differences in x-ray phase to translated into differences in intensity that can be seen on the x-ray detector. AXIOM was specifically designed with this in mind, and has several features that make it ideal for laboratory XPCI:

- A [liquid anode x-ray source](https://www.excillum.com/products/metaljet/metaljet-e1/) producing a small yet bright x-ray spot. This source, the brightest for its spot size outside of a synchrotron facility, provides the coherent x-rays required for XPCI.
- Two detectors:
  - A Varex flat panel detector providing a large field of view;
  - A [BrillianSe amorphous selenium direct x-ray detector](https://kaimaging.com/x-ray-imaging-solutions-industry-research/high-resolution-x-ray-detector/), providing high sensitivity and very small pixel size (8 µm) for high-resolution phase-contrast imaging;
  - A long chamber (nearly 4 m) providing flexibility in setting up imaging conditions to vary the phase contrast and magnification of the images; and
  - A Deben loading stage for *in situ* studies of deformation and fracture processes in materials under load.
 
The other primary technique in AXIOM is HEDM, which is ordinarily only done at synchrotron beamlines. HEDM requires a bright, highly parallel beam of monochromatic high-energy x-rays. To produce such a beam in AXIOM, x-rays from the source are diffracted from a pair of two-dimensional parabolic graded multilayer x-ray mirrors mounted in a side-by-side (Montel) geometry. The multilayer period is design to diffract In Kα radiation (24.1 keV) from the source, producing a 1.3 mm square beam with flux of 3 × 10⁸ photons per second. 

{{< figure src="axiom_hedm_sample.jpg" alt="Photo of HEDM sample with diffraction pattern" caption="An aluminum alloy sample and diffraction pattern for high-energy x-ray diffraction measured with AXIOM." >}}

