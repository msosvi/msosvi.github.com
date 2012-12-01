---
layout: post
title: "Apache Trinidad y Spring Web Flow"
date: 2012-02-13
comments: false
tags:
 - Apache Trinidad
 - Spring Web Flow
---

Para [integrar](http://static.springsource.org/spring-webflow/docs/2.3.x/spring-webflow-reference/html/ch13s13.html) Apache Trinidad con Spring Web Flow necesitamos un [AjaxHandler](http://jira.springsource.org/browse/SWF-1160) 

Con la introducción de la versión de Apache Trinidad para JSF 2 hay que hacer algunas modificaciones ya que la identificación de las solicitudes ajax ha sido modificada.

<script src="https://gist.github.com/1820713.js?file=ApacheTrinidadAjaxHandler.java"> </script>
