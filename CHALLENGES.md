# Challenges

-   I researched and learned about **responsiveness**, and I noticed three key points:

    1. Avoid using fixed widths.
    2. Use proper units for fonts and padding so they adjust according to screen size.
    3. Prefer padding over margin for spacing.

-   Instead of mixing multiple units, I chose one unit that made the most sense to me: `rem`.  
    **1rem = 16px** — this concept really clicked for me.

-   I realized that combining **Flexbox** and **Grid layout** is a powerful approach.

-   Applying Grid layout was a big step and also the part I struggled with the most since I was new to the concept.  
    I managed to place the cards in a grid, but I made a mistake by adding a fixed row for tablet mode, which caused issues later.

-   The most important learning was when I tried to make it responsive for tablets.  
    At first, the cards were shrinking instead of wrapping.  
    Later, I realized that I needed to remove the fixed row. Once I did that, the cards adjusted properly.

-   Initially, I thought applying **media queries** would be difficult, but once I started, I found them quite easy to work with.

-   Another mistake I made was applying horizontal margins (left and right) on the parent container.  
    This prevented the cards from adjusting properly on smaller screens.  
    After removing the margins and keeping only padding, the layout worked as expected.

---

## Final Thoughts

I’ve tried to explain all the challenges I faced while building this project.  
This was my **first responsive design**, and completing it gave me a real sense of accomplishment.
