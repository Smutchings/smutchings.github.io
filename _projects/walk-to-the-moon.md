---
name: Walk To The Moon
tools: [Sketch, Prototyping, Flinto]
image: /img/walk-to-the-moon.png
description: A walking app bringing together a love of space and a community-driven approach.
---

# Walk To The Moon

> Space is big. You just won't believe how vastly, hugely, mind- bogglingly big it is. I mean, you may think it's a long way down the road to the chemist's, but that's just peanuts to space.

As Douglas Adams said, Space is inordinately huge. So, how do you design a walking app based around space without making the accomplishments feel futile against the grander background of space?

## Can you walk to the Moon?
Before working on any design or further thoughts for the Walk To The Moon application, the first step was to understand if it is even possible for a human being, in their lifetime, to walk to the Moon. If it is, then the app at least has an accomplishable goal for the individual. If it isn't, then the app would just be a source of frustration, and wouldn't deserve to exist. So, I start with the maths.

### The Maths
Due to the elliptical nature of orbits, the distance between the Earth and the Moon varies based on their relative positions in their orbits. When they are closest together, they are considered to be "at perigee". When they are most distance from each other, they are considered "at apogee".

```
Distance to the Moon
At perigee: 356,500km 
At apogee: 406,700km
Mean: 384,402km
```

For the sake of Walk to the Moon, I'll be using the perigee distance between the Earth and the Moon, as this allows for the greatest chance of someone accomplishing the walk. But, even at perigee is it possible for someone to walk to the Moon? That depends on a few factors.

```
Human life expectancy: ~ 82 years in the developed world
Age at which a human can download the app: 13 (if not downloaded by parents)
Mean max time using the app: 69 years

Average walking speed: 4km/hour
Mean walking stance: 6km/day

Days taken to walk to the Moon at 6km/day:
356,600 / 6 = 59,433

In years: 162.7
```

This lead to a problem. Unless we find ways to drastically increase human life expectancy, the typical person is unable to walk to the moon in their lifetime. Instead, they're likely to only be able to get 25-40% of the way.

This means that only those who average 15km/day (observed in some Amish communities) would be able to achieve the goal. But, would the Amish use an app for that? 

## The Answer
Once the maths was clear, the answer was to look again at the stated point of the application, with the realisation of just how big space is, and consider what changes could be made.

For those who are very active, say those who do a 10k jog every day, on top of their normal walking, the Walk to the Moon application offers them an ambitious lifetime achievement - to have walked to the Moon.

For those who are more on the average, or more sedentary side, smaller stellar measurements could be used. For example, the first achievement could be walking the length of the Space Shuttle (an easily-achievable 37m), easing people into the app with a little dopamine hit, on top of the dopamine from walking. 

And for the vastness of space, there are communities. Because, whilst it would take a single person 160 or more years to reach the Moon, 160 people would make it there in about a year. That same group could be at Mars in 15 years. Get 1,000 people and you can be at Mars in about 2.5 years.

So, I decided that the app should be a community driven experience, as well as offering the individual goal of walking to the Moon.

### Bringing a Community Together, Privately
With anything I work on, I like to respect the rights of the human. Enshrined in those is the right to privacy, something that many community sites and applications overlook in their design.

By design, Walk to the Moon would collect only the necessary information required to perform its stated role. For the individual, a cumulative walking distance would be stored on the device, and used locally to calculate their distance towards the Moon and offer achievements. If the walker would like to share their achievements through a social network of their choice, they're free to do so by saving the medal to the photo library and sharing from there.

For the community goals, of walking increasingly further distances through space, the app would periodically send the distance walked (and only the distance walked) to a centralised server. This would then calculate the total distance travelled by the community and report it back to the devices taking part in the goal.

## Designing an Application
Once the purpose of the application was decided, it was time to bring pixels together to create a design for the app. This was done in Sketch 3 on a MacBook Air.

Initial designs of the app were inspired by the badge system used by the Boy Scouts and similar organisations around the world. In the centre of the view was a big number, showing the number of kilometres you had walked, and you would scroll up to see the achievements you had unlocked.

![We start our journey to the Moon with the initial design](/img/walk-to-the-moon/home.png)

I later decided that it was better to have the Moon present in this design, with it getting more visible as you get closer to your destination. Whilst not shown in these screenshots, the idea is that the moon would go from phase-to-phase as you approached it. Going from a total eclipse to a full moon.

![A later version showed the Moon as you walked towards it](/img/walk-to-the-moon/moon.png)

The community tab had a simple goal of showing the next target (with an image of it in the centre) as well as a progress bar showing the community's progress towards the goal. In this instance, the community are on their way to Mars.

![The community tab, as we walks towards Mars, the first community goal](/img/walk-to-the-moon/community.png)

## Creating a Prototype
Once the main screens of the application were designed, it was time to create a prototype. The original prototype was created using POP, but was then moved to Flinto to create a more functional prototype. A video of the Flinto prototype can be seen below, and the [POP prototype can be viewed online](https://marvelapp.com/2j99679).

![Video of the Origami Prototype](/img/walk-to-the-moon/prototype.mov)
