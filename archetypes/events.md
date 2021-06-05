---
translationKey: "events-{{ (now.Format "2006-01-02") }}"
title: "{{ replace .Name "-" " " | title }}"
image: "{{ print "events/" (now.Format "2006-01-02") ".jpg" }}"
where: ""
date: {{ .Date }}
publishdate: {{ .Date }}
draft: false
---
