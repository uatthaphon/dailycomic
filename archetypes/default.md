+++
title = "{{ replace .TranslationBaseName "-" " " | title }}"
description = ""
date = {{ .Date }}
tags = ["life", "fun"]
categories = ["Comic", "Blog"]
author = "yourname"
draft = false
weight = {{ len (where .Site.RegularPages "Section" "==" "posts") }}
+++

{{ replace .Name "-" " " | title }}
