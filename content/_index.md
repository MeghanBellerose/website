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
      username: dissertation
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
