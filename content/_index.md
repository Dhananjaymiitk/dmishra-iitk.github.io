---
type: widget_page

# This tells the site to build a homepage using blocks
sections:
  - block: about.biography
    content:
      username: admin
    design:
      background:
        color: '#f7f7f7' # Light grey background for the bio
  - block: collection
    content:
      title: Featured Research & Projects
      subtitle: 'Bridging Materials Science and AI Hardware'
      filters:
        folders:
          - project
    design:
      columns: '2'
      view: card
  - block: contact
    content:
      title: Contact & Collaboration
      subtitle: 'I am open to research collaborations and industry consulting'
      email: 'dmishra32@outlook.com'
      address:
        street: 'Dept. of MSE, IIT Kanpur'
        city: 'Kanpur'
        region: 'Uttar Pradesh'
        postcode: '208016'
        country: 'India'
        country_code: 'IN'
---
