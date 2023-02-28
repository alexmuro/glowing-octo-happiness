
### responsive layouts

The basic trick to most responsive layouts is to take a flex layout and simply switch the flex direction from row to colum. If you look at your new york times page you can see this pattern nested several times in the layout. 

The code here is a very simple example of this. The media query overwrites a minimal amount of values to make the layout shift when the screen width is less than 768px.

If you doc your dev tools in chrome to the right side of the screen, you can drag them bigger and smaller and this is an easy way to change hte screen size and see the changes