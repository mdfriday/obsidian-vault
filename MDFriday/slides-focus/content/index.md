---
title: "MDFriday Slides"
description: "A MDFriday theme for creating presentations with Markdown."
theme: "dracula"
# themes: focus, beige, black, black-contrast, blood, league, moon, night, serif, simple, sky, solarized
#         robot, sunblind, white, white-contrast, verbatim, dracula
---

{{< cover logo="logo.svg" title="MDFriday Slides" subtitle="A MDFriday theme for creating presentations with Markdown." />}}

---

{{% content title="Title" subtitle="Something to talk" decoration="minimal" %}}

- This is the content of the slide.
- You can write bullet points.
- You can even write **bold** or _italic_ text.
- You can include [links](https://mdfriday.com) as well.

{{% /content %}}

---

{{% content title="Image" subtitle="Something to talk" decoration="geometric" %}}

![Preview](https://picsum.photos/600/300)

{{% /content %}}

---

{{< content title="Column" subtitle="Something to talk" decoration="circles" >}}
{{< cols >}}

{{% col %}}
### Block 1
- project item 1
- project item 2
- project item 3
{{% /col %}}

{{% col %}}
### Block 2
- project item A
- project item B
- project item C
{{% /col %}}

{{< /cols >}}
{{< /content >}}

---

{{< content title="Column" subtitle="Something to talk" decoration="lines" >}}
{{< cols >}}
{{% col %}}
![Preview](https://picsum.photos/300/300)
{{% /col %}}

{{% col %}}
- The picture on the left is just a placeholder.
- You can replace it with any image you like.
- Feel free to customize the content on the right.
{{% /col %}}
{{< /cols >}}
{{< /content >}}

---


{{% content title="Slide" decoration="corners" %}}

Use this shortcode when you need to customize slide attributes like id, class, background color and transition.

{{% /content %}}

---

{{< slide transition="zoom" transition-speed="fast" >}}
{{% content title="Transition" decoration="dynamic" %}}
Did you notice? This slide has a fast zoom transition
{{% /content %}}
{{< /slide >}}

---

{{< slide background-color="#FF4081" >}}
{{% content title="Background Color" decoration="dynamic" %}}

This slide has a different background color.

{{% /content %}}
{{< /slide >}}

---

{{< slide background-image="images/bg.jpg" background-color="#000000" >}}
{{% content title="Background Image" decoration="dynamic" %}}

This slide has a background image.

<br/><br/><br/><br/>
<br/><br/><br/><br/>
<br/><br/><br/><br/>

{{% /content %}}
{{< /slide >}}

---

{{< cover title="Math" align="center" />}}

---

{{% content title="Math" subtitle="examples" decoration="dynamic" %}}

Block math:

{{< katex display=true >}}
\varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
{{< /katex >}}

Inline math:

This is an inline polynomial: {{< katex >}}5x^2 + 2y -7{{< /katex >}}.

{{% /content %}}

---

{{% content title="Mermaid" subtitle="Chart Example" decoration="dynamic" %}}

Here is a simple Mermaid chart example:

{{< mermaid >}}
graph LR
A --> B
B --> C
{{< /mermaid >}}

{{% /content %}}

---

{{< cover title="Thanks" align="center" />}}