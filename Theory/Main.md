---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
marp: true
---


# **Marp**

Markdown Presentation Ecosystem

![](https://marp.app/assets/marp.svg)

---

# How to write slides

Example python code

```python
def controls(delta):
    aux = set()
    for path in delta:
        if path[0] not in aux:
            aux.add(path[0])
    return aux
```