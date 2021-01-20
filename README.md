# Bass_Guitar_Tuner.py
A no_GUI tuner using .wav files

    - Created on Mon Mar 11 2019 11:15:24
    - Utility_Belt Designs, Tacoma, WA
    - www.pythonOver60.rocks
    - @author: ZennDogg
    - zenndogg@outlook.com


    Nothing to see here, folks.  There is no visual interface.

    - Start the program
    - Press the key for the note to be tuned
    - Press the next key, etc.
    - Press any other key to stop

    I use AutoHotkey for a 3 key combination to run BassGuitarTuner.py.
    The wave files were made in Audacity using its tone generator to create
    a 30 second sine wave at the specified frequency. The frequencies are
    based on the A=440hz spectrum. The frequencies used to generate the
    tones can be found at: http://pages.mtu.edu/~suits/notefreqs.html

    They are:
      - E = 82.41  hz
      - A = 110    hz
      - D = 146.83 hz
      - G = 196.00 hz

    HINT: You may find tuning easier if you use the twelfth harmonic.
