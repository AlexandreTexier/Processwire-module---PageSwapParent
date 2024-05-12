# Page swap parent
A module for [ProcessWire](https://processwire.com/) CMF/CMS that allows you to move pages having specific templates between two predefined parent pages depending on a toggle field value. 
The toggle field is automaticaly added to selected templates with default values that you can customize at your will.
The module was first intended to be a way of easily handling *current* and *archived* pages.

This module requires 3 elements :
- A list of templates that can be parent swapped
- A main parent page
- A secondary parent page

Be sure that the two parent pages can have pages with selected template(s) as children. And be sure that the movable pages can be child of the two parent pages.