---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

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

### Downloads
- {{% staticref "uploads/iibdgc-trans-ancestry-filtered-summary-stats.tgz" "newtab" %}}Latest combined GWAS and Immunochip trans-ancestry summary statistics{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/international-multiple-sclerosis-genetics-consortium-association-2015" >}}) [$^{ref.}$]({{< relref "/publication/international-inflammatory-bowel-disease-genetics-consortium-high-density-2015" >}})

##### Depreciated
- {{% staticref "uploads/gwas_ichip_meta_release.txt.gz" "newtab" %}}Combined GWAS and Immunochip summary statistics{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/the-international-ibd-genetics-consortium-iibdgc-hostmicrobe-2012" >}})
- {{% staticref "uploads/cd-meta.txt.gz" "newtab" %}}Crohn's disease meta-analysis summary statistics{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/franke-genome-wide-2010" >}})
- {{% staticref "uploads/" "newtab" %}}Crohn's disease meta-analysis UCSC custom track{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/franke-genome-wide-2010" >}})
- {{% staticref "uploads/ucmeta-sumstats.txt.gz" "newtab" %}}Ulcerative colitis meta-analysis summary statistics{{% /staticref %}} [$^{ref.}$]({{< relref "/publication/anderson-meta-analysis-2011" >}})

### Documents
- [Project Proposal Form](static/uploads/International_IBD_ProposalForm_v2021.docx)
- [Genotyping Manifest Template](static/uploads/DNA_genotyping_manifest_template.xlsx)
- [Genotyping Prep Protocol](static/uploads/DNA_for_genotyping_updatedOct2021.docx)
