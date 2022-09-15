# Q4 Pseudo code Python ascii text CLI app

PROMPT for ASCII Art Text
GET text

PROMPT for ASCII Art Font
GET font

IF font input is 'random'
> REQUEST all fonts from fonts list URL
>
> GET all fonts
> >
> DO the following 3 times
> >
> > SET font to a random font from fonts list
> >
> > REQUEST ascii art from URL with user text and random font
> >
> > DISPLAY "Font: **user font here**"
> >
> > DISPLAY ascii art
>
> END LOOP

ELSE IF font input exists
> REQUEST ascii art from URL with user text and user font
>
> GET ascii art
>
> DISPLAY "Font: **user font here**"
>
> DISPLAY ascii art

ELSE IF there is no font input
> REQUEST ascii art from URL with user text
>
> GET ascii art
>
> DISPLAY "Font: default"
>
> DISPLAY ascii art

END IF
