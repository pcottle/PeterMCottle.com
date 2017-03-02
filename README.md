# Peter M Cottle.com

[PeterMCottle.com](http://petermcottle.com) is my personal website as well as a proof-of-concept of a new browsing interface.

<img src="http://pcottle.github.io/PeterMCottle.com/site_pic.png" />

## Idea

File system hierarchies are logical ways to organize and display a vast amount of information. Why not use the same approach to presenting static content on the web?

This browsing interface uses the same approach -- horizontal scrolling displays different options and relevant data to the current level in the tree. "Drilling down" delves deeper into that topic, and bubbling back up returns to a higher-level summary of who I am.

## Inspiration

Hakim El Hattab created Reveal.JS, a presentation framework based on CSS3D. The concept he presented was really cool but only supported grid-like browsing schemes. I wanted to build a 3D browsing interface that was tree-structured instead, so I started fresh (with the exception of the bezier values for the animation, which are too perfect to pass up).

This was my second Javascript project so the code is really rough. It still accomplishes a relatively unique / novel interface though; I like being able to browse static content with just the arrow keys on my keyboard. I think in this sense it appeals to power-users and other programmers who might be viewing the site. It unfortunately doesn't work in IE6, but that's a loss I'm willing to accept.

