# ❗ Deprecation Notice
We want to express our sincere gratitude for your support and contributions to this open source project. As we are no longer using this technology internally, we have come to the decision to archive this repository. While we won't be providing further updates or support, the existing code and resources will remain accessible for your reference. We encourage anyone interested to fork the repository and continue the project's legacy independently. Thank you for being a part of this journey and for your patience and understanding.
Airbnb CSS / Sass Styleguide
## A mostly reasonable approach to CSS and Sass

Terminology
Rule declaration
A “rule declaration” is the name given to a selector (or a group of selectors) with an accompanying group of properties. Here's an example:

.listing {
  font-size: 18px;
  line-height: 1.2;
}
Selectors
In a rule declaration, “selectors” are the bits that determine which elements in the DOM tree will be styled by the defined properties. Selectors can match HTML elements, as well as an element's class, ID, or any of its attributes. Here are some examples of selectors:

.my-element-class {
  /* ... */
}

[aria-hidden] {
  /* ... */
}
Properties
Finally, properties are what give the selected elements of a rule declaration their style. Properties are key-value pairs, and a rule declaration can contain one or more property declarations. Property declarations look like this:

/* some selector */ {
  background: #f1f1f1;
  color: #333;
}
