---
layout: docs
title: Visibility
description: Control the visibility of elements, without modifying their display, with visibility utilities.
group: utilities
---

Set the `visibility` of elements with our visibility utilities. These utility classes do not modify the `display` value at all and do not affect layout – `.invisible` elements still take up space in the page.

{{% callout warning %}}
Elements with the `.invisible` class will be hidden *both* visually and for assistive technology/screen reader users.
{{% /callout %}}

Apply `.visible` or `.invisible` as needed.

{{< highlight html >}}
<div class="visible">...</div>
<div class="invisible">...</div>
{{< /highlight >}}

{{< highlight scss >}}
// Class
.visible {
  visibility: visible !important;
}
.invisible {
  visibility: hidden !important;
}
{{< /highlight >}}
