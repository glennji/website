---
name: "{{ replace .Name "-" " " | title }}"
title: {{ delimit (union (last 1 (split (replace .Name "-" " ") " ")) (split (replace .Name "-" " ") " ") ) ", " | title }}
authors:
- {{ .Name }}
superuser: false
avatar: avatar.jpg

# Role/position
# role:
# Organizations/Affiliations
#organizations:
#- name: Stanford University
#  url: ""

# Short bio (displayed in user profile at end of posts)
bio:
---