# When blocks
All code must be in a when event. They are marked with the blocks `when()` and `endWhen()`
## All when events
* onInit — runs when the ball is created
* onHitBlock — runs when the ball hits a block
* onHitAny — runs when the ball hits a block or a wall
* onTick — runs every game tick
* on1Second — runs every second
* on2Seconds — runs every 2 seconds
* on6Seconds — runs every 6 seconds
## Example usage
```
when(onInit)
setRotationStyle(all around)
endWhen(inInit)
when(onHitBlock)
turn(10)
endWhen(onHitBlock)
```
Lets the ball spin visually on initialization, and rotates 10° clockwise when it hits a block.
