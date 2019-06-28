---
name: Magic The Gathering Commander Overlay
tools: [HTML, CSS, Sketch, Firebase]
image: /img/MTGCO/hero.png
description: An interactive streaming overlay for Magic The Gathering.
---

# Magic: The Gathering Commander Overlay
At Elite Gaming, we started streaming Magic: The Gathering as a way to share our community with the world. In order to give the best viewing experience to our viewers, I created an interactive overlay that could be controlled by our players and show on the stream video for the viewers.

## The Design
The design of the overlay went through multiple iterations before coming to the design that is currently used. Initially, the design was highly influenced by the design language of Magic: The Gathering, but this evolved to something that was more neutral in design, so that it could be used for multiple game formats, but also so that we don't encounter issues with intellectual property.

![The original design, inspired by the design language of Magic: The Gathering](/img/MTGCO/gameDayOverlay.png)
The original design, inspired by the design language of Magic: The Gathering


![The updated design, using a four-colour interface inspired by video games](/img/MTGCO/newOverlay.png)
The updated design, using a four-colour interface inspired by video games

## The Technology
The overlay is created in HTML and CSS with a smattering of JavaScript. This is hosted on GitHub Pages, and the overlay is loaded into the streaming software (OBS) with a custom CSS property to make the background transparent.

On the back end, the database for the system is provided by Google Firebase. Requests from the admin page are sent to the database to update the information, and then this information is updated in real-time on the overlay displays.

![The admin panel running on an iPhone](/img/MTGCO/admin.jpeg)
The admin panel running on an iPhone

## The Result
Magic: The Gathering Commander Overlay has proved a success with both the players and viewers on our streams. It helps them see what's going on in the game, and has helped us with other events through slight adjustments and additions - such as a card display panel.

I've also had a couple of streamers ask to use the Overlay on their streams - both at a local and a national level. This would require additional work, so has not happened yet, but I plan to expand the system to work with this in the future.