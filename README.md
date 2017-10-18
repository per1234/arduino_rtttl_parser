# Arduino RTTTL parser
A parser for RTTTL (Nokia) melodies for Arduino (uses protothreading).
Useful for game making, robotics with melody background ...

## Usage
Install this library to your sketchbook/libraries directory.
Instanciate  the RTTTL object  by giving the buzzer pinID as well as a pointer to the melody to be played in the form of a null terminated string.
In  your loop function, call   <the instance of RTTTL>.tick(); This will trigger the parsing of the notes and the  playing .

## Status
Still  under developement.