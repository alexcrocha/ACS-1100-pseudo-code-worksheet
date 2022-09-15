# Q4 Pseudo code Python ascii text CLI app

PROMPT for ASCII Art Text
GET text

PROMPT for ASCII Art Font
GET font

IF font input is 'random'
> REQUEST all fonts from http://artii.herokuapp.com/fonts_list
>
> GET all fonts
> >
> DO the following 3 times
> >
> > SET font to a random font from fonts list
> >
> > REQUEST ascii art from http://artii.herokuapp.com/make?text={**user text here**}&font{**random font here**}
> >
> > DISPLAY "Font: **user font here**"
> >
> > DISPLAY ascii art
>
> END LOOP

ELSE IF font input exists
> REQUEST ascii art from http://artii.herokuapp.com/make?text={**user text here**}&font{**user font here**}
>
> GET ascii art
>
> DISPLAY "Font: **user font here**"
>
> DISPLAY ascii art

ELSE IF there is no font input
> REQUEST ascii art from http://artii.herokuapp.com/make?text={ user text here }
>
> GET ascii art
>
> DISPLAY "Font: default"
>
> DISPLAY ascii art

END IF
