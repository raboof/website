---
# Event Name
title       : "{{ replace .Name "-" " " | title }}"

# Event start date
date        : {{ .Date }}

# Event end date
endDate     : {{ .Date }}

# Event gets published on the calendar on or after this date
publishDate : {{ .Date }}

# Event gets removed from the calendar on or after this date
#expiryDate  : {{ .Date }}

# Event status (drafts do NOT show!)
draft       : true

# Identifying mnemonics, INTERNAL use only.
# This refers to this project from other items like blogs, teams, etc.
projects    : ["ReplaceThisWithTheCorrectProjectID"]

# External reference name (i.e. https://bodge.theme/event/slug)
slug        : ""
---

A nice description about this event could go there.
