---
layout: page
title: "Function Contains"
subtitle: "fn:contains()"
category: fn
date: 2014-05-30
order: 1
---



```jstl
fn:contains(string, 'test')
```


```jstl
<c:set var="string" value="this is the awesome test string"/>

<c:if test="${fn:contains(string, 'awesome')}">
    <div>Awesome output.</div>
</c:if>
```
