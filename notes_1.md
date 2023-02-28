
### responsive layouts

The basic trick to most responsive layouts is to take a flex layout and simply switch the flex direction from row to colum. If you look at your new york times page you can see this pattern nested several times in the layout. 

The code here is a very simple example of this. The media query overwrites a minimal amount of values to make the layout shift when the screen width is less than 768px.

Here you could for hte main sections set the first to flex:2 and the second to flex 1 and get a 2 /3 to 1/3 size ratio. However I find its better to have one of the elements a fixed size and the other one flex:1 to take up the remaining space, so that only one element resizes. Additionally you will see that I do a centered max with content container. The real nytimes website also does this. Doing full page width designs should be the exception to this, there are reasons to do it, but screens can get very wide and by setting a max width container you eliminate your design looking weird on very large screens.

If you doc your dev tools in chrome to the right side of the screen, you can drag them bigger and smaller and this is an easy way to change hte screen size and see the changes