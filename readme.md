# Py: ParseFile

W.I.P.

Python tools to patch text-process generated '\*.fetxt' to '\*.dmp' file to directly "#incbin" by Event Assembler.

As is load from UTF-8 encoded, so it can also identify Chinese and Janpanses characters.

Working in Process.

```
usage: (python) ParseFileUTF8.py [-h] [-i INPUT] [-o OUTPUT]

options:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        input .fetext file generated by text-process
  -o OUTPUT, --output OUTPUT
                        output .dmp file to "#incbin" by Event-Assembler
```