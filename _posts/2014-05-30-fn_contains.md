---
layout: page
title: Function Contains
subtitle: fn:contains
category: fmt
date: 2013-06-06 08:55:36 UTC
order: 1
---



```jsp
    fn:contains(string, 'test')
```


```jsp
    <c:set var="string" value="this is the awesome test string"/>

    <c:if test="${fn:contains(string, 'awesome')}">
        <div>Awesome output.</div>
    </c:if>
```
