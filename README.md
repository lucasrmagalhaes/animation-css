**CSS Transform**
- Changes the shape and position of the affected content without disrupting the normal document flow by modifying the coordinate space.

---

**CSS Transition**
- Allows changes in a property to take place over time.

---

**CSS Keyframe Animation**
- Defines an animation sequence of states within the @keyframes rule.

**Two Step CSS @keyframe Animation**
- Defining the animation keyframes in @keyframes rule.
- Assign the keyframes to an element.

**0% of "from" keyframe** is the start of the animation.

**100% or "to" keyframe** is the end of the animation.

---

**animation-delay**
- Specifies the amount of time to wait before beginning to perform the animation.

**animation-fill-mode**
- Lets you control what happens during delays before an animation starts actively playing, and/or what happens after an animation's duration has ended.

---

**animation-direction**
- Lets you control what order our keyframes are executed in.
- Values: normal, reverse, alternate and alternate-reverse.

---

**Easing**
- Easing is what describes the speed changes of your animation over the course of its duration.

**Three Options for animation-timing-function**
- Easing keywords
- The steps() function
- Custom cubic-bezier curves

**Keyword Easing Options**
- ease
- ease-in-out
- ease-in
- ease-out
- linear

[cubic-bezier](https://cubic-bezier.com/#.17,.67,.83,.67) <br />
[easings](https://easings.net/)

---

**steps()**
- Plays an animation back in a defined number of steps, pausing briefly at each, instead of smoothly interpolating between keyframes states.

---

**animation-play-state**
- Controls whether an animation is playing or paused.

---

**transform-origin**
- The point around which a transformation is applied.

---

**Tip**
- Look for distinct and complete shapes for the objects you want to animate.
- Name the layers and/or paths you'll be animating so it's easier to find them later.

---

**Different Tools Surface Different Options**
- We'll be covering the most common export options, but the export options vary from tool to tool.

**SVG Export Options**
- Presentation attributes or internal CSS?
- Linked or embedded images?
- Minifed file?

**Internal CSS or Presentation Attributes?**
- This one is up to personal preference.

**Linked or Embedded Images?**
- Linked images is the most flexible option. Embedding images in your SVG can greatly increase the file size.

**Minify the Exported File?**
- Working with a minified file for animation can be extremely difficult. Wait until your animation is complete to minify your SVG.

[SVGOMG](https://jakearchibald.github.io/svgomg/)

---

[GreenSock](https://greensock.com/)

---

**CSS Motion Path**
- With offset-path.

**offset-path**
- Specifies a path for an element to follow or be placed along.

**offset-distance**
- Specifies a position along an offset-path for an element to be placed.

**offset-rotate**
- Defines the orientatio and/or direction of an element as it is positioned along an offset-path.

---

**CSS Custom Properties**
- Also known as CSS variables; values that you can define and reuse within your CSS document.

**CSS Variables**
- Can be changed at runtime
- Follow the CSS cascade
- Can be easily accessed by JavaScript

**Where to Use CSS Variables**
- In your @keyfram definitions
- In the animation properties assignment