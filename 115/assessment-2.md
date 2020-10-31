## In the next few weeks, we'll be learning how professional developers work on larger projects. What are you most looking forward to in this section?

- I'm most looking forward to learning about how the development process works when working as a team vs. working alone on a project. Are there some things that
others in a group do better than the rest? Do they divide the work up between groups? Are there any drawbacks of developing a large project in groups? Advantages?

## Briefly explain event propogation and bubbling using an example of two nested HTML elements.

- Event propogation is a term used to describe bubbling and event capturing. 
<header onKeypress="alert('this is the header')">header</header>
<h1 onKeypress="alert('this is the h1')">h1</h1>
h1 and header being the nested elements. The first "h1" will run first then its parent. 


## You learned to use addEventListener on a DOM node to listen for a type of event and create a function to handle that event.
When the event happens, that function is called with an Event Object that gives you more information about the event.
Choose two different event types and explain two properties of each that are unique to that event. Use your MDN reference for help.

1. visibilitychange is shown  the bottom of the MDN event references page and starts playing a music track when the document becomes visible, then stops the music when the document isnt visible any longer.

2. Wow, this one "devicemotion" helps determine if the device loading it is recieving any type of force of motion. In it's function it uses "event.accelerationIncludingGravity" woah.

