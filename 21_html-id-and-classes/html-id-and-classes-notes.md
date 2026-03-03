<!-- +++++++++++++++ HTML ID and Classes +++++++++++++++ -->
1. Id Attribute:
=> The id attribute gives a unique name to an HTML element.
=> It is declared with #.
=> Each id can be used only once in an HTML page.
=> ID cannot be repeated, and only one ID is allowed per element.
Example:- <h1 id="myHeader">Hello</h1> → styled by #myHeader { }

2. Class Attribute:
=> The class attribute gives a name to one or more HTML elements.
=> It is declared with a dot (.).
=> The same class can be used multiple times on a page.
=> An element can have multiple classes in one element.
Example:-
<h1 class="myHeader">Hello</h1>
<p class="myHeader">Welcome!</p> → styled by .myHeader { }

=> .para1 and .para2 have the same specificity because both are class selectors.
=> If both classes are on one element, the last CSS rule applied.
<p class="para1 para2">This has two classes</p>