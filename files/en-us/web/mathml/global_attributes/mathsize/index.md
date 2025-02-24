---
title: mathsize
slug: Web/MathML/Global_attributes/mathsize
browser-compat: mathml.global_attributes.mathsize
---

{{QuickLinksWithSubPages("/en-us/docs/Web/MathML/Global_attributes")}}{{Deprecated_Header}}

The **`mathsize`** [global attribute](/en-US/docs/Web/MathML/Global_attributes) sets the [font-size](/en-US/docs/Web/CSS/font-size) of a MathML element.

> **Note:** Use CSS for styling MathML whenever possible. The `mathsize` attribute should only be included for applications that are not CSS-aware and will be overridden by the CSS `font-size` property, if set.

## Syntax

```html-nolint
<!-- <length> values -->
<math mathsize="12px">
<math mathsize="0.8em">

<!-- <percentage> values -->
<math mathsize="80%">
```

### Values

- {{cssxref("&lt;length&gt;")}}

  - : A positive {{cssxref("&lt;length&gt;")}} value. For most font-relative units (such as `em` and `ex`), the font size is relative to the parent element's font size.

- {{cssxref("&lt;percentage&gt;")}}
  - : A positive {{cssxref("&lt;percentage&gt;")}} value, relative to the parent element's font size.

> **Note:** Some browsers may also accept [legacy MathML lengths](/en-US/docs/Web/MathML/Attribute/Values#legacy_mathml_lengths).

## Specifications

{{Specifications}}

- In MathML 3 and earlier versions, keywords `small`, `normal`, and `big` as
  well as the MathML3-specific syntax for lengths was supported.
  Since MathML Core, the syntax matches CSS
  {{cssxref("&lt;length-percentage&gt;")}} values.

- This attribute was designed for MathML applications that are not CSS-aware.
  Since MathML Core, the use of equivalent CSS is recommended instead.

## Browser compatibility

{{Compat}}

## See also

- All [global attributes](/en-US/docs/Web/MathML/Global_attributes).
- {{cssxref("font-size")}}
