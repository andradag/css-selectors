# css-selectors
using an attribute selector to select all elements with a specific characteristic and add a follow-up content using : : after


# Adding an icon next to every `<a>` element that has a link to a downloadable CSS file in its `href` attribute.

- Targeting a file type by its file extension (i.e., `.css`, `.html`, `.md`, etc.)

- Using pseudo-elements to accomplish this task.


'''
/* Use an attribute selector to select all <a> elements that have an href value that ends with '.css' */
a[href$='.css']::after {
  content: '📝';
  display: inline-block;
  margin-left: 3px;
}
'''
