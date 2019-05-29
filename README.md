# 2D_Canvas_JS
Examples of 2d graphics and animation on a Javascript canvas

This repository contains multiple stand alone pages all of which are html canvas elements.

cnvs_TriangleSquareCollision :-
Contains a triangle made from three coordinate points and a square that will continue
to move left across the main canvas area.
When the square is over the triangle a label will notify of clash.

When the square starts to travel outside of the main canvas area, a clone of the square will appear on the right side
of the inner canvas. When the square is completely out of view, the clone of the original square will take its place.


cnvs_TriangleSquareFall :-
Just like triangleSquareCollision a triangle is made of three coordinates. Each side of the inner canvas will have
small square that will start to move from up to down or down to up. The mini squares will stop moving when each has
either hit the bottom or top of the inner canvas area or if the position of the triangle creates a collision.
Left to right and right to left square will move after up to down vice versa have finished.

Blue buttons on the right side can change the position of each point of the triangle.
If a mini square is within the virtual square of the triangle calculations are executed to find which line or lines
of the triangle are diagonal. A "y = mx + b" algorithm is calculated to find where the clash is


parralaxScrollingCanv:-
This is a very simple animation to give a 3d effect of having three layers of rectangles each at a different distance.
