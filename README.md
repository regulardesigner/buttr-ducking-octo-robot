Buttr Version 1.5

buttr - your grid system with a delicious piece of butter !
========================
#
Yet another grid system, extremely simple, basic and useful for html. A very old project developed after ten years of html with my old friend Philippe Candille (AKA Fluxen). http://www.fluxen.net/
#
#
Buttr is born in 2009 during a client project. 
#
We wanted to use our own grid system because we found all other grid too complicated or not flexible enough. Since we can not stop using buttr because it has proven extremely useful to create the html code of all the graphics. Yes even the most eccentric!
#
#
## HOW BUTTR WORKS
#
### Fisrt things first!
Firstly you will need to add two simple lines of code in your header between <head> and </ head>. Easy, right?

	<link rel="stylesheet" href="bttr.css" />
	<link rel="stylesheet" href="mediaqueries.css" />

#
### And Now?
#
Tree css class, that it !
#
first = .bttr
#
Second = .g + the col size number : 12, 11, 10, 9, 8, 7, 6, 5, 4, 3, 2, 1.
#
For exemple you want to creat two columns, you need to use twice the .g6 class

	<div class="bread">
		<div class="bttr g6">the content<div>
		<div class="bttr g6">the content<div>
	</div>

third = .bread
#
This css class is not mandatory, but if you need to focus your column in a 960px wide page you need this class!
#
### Go further
#
*I have to write this part ... sorry;)*
