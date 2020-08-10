# A11y checklist

## Text alternatives
* Add a text alternative to your images.
* If the content is video or audio, add a short description of the topic.
* Make sure that decorative images have empty alt attribute values.
* Is there a plain text which lists points on the map or sections of a flowchart? Describe all visible information. This       includes graph axes, data points and labels, and the overall point the graphic is communicating.
* For images containing text, make sure the alt description includes the image's text.

## Semantic markup
* Break up content with subheadings for new sections.
* Mark those headings with HTML header tags.
* Use the correct HTML for all structural elements.
* Use valid HTML everywhere else.
* Use clear labels on forms.
* Ensure that media controls use appropriate markup.

## Navigation
* Use `role="navigation"` for navigation
* Unplug your mouse and verify that you can use the `Tab` key to navigate to every part of your website and use every function, including search boxes and forms – make sure each page has a sensible focus order.
* Make the keyboard focus visible on all elements (menu items, form fields, links, etc…).
* Use breadcrumbs to help with navigation. Show the sequence a user is following and where they are in that sequence. For example: You are here: `Home > Fish > Bass`
* Add a sitemap page to your website
* Remove `tabindex` attribute values that aren't either 0 or -1.
* Avoid using the `autofocus` attribute.
* Remove the ability to focus on elements that are not presently meant to be discoverable.
* Provide a skip link and make sure that it is visible when focused.

## Form
* All inputs in a form are associated with a corresponding label element.
* Does your form contain multiple sections of related inputs? Use fieldset to group them, and legend to provide a label for what this section is for.
* Inputs use autocomplete where appropriate.
* Associate input error messaging with the input it corresponds to.
  Techniques such as using aria-describedby allow people who use assistive technology to more easily understand the       difference between the input and the error message associated with it.

## Form errors
* If a form requires input in a certain format, show and describe the required format.
* If a mandatory field is empty, highlight the field and explain what’s required.
* Build forms to be forgiving, accepting variations on the formats you prefer.
* Don’t ask for too much information, just what you need.
* Be specific. Use clear, concise instruction and form field labels.
* Highlight mistakes in forms with colours and symbols.
* Don’t clear a form if a user makes a mistake. Save the information and allow the user to edit their error and continue.
* Provide extra help by giving your contact details on all pages (the header or footer are great) and especially near forms.
* If the error is in the format of the input, the suggestion shows the correct format (for example, ‘The date must be in the form DD/MM/YYYY’).

## Content
* Give each page on your website a unique and descriptive title. Use pattern `Page name – Page description – Website name`
* Text can be resized to 200% without loss of content or function
* If you must use a pop-up, make sure that keyboard focus is on the window-closing ‘X’ icon in the corner that closes the pop-up. This means keyboard users can close the new window. When they do close it, return focus to the place on the page they were at before the pop-up appeared.
* Use `lang` attribute on `html` element 
* Remove title attribute tooltips.
* Use the caption element to provide a title for the table.
* Depending on how complex your table is, you may also consider using scope="col" for column headers, scope="row" for row     header.

## SVG
* Make sure that svg elements include the code focusable="false" when they are the child element of a focusable element.
* Add `aria-hidden="true"` to svg that is decorative.
* Make sure that svg utilizing the use element has whitespace between the svg and use elements.
* Ensure that img elements with an svg source includes the role="img" attribute.
