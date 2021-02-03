#Daily Journal

##Cool Site link https://github.com/JohnVWebb/cool-site

##Building Blocks of Web Development>CSS

###Questions

1. What is a Pseudo-Class and what are some of the most common ones you think you will use

Pseudo classes are used to select elements in a particular state. They are also more flexible by allowing us to select elements by their relation to other elements rather than a specific one. This can be useful, for example, when you have a style applied to the first paragraph of a page. If another paragraph is added above that then the style won't be applied to the new paragraph unless manually edited. A pseudo class can be used to select the child of a parent element and if a new child is added in the originals place then the style would apply to the new paragraph without additional code.
:first-child :last-child :only-child :nth-child() :first-of-type :only-of-type :last-of-type are some that I believe will be pretty common. 

2. What is Specificity and how might you use it to your benefit?

Specificity is built into CSS to create a hierarchy to govern which rules are applied to the elements and values we create. We can change multiple elements at the same time if they have the same specificity. We can also be more specific about which element to alter even if there are multiples of the same element.


3. What problems do you think you could run into if you over-utilized the !important

The !important property overwrites any other styling. If we use it on elements that don't require it we can run into issues of not being able to use css to overwrite and style that specific element.

