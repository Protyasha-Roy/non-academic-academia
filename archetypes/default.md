+++
date = '{{ .Date }}'
lastmod = '{{ .Lastmod }}'
draft = false
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
description = '{{ .Params.description }}'
tags = {{ .Params.tags }}
categories = {{ .Params.categories }}
+++
