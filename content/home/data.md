---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Data
subtitle: ""

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
      tag: "*"
#  - name: Deep Learning
#    tag: Deep Learning
#  - name: Other
#    tag: Demo

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

# Hosting Platforms

## Open Science Framework

OSF is a publication-oriented content management system for collaboration and hosting of publication adjacent supplimentary content. This platform will serve as the first point of contact for most published data. The NIDDK group hosts a collection of OSF projects at:

[osf.ibdgc.org](https://osf.ibdgc.org)

## Globus

Globus is a distributed data access and sharing platform that allows for movement of large data objects between compute environments with a simple graphical interface. Globus will be utilized in ad hoc data distribution cases where other methods make less sense.

## Dataverse

Currently under construction.

Dataverse is an integrated data repository platform. We will be using this as the data back end to OSF for large content that requires programmatic interaction.

---

# Summary Statistics

{{% callout warning %}}
Pre-release access to IIBDGC data products requires active participation in an MOU signatory group and follows the distribution and sharing rules outlined in our [DUA](https://drive.google.com/file/d/10ZSvrUP2QKWwOv1XpeGk9AI9cn9dVbn2/view?usp=sharing). All pre-publication content should be treated as strictly confidential.
{{% /callout %}}

## Open Access

- [Latest combined GWAS and Immunochip trans-ancestry](https://www.dropbox.com/s/ttuc6s7tv26voq3/iibdgc-trans-ancestry-filtered-summary-stats.tgz?dl=0)[$^{ref.}$]({{< relref "/publication/international-multiple-sclerosis-genetics-consortium-association-2015" >}}) [$^{ref.}$]({{< relref "/publication/international-inflammatory-bowel-disease-genetics-consortium-high-density-2015" >}})
- [East Asian and European meta analysis GWAS](https://www.dropbox.com/s/gxe0pishq7assla/liu-2022-east-asian-gwas.tar.gz?dl=0)[$^{ref.}$]({{< relref "/publication/liu-genetic-2023" >}})
- {{% staticref "uploads/gwas_ichip_meta_release.txt.gz" "newtab" %}}Combined GWAS and Immunochip{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/the-international-ibd-genetics-consortium-iibdgc-hostmicrobe-2012" >}})
- {{% staticref "uploads/cd-meta.txt.gz" "newtab" %}}Crohn's disease meta-analysis{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/franke-genome-wide-2010" >}})
- {{% staticref "uploads/ucmeta-sumstats.txt.gz" "newtab" %}}Ulcerative colitis meta-analysis{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/anderson-meta-analysis-2011" >}})

## Restricted Pre-release

{{% callout note %}}
Access Requirements:

- updated personnel on the "2024" tab of the [MOU Signatory Document](https://docs.google.com/spreadsheets/d/1ykB463JQDp9BPtG355gP5EGJLwzj3xCElqdkNMtyaKA/edit?usp=sharing)
- submission of signed [DUA](https://drive.google.com/file/d/10ZSvrUP2QKWwOv1XpeGk9AI9cn9dVbn2/view?usp=sharing) to requests@ibdgenetics.org
- project proposal NOT required

Altogether, any individual making a request will need to be listed on the 2024 tab of the MOU Signatory document and have submitted a signed DUA.
{{% /callout %}}

- [Fachal et. al. GWAS EUR Tier1 Tier2 Mega2](https://osf.io/3vc8y/)

---

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
1. Send the signed copy to requests@ibdgenetics.org named **ibdgc-dua-v2.2_firstname-lastname.pdf**.
