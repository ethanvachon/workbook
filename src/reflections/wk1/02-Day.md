# Day Two Reflection
__12-1-20__

## What is a Pseudo-Class and what are some of the most common ones you think you will use
A pseudo-class is a css selector with an added keyword to indicate a scenario. An example would be button:hover, which is only applied when the mouse is hovering over a button. :hover is common and very useful for making the page more responsive and just feel better in general. Another useful class is :visited which keeps a history of navigation, or :first-child which applies only to the first child of a parent element.

## What is Specificity and how might you use it to your benefit?
Specificity is the process in which css decides what rules have priority over others. If multiple rules are giving an element conflicting values, the rule with higher specificity will be applied. It's very useful if for example all p tags are turned red, but you want p tags with a certain class or id to be green. Writing a rule targeting that class/id will override the general rule for all p tags. 

## What problems do you think you could run into if you over-utilized the !important feature?
Important tags give a rule a specificity that cannot be overwritten, unless another !important tag is used. Liberally using the important tag isn't needed, as generally you can get the same effect without using it if one is familiar with other ways to influence specificity. If the important tag needs to be overwritten, you can only use another important tag, which can easily get out of hand.
