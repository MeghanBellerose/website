---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-06-14
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      username: admin
  - block: about.biography
    id: dissertation
    content:
      title: Dissertation
      username: dissertation
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
  - block: collection
    content:
      title: Other Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
