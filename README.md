# Tic Tac Swarm

This is a gam of tic tac toe with a twist! 

The game allows a user to specify the size of a game grid between 3x3 and 9x9, as well as allowing them to styalise the game grid borders between two options.

When the user clicks a grid square to make their turn, the gently swiming snakes swarm in a vortex over the character, 'popping' the nicely formatted character into a glitchy broken form.

The aim of the game is to get all of the same character in either a horizontal row, vertical colum or corner-to-corner diagonal.

I wanted to make a game of tic tac toe with a twist that was visually interesting and modern, showing off all you can do with native JS.

The style is modern, almost steam punky.

## Current Features

- swarming snakes using a canvas, modified from a codepen by FRADAR calles Snake bugs animation.  Altered the event handlers and made it swarm over the clicked point for 3sec
- glitching text using css layer animations
- neon sign glowing text effect showing which players turn it is using CSS animations
- disco underlay the same size as the game grid canvas using a swirling color CSS effect
- white lines 'classic' which appears and overlays the disco effect using the z-index

## Features to implement

- session storage of games
- game wins counter underneath the 'X' and 'O' characters
- more dramatic animation of the 'win' CSS class and removal of the 'hero glitch layer' class - maybe a blinking neon sign effect

## BUGS

- re-size swarm mcanvas when the window.size changes ... if the user re-sizes the browser window
