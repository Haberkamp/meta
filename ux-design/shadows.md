# Shadows

Shadows were the one thing I really struggled to understand. But once I understood them, I was able to create much more interesting designs.

## Why use shadows?

You can use shadows to say: "this is more important than the other things". The bigger the shadows, the more important it is.

Moreover, they're a way to make a design more interesting. But this is just a preference in taste.

## How to create shadows?

First, you need to understand how shadows work. We have simple shadows and layered shadows.

### Simple shadows

```css
.my-element {
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
}
```

### Layered shadows

Some elements do not only have a single `box-shadow` property, but multiple ones.

There's a direct shadow, the one casted by the sun-light or your ceiling lights. Then there's the ambient shadow, the one casted by the indirect light.

The direct shadow is larger and softer. The ambient shadow is smaller and harder/darker.

<!-- prettier-ignore-start -->
```css
.my-element {
  box-shadow:
    0 10px 20px rgba(0, 0, 0, 0.15), /* direct shadow */
    0 3px 6px rgba(0, 0, 0, 0.1); /* ambient shadow */
}
```
<!-- prettier-ignore-end -->

One thing to note, when the element is is closer its background the ambient shadows is more visible. The further away the element is, the more the ambient shadows will be hidden.

### Experimenting with shadows

Those are not the only ways to create shadows. Here are some other ways to experiment:

- Use different colors
  - Grays
  - A different shade of your background color where the element sits on
- Reverse engineer shadows from other apps
  - Get a website you really like
  - Inspect an element with a shadow
  - Look at the shadows values, try to re-create them with CSS or in Figma

## Resources

- [Refactoring UI](https://www.refactoringui.com/)
- [Tips for Designing Better Drop Shadows in Figma for Developers & Designers](https://www.youtube.com/watch?v=gmC-IlDcqhM)
- [Design detail: Crafting better shadows for interaction](https://uxdesign.cc/design-detail-crafting-better-shadows-for-interaction-b94796a29664)
