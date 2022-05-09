# Style Stage

```json
{
  "title": "Atomic Clockwork",
  "author": "Eric Brown"
}
```

## Description

This page, or at least its stylesheet, is a submission to [Style Stage](https://stylestage.dev), maintained by Stephanie Eckles.

I am a web development student in IDMX 268 at Raritan Valley Community College, and Style Stage is our final project this semester. My design: "Atomic Clockwork" is \[loosely\] inspired by code editor syntax highlighting and pre-markdown README files.

### Some features that I included:

- Fluid font sizes

- Two variable fonts

- Animated hover effects

- SVG background patterns

- Custom properties

- Styled lists with custom markers

- A multi-column grid layout at larger screen sizes

- An ENORMOUS header

### Other Notes

**Note on a false aXe error**: aXe cannot determine the background color of many elements due to background images. The background SVG images are almost completely transparent, and the actual background color shows through them. When they are temporarily removed, aXe returns a report with no issues.

**Skip Link**: The skip link is hidden by default, but can be revealed by tabbing to it.

**Animation**: All animations are contained within a 'prefers-reduced-motion:no-preference' media query, and animations did not trigger when system preference was set to reduced motion during testing.

## Resources

[HTML Content from Style Stage by Stephanie Eckles](https://stylestage.dev)

[Build Excellent Websites by Andy Bell](https://buildexcellentwebsit.es/)

[Code for Bell's Build Excellent Websites (the source for the Fluid CSS code linked above) ](https://glitch.com/edit/#!/build-excellent-websites)

[Sanitize.css (My chosen CSS normalize library)](https://github.com/csstools/sanitize.css)

[DequeUniversity.com(How I hid the skip link)](https://dequeuniversity.com/rules/axe/4.3/skip-link)

[Page header and footer background: "Circuit Board"](https://heropatterns.com/)

[Body Background:"Floating Cogs"](https://heropatterns.com/)
