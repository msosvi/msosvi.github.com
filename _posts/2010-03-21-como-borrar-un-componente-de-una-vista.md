---
layout: post
title: "Como borrar un componente de una vista JSF."
date: 2010-03-21
comments: false
tags:
 - JSF
---

Para borrar un componente de una vista JSF:

{% highlight java %}
myUiComponent.getParent().getChildren().remove(myUiComponent);
myUiComponent.setParent(null);
{% endhighlight %}

Como advierten el [API de JSF](http://java.sun.com/javaee/javaserverfaces/1.2/docs/api/javax/faces/component/UIComponent.html#getChildren%28%29):

>Whenever an existing child component is removed, the parent property of the child must be set to null.
