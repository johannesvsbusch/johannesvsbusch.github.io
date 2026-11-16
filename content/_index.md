---
# Homepage layout: which sections appear, in which order.
# This file holds no content of its own. Each section names where its content comes from:
#   data/profile.yaml          name, bio, links, interests, education
#   data/<source>.yaml         one list of records per section (awards, teaching, ...)
#   content/publications/      one folder per publication
# Each `block` is drawn by the template layouts/_partials/blocks/<block>.html
sections:
  - block: profile
    id: about

  - block: publication-list
    id: publications
    title: Publications

  - block: data-list
    id: awards
    title: Awards
    groups:
      - source: awards        # data/awards.yaml
        fields: { title: title, detail: awarder, meta: year }

  - block: data-list
    id: service
    title: Service
    groups:
      - heading: Organizing
        source: organizing    # data/organizing.yaml
        fields: { title: event, detail: venue, meta: role }
      - heading: Reviewing
        source: reviewing     # data/reviewing.yaml
        fields: { title: venue, meta: years }
        meta_fallback: count  # shown as ×N where no years are recorded
        meta_fallback_prefix: '×'

  - block: data-list
    id: teaching
    title: Teaching
    groups:
      - source: teaching      # data/teaching.yaml
        fields: { title: course, meta: terms }

  - block: contact
    id: contact
    title: Contact            # data/contact.yaml
---
