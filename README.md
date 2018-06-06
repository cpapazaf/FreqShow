FreqShow
========

Using code from https://github.com/dswiston/pyFmRadio

Test before running
```
rtl_fm -f 104.3e6 -M wbfm - | aplay -f S16_LE
```

Run
```
ENVIRONMENT=ubuntu python freqshow.py | aplay -f S16_LE
```

Not working perfectly yet


