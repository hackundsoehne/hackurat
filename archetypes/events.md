---
title: "{{ replace .Name "-" " " | title }}"
featured_image: "{{ print "img/" (now.Format "2006-01-02") ".jpg" }}"
date: {{ .Date }}
where: ""
draft: true
---
