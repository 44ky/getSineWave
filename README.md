getSineWave.c
======================
It generates the sine wave (.wav) file.  
If you did want to set parameters, you could use options. 

Usage
------
    $ gcc getSineWave.c -o wave
    $ ./wave
And you'll get the wave file on current directory.  

Example
------
    $ Hi-Fi sine wave for guitar tuning
    $ ./wave -b 24 -r 192000 -f 441

Options
------
    $ ./wave -h

License
----------
Copyright &copy; 2013 44ky  
Released under the MIT license
