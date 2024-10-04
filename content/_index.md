---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-10-04
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      username: admin
  - block: markdown
    id: dissertation
    content:
      title: Dissertation
      text: |-
        My dissertation examines the impact of health insurance coverage policies on reproductive and pregnancy care use among women with disabilities in the United States. This work is funded by an F31 Ruth L. Kirschstein Predoctoral Individual National Research Award from the Eunice Kennedy Shriver National Institute of Child Health & Human Development (NICHD).
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: contact
    id: contact
    content:
      title: Contact
      text: "Email: meghan_bellerose@brown.edu"
      contact_links:
        - icon: twitter
          icon_pack: fab
          link: https://x.com/MeghanBellerose
          name: "@MeghanBellerose"
    design:
      columns: '2'
---
