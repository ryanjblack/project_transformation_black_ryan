# Ryan Black Project Transformation Homework

[Link to my Repo!](https://github.com/ryanjblack/project_transformation_black_ryan)

## Resources

Stuff I used on this project:

- [Boilerplate](https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css#L107-L169) to hide items in CSS (for structure)

Otherwise :
> “I did not use any resources outside of the lectures and my notes on this assignment."

## Deductions

> I reviewed the list of deductions for this project and in the syllabus.

## Comments

Git issues? Super old lectures (did he say "Iphone 4?!")? More links and resources to scour than hours in a day? Like Tim Gunn would say:

> Make it work

This assignment was like a mid-week workout. Longer than you'd expect, but ultimately all worth it by the end. I appreciated the opportunity to remake an old site, since so many websites look like this today - my employer was using divs for everything until just last year! Pacing the project changes into git was certainly a chore, and I had to restart a few times after encountering too many issues with branching (I ended up following how Richard did his transformation all on the master). If I had the opportunity to do this as a real-world experience and in a group I would certainly make the branches work, but for my purposes of having to check, then re-check my css and html made swapping a bit of a nightmare. I know if I had to do this again or in an exercise I would probably write out all of my plans for action on a notepad first, make some changes and then revisit. 

README Initial Update

Issues Solved:

Encountered an issue with the cloned stylelintrc file on line 37:

The following rule seems to be depreciated with the latest versions of the stylelint package:

>    "rule-non-nested-empty-line-before": ["always", { "except": ["after-single-line-comment"] }],

Updating to the following rule instead removed errors:

>    "rule-empty-line-before": ["always", { "except": ["after-single-line-comment"] }],

Found the updated rule via [this message](https://github.com/alienlebarge/stylelint-config/issues/19)
