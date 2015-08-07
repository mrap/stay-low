# stay-low (working title)
A points based pool game that promotes combos and fun.

## Rules

Take turns to earn points by pocketing balls. 
If you fail to pocket a ball, your turn ends.
Player with the most points wins.

  1. Balls pocketed award points matching the number on the ball.
  2. At the start of every turn, all object balls are valid targets. 
     On all following shots (in the same turn), the target ball must be higher or equal to the target of your previous shot.
     If there are no more legal targets then the turn is over.
  3. Combos that are called award a point multiplier.   
     The multiplier is equal to the number of object balls involved. 
     The called combo does not need to have a pocket specified.
     Total points = pocketed ball num * num of object balls.
  4. Last pocketed ball on the table is worth double points.

### Rack
  
  Same as [Rotation](https://en.wikipedia.org/wiki/Rotation_(pool))
  ![Rotation rack](https://upload.wikimedia.org/wikipedia/commons/f/f1/Rotation_rack.jpg)

## Fouls

  * If the cue ball is pocketed, any points accumulated for **this shot** are awarded to the opposing player.
    The turn ends, and the opposing player has ball in hand.

## Terms

  * Object ball - any numbered ball
  * Target (ball) - ball that can be legally struck by the cue ball

## Tie Breakers

  * The player with the highest chain count wins. Start with the highest achieved chain and work down to the lowest untill there is a winner.
  * If no winner has been decided, the total number points of the pocketed balls for each player are used (multipliers do not apply).
  * If this fails, the total number of pocketed balls will decide a winner.

## TODO

  * Tie-breakers?
