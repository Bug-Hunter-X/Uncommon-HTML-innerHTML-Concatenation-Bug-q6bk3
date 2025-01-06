# Uncommon HTML Bug: InnerHTML Concatenation

This repository demonstrates an uncommon bug related to innerHTML manipulation in HTML.  Incorrect concatenation of strings when setting the innerHTML property can lead to unexpected or erroneous results. The bug showcases this issue and provides a corrected solution.

## Bug Description
When using string concatenation to build up HTML content before assigning it to innerHTML, omitting the necessary spaces between HTML tags can lead to unexpected behaviour or HTML parsing errors. The browser may not render the HTML correctly, or it might fail completely. This is particularly noticeable when working with multiple HTML elements within a string.

## Solution
The solution involves creating a properly formatted HTML string without unnecessary concatenation that results in the incorrect number of tags. 
