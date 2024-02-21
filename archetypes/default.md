+++
title = 'post {{ .Date | time.Format ":date_medium" }}'
date = {{ .Date }}
categories = ['draft']
tags = ['draft']
slug = '{{ .Date | time.Format ":time_long" }}'
draft = false
+++
