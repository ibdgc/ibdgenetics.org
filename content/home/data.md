---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Data
subtitle: ''

content:
  # Page type to display. E.g. project.
  #page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
#  - name: Deep Learning
#    tag: Deep Learning
#  - name: Other
#    tag: Demo

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

# IBDGC Data Commons
This is the central, managed data repository for the International IBDGC. Hosted by the NIDDK member consortium, the Data Commons offers a secure and accessible platform to distribute and interact with both pre-release and open access data products.

- Access the Commons at [ibdgc.datacommons.io](ibdgc.datacommons.io)
- Documentation for the high throughput command-line download/upload client found [here](https://gen3.org/resources/user/cdis-client/).

# Summary Statistics
{{% callout warning %}}
Pre-release access to IIBDGC data products requires active participation in an MOU signatory research group and follows the distribution and sharing rules outlined in our [DUA](https://drive.google.com/file/d/10ZSvrUP2QKWwOv1XpeGk9AI9cn9dVbn2/view?usp=sharing). With that, pre-publication summary statistics should be treated as confidential.
{{% /callout %}}

## Open Access
- [Latest combined GWAS and Immunochip trans-ancestry summary statistics](https://www.dropbox.com/s/ttuc6s7tv26voq3/iibdgc-trans-ancestry-filtered-summary-stats.tgz?dl=0)[$^{ref.}$]({{< relref "/publication/international-multiple-sclerosis-genetics-consortium-association-2015" >}}) [$^{ref.}$]({{< relref "/publication/international-inflammatory-bowel-disease-genetics-consortium-high-density-2015" >}})
- [East Asian and European meta analysis GWAS summary statistics](https://www.dropbox.com/s/gxe0pishq7assla/liu-2022-east-asian-gwas.tar.gz?dl=0)[$^{ref.}$]({{< relref "/publication/liu-genetic-2023" >}})
- {{% staticref "uploads/gwas_ichip_meta_release.txt.gz" "newtab" %}}Combined GWAS and Immunochip summary statistics{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/the-international-ibd-genetics-consortium-iibdgc-hostmicrobe-2012" >}})
- {{% staticref "uploads/cd-meta.txt.gz" "newtab" %}}Crohn's disease meta-analysis summary statistics{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/franke-genome-wide-2010" >}})
- {{% staticref "uploads/ucmeta-sumstats.txt.gz" "newtab" %}}Ulcerative colitis meta-analysis summary statistics{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/anderson-meta-analysis-2011" >}})

## Pre-release
{{% callout note %}}
Access Requirements:

- signed DUA
- member of MOU signatory group
- project proposal NOT required
{{% /callout %}}

- Fachal et. al. GWAS EUR Tier1 Mega2
    - Summary Stats v1.0 ([gen3 client](https://gen3.org/resources/user/cdis-client/) download only)
        - dg.EA80/582b6011-3337-476f-b645-0c68f86568ed
    - [Summary Stats v1.0 5e7 Filtered](https://ibdgc.datacommons.io/files/dg.EA80/4a144666-20c7-4895-b67a-548ca1c12d28)
    - [Terms of Use](https://ibdgc.datacommons.io/files/dg.EA80/f9934f08-6576-401e-837c-5787234abe20)

# Forms
- [Project Proposal Form](https://forms.gle/4oLAJ8Q5bf31p3Eh9)
- [MOU Web Form](https://forms.gle/aMJQ6bou9cwZGiGy5)
- {{% staticref "uploads/IIBDGC_MOU_28jan2019_with_bookmarks.pdf" "newtab" %}}Complete MOU{{% /staticref %}}
- [International DUA](https://drive.google.com/file/d/10ZSvrUP2QKWwOv1XpeGk9AI9cn9dVbn2/view?usp=sharing)

**Memo of Understanding (MOU) Instructions:**

1. Complete the [MOU Web Form](https://forms.gle/aMJQ6bou9cwZGiGy5).
1. Sign the received copy of the completed form at your provided email address.
1. Send the signed copy to contact@ibdgenetics.org.

**Data Use Agreement (DUA) Instructions:**
{{% callout note %}}
All individuals seeking to access pre-publication summary statistics need to submit a signed DUA
{{% /callout %}}

1. Download the form [here](https://drive.google.com/file/d/10ZSvrUP2QKWwOv1XpeGk9AI9cn9dVbn2/view?usp=sharing).
1. Complete the document using a pdf editing tool (e.g. adobe acrobat, apple preview).
    1. Initial the "IIBDGC Internal Use Only" appendix if applicable (i.e. when requesting access to pre-publication data).
1. Send the signed copy to requests@ibdgc.org named **ibdgc-dua-v2.2_firstname-lastname.pdf**.

