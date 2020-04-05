To perform unit test of this Egbert theme, execute:

    cd egbert-theme
    python -Wd -m unittest discover

To modify CSS files, recreate the master CSS file, execute:

    cd egbert-theme/css
    ./

To change color of Pygments lexer (code syntax hi-lighting):

    pygmentize -S parasoi -f html -a .codehilite > pygments-dark-new.css

