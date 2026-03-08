3/8 HW 2
**Flex‑direction controls the arrangement of items in a container.** `flex-direction: row` **arranges items horizontally, and** `flex-direction: column` **arranges them vertically**

**Relative units allow elements to scale dynamically, which makes your layout more responsive across different screen sizes. They also improve accessibility and consistency.** `vh` **and** `vw` **resize elements based on the viewport.** `rem` **is best for font sizes and margins, while** `em` **works well for padding and margins within components.** `%`**,** `vw`**, and** `vh` **are ideal for setting layout widths, heights, and overall responsiveness.**

I was having trouble seeing the changes applied to my site with the media queries. I asked AI to list all the possible reasons why this issue was happening, it told me it was either a cache issue, or a file path issue. Finally they told me to add this tag to my html file: <meta *name*="viewport" *content*="width=device-width, initial-scale=1.0">, while allowed me to see the changes and make my website responsive.
