---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      user_groups:
          - Group Leader
          - Postdocs
          - PhD Students
          - Honours Students
          - Masters Students
          - Project Students
          - Administration
          - Visitors
          - Collaborators
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  
  - block: markdown
    content:
      title: Alumni
      text: |-
        <ul>
        {{< alumni-list >}}
        </ul>
---