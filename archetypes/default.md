+++
title = '{{ replace .File.ContentBaseName "-" " " | lower }}'
date = {{ .Date }}
draft = false
layout = 'products'
sku = '{{ replace .File.ContentBaseName "-" " " | lower }}'
image = '{{ replace .File.ContentBaseName "-" " " | lower }}.png'
imageText = '{{ replace .File.ContentBaseName "-" " " | lower }}'
+++

# {{ replace .File.ContentBaseName "-" " " | upper }}
