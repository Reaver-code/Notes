# CSS Selectors

CSS selectors are used to target HTML elements for styling. They are essential for applying styles effectively in web development. Below is a detailed guide to CSS selectors:

---

## 1. **Basic Selectors**
### Universal Selector (`*`)
- Selects all elements on the page.
```css
* {
  margin: 0;
  padding: 0;
}

### Type Selector (Element Selector)
- Targets elements by their tag name.
```css
h1 {
  color: blue;
}
```

### Class Selector (`.`)
- Targets elements with a specific class.
```css
.intro {
  font-size: 16px;
}
```

### ID Selector (`#`)
- Targets a single element with a specific ID.
```css
#header {
  background-color: gray;
}
```

---

## 2. **Group Selectors**
- Apply the same styles to multiple selectors.
```css
h1, h2, h3 {
  font-family: Arial, sans-serif;
}
```

---

## 3. **Combinators**

### Descendant Selector (Space)
- Selects elements that are descendants of a specified element.
```css
div p {
  color: red;
}
```

### Child Selector (`>`)
- Selects direct child elements only.
```css
ul > li {
  list-style: none;
}
```

### Adjacent Sibling Selector (`+`)
- Selects the first sibling immediately after a specified element.
```css
h1 + p {
  margin-top: 0;
}
```

### General Sibling Selector (`~`)
- Selects all siblings after a specified element.
```css
h1 ~ p {
  color: gray;
}
```

---

## 4. **Attribute Selectors**
- Target elements based on their attributes.

### Presence Attribute Selector
- Selects elements with a specific attribute.
```css
[required] {
  border: 1px solid red;
}
```

### Value Attribute Selectors
- `[attr=value]`: Matches elements with an exact attribute value.
```css
[type="text"] {
  width: 100px;
}
```
- `[attr~=value]`: Matches elements with a space-separated list of values containing the value.
```css
[class~="highlight"] {
  background-color: yellow;
}
```
- `[attr|=value]`: Matches elements with a value that starts with the specified value (useful for languages).
```css
[lang|="en"] {
  font-style: italic;
}
```
- `[attr^=value]`: Matches elements with a value starting with the specified value.
```css
[href^="https"] {
  color: green;
}
```
- `[attr$=value]`: Matches elements with a value ending with the specified value.
```css
[href$=".pdf"] {
  text-decoration: underline;
}
```
- `[attr*=value]`: Matches elements with a value containing the specified value.
```css
[title*="important"] {
  font-weight: bold;
}
```

---

## 5. **Pseudo-Classes**
- Define a special state of an element.

### Structural Pseudo-Classes
- `:first-child`: Selects the first child of an element.
```css
p:first-child {
  font-weight: bold;
}
```
- `:last-child`: Selects the last child of an element.
```css
p:last-child {
  font-style: italic;
}
```
- `:nth-child(n)`: Selects the nth child of an element.
```css
li:nth-child(2) {
  color: blue;
}
```
- `:nth-last-child(n)`: Selects the nth child from the end.
```css
li:nth-last-child(1) {
  font-size: larger;
}
```
- `:only-child`: Selects an element that is the only child of its parent.
```css
p:only-child {
  text-align: center;
}
```

### UI Pseudo-Classes
- `:hover`: Selects elements when hovered.
```css
a:hover {
  text-decoration: underline;
}
```
- `:focus`: Selects elements when focused.
```css
input:focus {
  outline: 2px solid blue;
}
```
- `:disabled`: Selects disabled form elements.
```css
button:disabled {
  opacity: 0.5;
}
```

---

## 6. **Pseudo-Elements**
- Select and style parts of elements.

### `::before` and `::after`
- Insert content before or after an element's actual content.
```css
p::before {
  content: "Note: ";
  font-weight: bold;
}
```
```css
p::after {
  content: " [Read more]";
  color: blue;
}
```

### `::first-line`
- Styles the first line of text.
```css
p::first-line {
  font-size: larger;
}
```

### `::first-letter`
- Styles the first letter of text.
```css
p::first-letter {
  font-size: 2em;
  color: red;
}
```

---

## 7. **Specificity**
- The order of applying styles is determined by specificity and importance:
  - Inline styles (e.g., `style="color: red;"`) > IDs > Classes/Attributes > Elements.
  - Universal selectors and inherited styles have the lowest specificity.

```css
/* Example of specificity */
#unique {
  color: red; /* ID selector */
}
.warning {
  color: orange; /* Class selector */
}
div {
  color: blue; /* Element selector */
}
```

---
## 8. **Best Practices**
- Use classes for reusable styles.
- Avoid over-reliance on ID selectors to keep styles scalable.
- Group selectors to reduce redundancy.
- Use pseudo-classes and pseudo-elements to enhance user experience.

---
