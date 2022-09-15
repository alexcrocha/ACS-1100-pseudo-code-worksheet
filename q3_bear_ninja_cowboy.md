# Q3 Pseudo code Python Bear Ninja Cowboy game

INITIALIZE roles with Bear, Ninja, and Cowboy

INITIALIZE computer with a random role

PROMPT the player for one of the roles

GET player role

IF computer role and player role are equal
> DISPLAY “DRAW”

ELSE IF computer equals Cowboy
> IF player equals Bear
> > DISPLAY “You lose!”
>
> ELSE player equals Ninja
> > DISPLAY “You win!”
>
> END IF

ELSE IF computer equals Bear
> IF player equals Cowboy
> > DISPLAY “You win!”
>
> ELSE player equals Ninja
> > DISPLAY “You lose!”
>
> END IF

ELSE computer equals Ninja
> IF player equals Cowboy
> > DISPLAY “You lose!”
>
> IF player equals Bear
> > DISPLAY “You win!”
>
> END IF

END IF
