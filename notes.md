
Aufteilung:

1. Motion (material guideline etc)
2. The transition-property on a CTA
3. Use-case: Navigation-Bar
4. Best practices:
	- Performance best practices
	- A11Y (accessibility )
	- Does "too much motion" exist?

Motion

Einstieg:
- hello everybody, my name is…
- Spot the differnece => motion
- material-design principles: https://material.io/design/motion/#principles
- We know what we want to try today, lets write it down=> write down the structure for today (CODE)

We already talked about the motion-part, so ist time to get to know to the transition property

The transition-property on a CTA

start with 2 examples: twitter https://twitter.com/home

- try rebuilding the twitter-button (CODE)
- add transition 
- every transition prop on its own (siehe unten)
- transition shorthand transition: <property> <duration> <timing-function> <delay>;
	

props:
- transition-propty => Set of animatable properties: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties
- transition-duration …
- transition-timing-function: 
	- linear 
	- easing https://easings.net/
	- steps(n, start/end)
	- step-end == steps(1, end) <> step-start == steps(1, start)
- transition-delay
		

Navbar example

Start with an example, what we want to build (amazon)

- start flexing the nav + list-style-none
- spacing via margins


Performance

example

Only use gpu-accellerated properties (transform + opacity)
https://www.html5rocks.com/en/tutorials/speed/high-performance-animations/



allgemein

weitere beispiele: https://www.smashingmagazine.com/


Typische animationen:
- Fading
- sliding



