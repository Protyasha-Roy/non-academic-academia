+++
date = '{{ .Date }}'
lastmod = '{{ .Lastmod }}'
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
description = '{{ .Params.description }}'
tags = {{ .Params.tags }}
categories = {{ .Params.categories }}
+++
