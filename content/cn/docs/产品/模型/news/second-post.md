---
title: Second  post
date: 2018-10-06
isCJKLanguage: true
mermaid: true
description: >
  A short lead description about this content page. Text here can also be
  **bold** or _italic_ and can even be split over multiple paragraphs.
---

<script type="module"> import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.esm.min.mjs'; mermaid.initialize({ startOnLoad: true }); </script> 

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```



```mermaid
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, 2014-01-01, 30d
    Another task     :after a1  , 20d
    section Another
    Task in sec      :2014-01-12  , 12d
    another task      : 24d
```

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```
