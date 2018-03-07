What happens to the layout when you resize the screen to less than 550 px. How do you think that works?

Several of the elements switch from being columns to stacking on top of one another, some of the images resize.

Skeleton uses media queries and a fixed width threshold at which to change the behaviour of the columns, once this size
is hit the columns go from a fixed percentage width of their container element to being full width.