---
title: "Graphql Common"
date: 2017-11-29T20:59:54-05:00
description: "Contains common utilities and static variables that are shared by other components"
categories: []
keywords: []
slug: ""
aliases: []
toc: false
draft: false
---
This module controls the configuration for GraphQL service and share some static variables with other modules to make the dependencies much simpler.

Here is an example of graphql.yml

```
# GraphQL configuration
---
# The path of GraphQL endpoint for both GET and POST
path: /graphql

# Enable GraphiQL for development environment only. It will allow you to test from your Browser.
enableGraphiQL: true
```