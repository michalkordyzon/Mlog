---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
tags: ["example"]
categories: ["examples"]
ShowToc: true
cover:
  image: "/images/sample.jpg"   # change to your image path in /static/images/
  alt: "Cover image"
  caption: "Optional caption for the cover image."
  relative: false
math: true
---

## Introduction
This is a short intro paragraph for **{{ replace .Name "-" " " | title }}**.  
Replace it with your own 1–2 sentences to start the post.

---

## Example Image
![Sample image](/images/sample.jpg)

---

## Example Code
```python
def example():
    return "Hello, PaperMod!"
```
---

# Example math
example_math_inline: "$E = mc^2$"
example_math_block: "$$\\nabla \\cdot \\vec{E} = \\frac{\\rho}{\\varepsilon_0}$$"
---