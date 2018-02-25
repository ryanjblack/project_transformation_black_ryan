# Ryan Black Project Transformation Homework

[Link to my Repo!](https://github.com/ryanjblack/project_transformation_black_ryan)

## Resources

Stuff I used on this project:

- [LinkName](url)

Otherwise :
> “I did not use any resources outside of the lectures and my notes on this assignment."

## Deductions

> I reviewed the list of deductions for this project and in the syllabus.

## Comments

Git issues? Outdated lectures? More links and resources to scour than hours in a day? Like Tim Gunn would say:

> Make it work

README Initial Update

Issues Solved:

Encountered an issue with the cloned stylelintrc file on line 37:

The following rule seems to be depreciated with the latest versions of the stylelint package:

>    "rule-non-nested-empty-line-before": ["always", { "except": ["after-single-line-comment"] }],

Updating to the following rule instead removed errors:

>    "rule-empty-line-before": ["always", { "except": ["after-single-line-comment"] }],
