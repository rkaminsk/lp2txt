# lp2txt converts the smodels format into something readable

This is just to keep some of my old code around. It runs only with Python 2 and
is superseeded by the lpconvert program that comes with clasp.

    echo "1 {a; b} 1." | gringo --output=smodels | lp2txt
