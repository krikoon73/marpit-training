---
marp: true
author: cc
theme: default
class: invert
#backgroundImage: #bdc3c7;  /* fallback for old browsers */
#backgroundImage: -webkit-linear-gradient(to right, #2c3e50, #bdc3c7);  /* Chrome 10-25, Safari 5.1-6 */
#backgroundImage: linear-gradient(to right, #2c3e50, #bdc3c7); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
backgroundImage: "linear-gradient(to bottom, #004643, #001e1d)"
paginate: true

---

# How to build marp slides

<!--_paginate: false
-->

---
# My First Slide

Hello World!

![bg](img/BuildingIPnetworksforgenerativeAIapplications.jpg)

---

# Use Case for Marp

- Repeatable way
- Integrate slide with some repository
- Sharing

Marp is not the only framework to build slides!

# How to change Theme

Nice and dark. Emoji => :blush:

``` markdown
---
Test code block
```

---

# To get free pictures

![bg right](img/pexels-aidan-roof-2449605.jpg)

Use:

- [Pexel](https://www.pexels.com/)
- [Unplash](https://unsplash.com)

How to work with images:

- [image syntax](https://marpit.marp.app/image-symtax)

If you can - add a reference to the author or collection.

---

![bg blur:2px](img/pexels-aidan-roof-2449605.jpg)
![bg opacity:.8](img/pexels-aidan-roof-2449605.jpg)
![bg sepia](img/pexels-aidan-roof-2449605.jpg)

---

# More Marp Themes

Marp community themes:

- [Dracula](https://draculatheme.com//marp)
- [Beam](https://rnd195.github.io/marp-community-themes/theme/beam.html)
- [Marpstyle](https://github.com/cunhapaulo/marpstyle)

---

# Using community themes

- Add css from some community repos
- Add foloowing VSCode settings:

```json
"markdown.marp.themes": [
        "./themes/dracula.css",
        "./themes/einstein.css"
    ]
```

- Use theme: `theme: <theme-name>`
- Update the workflow: `--theme ./temes/dracula.css ... etc.`

---

# Using gradient background

Where to find gradients and colors:

- [Uigradients](https://uigradients.com)
- [HappyHues](https://happyhues.co)

```yaml
backgroundImage: ""
```

---

# How to use animated images

- This looks amazing on a starting page

```markdown
![bg right fit](https://github.com/srl-labs/containerlab/raw/main/docs/images/containerlab_export_white_ink.svg?sanitize=true)
```

![bg right fit](https://github.com/srl-labs/containerlab/raw/main/docs/images/containerlab_export_white_ink.svg?sanitize=true)

---

# Using list

- item1
- item2

---

# Animated list

- Some item
  - subitem

* This will be hidden at first

```markdown
- Some item
  - subitem

* This will be hidden at first
```

---

# Paginate

```markdown
paginate: true

+ on specific page

<!--_paginate: false -->
```

---

# Footer

```markdown
<!-- footer: 'April 2024'-->
```

<!--
footer: 'April 2024'-->

# Add image as Footer

```markdown
<!-- Add footer starting from this slide -->
<!--
footer: '![h:20](https://www.arista.com/assets/images/logo/Arista_Logo.png)'
-->
```
<!-- Add footer starting from this slide -->
<!--
footer: '![h:20](https://www.arista.com/assets/images/logo/Arista_Logo.png)'
-->

