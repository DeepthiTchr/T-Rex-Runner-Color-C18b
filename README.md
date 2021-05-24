# T-Rex-Runner-Color
Q. for the multiplayer car game in which all three arrows can be used to move the sprite at one time
A.
if (touches.length > 0) {
if (restart.overlapPoint(touches[0].x, touches[0].y)) {
reset();
touches = []
}
}

it check touches event on sprite click event
you can create four button as sprite
and use above condition
to check touches on particular button

https://molleindustria.github.io/p5.play/docs/classes/Sprite.html#method-overlapPoint

overlapPoint ( pointX  pointY ) Boolean
Defined in lib/p5.play.js:2039

Checks if the given point is inside the sprite's collider.

Parameters:
pointX Number
x coordinate of the point to check

pointY Number
y coordinate of the point to check

Returns:
Boolean:
result True if inside
