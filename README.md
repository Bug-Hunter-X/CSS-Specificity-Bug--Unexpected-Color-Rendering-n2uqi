# CSS Specificity Bug

This repository demonstrates a common CSS specificity issue that leads to unexpected styling results.  The problem arises from the conflicting styles applied to a paragraph element nested within a div. Understanding and resolving CSS specificity is crucial for creating predictable and maintainable stylesheets. 

## Bug Description:

The provided CSS includes styles that conflict due to specificity.  The expected behavior may not occur because of the order and specificity of the selectors. 

## Solution:

The solution involves carefully adjusting the CSS to ensure that the desired style is applied correctly, understanding selector specificity rules, and potentially using the `!important` flag (though this is generally discouraged). 