# Exam template

This is a template that can be used for exam preparation.
The template includes:
- main.tex which is a article class document to includes notes or theorems, to be used in oral exam when using the blackboard.
- presentation.tex which is a beamer presentation used for oral exams with slides.

Both document are super basic layout wise.

I personally use MikTex on Windows for compiling, just using the command line i.e. pdflatex main.tex for example.

I have experienced an issue when compiling namely; pdflatex.exe (file mathkerncmssi8): Font mathkerncmssi8 at 600 not found.
This was fixed by first navigating to the MikTex installation directory, then executing the two commands

- initexmf --mkmaps
- initexmf --update-fndb

Source is stackoverflow https://tex.stackexchange.com/questions/133781/font-display-error-in-windows answer by chrischi.