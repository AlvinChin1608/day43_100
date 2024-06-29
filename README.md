# day43_100
I am currently engaged in a 100-day Python Bootcamp, which I am documenting and sharing my progress on GitHub. The boot camp is designed to progressively intensify, allowing me to deepen my understanding and proficiency in Python programming.

Additionally, I have chosen to include the beginner, intermediate and advanced in my documentation to provide a valuable reference for my future growth and development.

----------------

# What I Learned Today
Today, I deepened my understanding of CSS (Cascading Style Sheets) and how it can be used to style web pages effectively. Here’s a summary of the key concepts I covered:

## CSS Selectors
- __CSS Selectors:__ Selectors are patterns used to select the elements you want to style. I learned about different types of selectors including:
- __Element Selectors:__ Selects elements based on their tag name (e.g., p selects all &lt;p&gt; elements).
- __Class Selectors:__ Selects elements based on the class attribute (e.g., .classname selects all elements with class="classname").
- __ID Selectors:__ Selects a single element based on its ID attribute (e.g., #idname selects the element with id="idname").
- __Attribute Selectors:__ Selects elements based on the presence or value of an attribute (e.g., [type="text"] selects all &lt;input&gt; elements with type="text").
  
## Inline CSS
- __Inline CSS:__ I learned that inline CSS is used to apply a unique style to a single HTML element. It is added directly within the style attribute of the element (e.g., &lt;p style="color: red;"&gt;This is a red paragraph.&lt;/p&gt;). While it’s useful for quick, individual styles, it is generally not recommended for large projects due to lack of reusability.

## Internal CSS
__Internal CSS:__ This method involves embedding CSS within the &lt;style&gt; tag in the &lt;head&gt; section of an HTML document. It is useful for styling a single document and keeps the CSS separate from the HTML content (e.g.,

```python
<head>
  <style>
    p { color: blue; }
  </style>
</head>
```
).

## External CSS
- __External CSS:__ I learned that external CSS involves linking to an external .css file from within the HTML document. This method is ideal for applying styles across multiple pages. The external CSS file is linked using the &lt;link&gt; tag in the &lt;head&gt; section (e.g.,
```python
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```
). This approach promotes reusability and separation of concerns.
