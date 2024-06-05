
# Music Composition
## Piece 1: Pentatonic Roulette

[View Video Demo](https://.com) <br>
[View Repo](https://github.com/allolib-s24/EricM/blob/master/tutorials/synthesis/PentatonicRoulette.cpp)


This piece is entirely randomly generated and nondeterministic. Pentatonic Roulette utilizes pentatonic scales to ensure melodious outcomes. Each time the program runs, it generates a random beats per minute (bpm) value between 60 and 180. The number of measures, determining the piece's length, is also randomly selected within the range of 8 to 25. A random pentatonic scale is then chosen. As the piece plays, another random integer determines whether a specific note is played at each beat, based on the generated bpm. Each note within the chosen pentatonic scale has an equal chance of being selected for any given beat.

I have also incorporated a synthesized hi-hat from my music synthesis project, which plays on every beat to provide structure to the piece.

While playing, the spectrogram visuals are thanks to Grace Feng from her file [interstellar.cpp](https://github.com/allolib-s23/demo-gracefeng05/blob/main/tutorials/synthesis/interstellar.cpp) throughout the course of CMPSC 190D (F23).


## Piece 2: Married Life from "Up"

View Video Demo<br/>
[View Generated Synth Sequence](https://github.com/allolib-s24/EricM/blob/master/tutorials/synthesis/bin/SineEnv_Piano-data/Married%20Life%202.synthSequence)

Song Name: Married Life<br/>
Composer: Michael Giacchino

This was the first piece I played using SinEnv Piano on my keyboard. The voice used was the default that comes in the SineEnv file. It took some time to learn and perfect, but completing it was ultimately very rewarding.

# Instrument Synthesis

View Video Demo of Drums Playing Together<br/>
View Repo


I decided to focus on percussion as I began picking up the drums this academic year. I focused primarily on the bass drum and the Hi-Hat 

## Instrument 1: Hi-Hat

View Video Demo<br>

## Instrument 2: Bass Drum

View Video Demo


<br/><br/>
# Music Theory Tutor

View Video Demo<br/>
View Repo

For my final project, I decided to create an application that would help prospective CS190D students learn music theory. Upon coming to class, I saw that some of my fellow classmates did not know the notes of the piano and some other basic music theory that would be helpful in the first task of the class: to create a musical piece.

This is project is a tutor and a game at the same time.
The user can choose between 4 different modes:
<li> Learn Notes</li>
<li> Learn Triads</li>
<li> Learn Intervals</li>
<li> Free Play</li>

These three game modes are designed to give the user practical and applicative experience using these new ideas they learn.

### Game Mode 1: Notes

The user can choose between three options: to learn what notes are, to learn notes as the user plays in a sandbox, and to test oneself.

#### Learn Notes: 
Gives the user a background as to what the notes are and it's structure.
####Play and Learn in a Sandbox:
The user can free play on the piano, and when a note is pressed, the corresponding note is displayed above the keyboard. The user can individually practice certain notes and nail them down before heading into test mode.
####Test yourself!
A note is displayed that the user needs to play. If the user plays the correct note, the score of the user is increased. However, if a wrong note is played, then the score resets to zero, but the game keeps the user's highest score achieved and displays it.

### Game Mode 2: Triads

The user can choose between 4 options: to learn what minor triads are, to learn what major triads are, practice minor triads, and practice major triads.

#### Learn Minor Triads:
Gives the user a background on how to create minor triads in general.

#### Learn Major Triads:
Gives the user a background on how to create minor triads in general.

#### Display and Play Minor Triads!

The user can select between 12 different notes from where the minor triad starts. After, the user can attempt to play those notes. In this mode, the user has full access to the piano at any time and can reference how to play a specific one of these triads by holding down the corresponding key displayed above the piano to display the triad. Then the user can emulate it and learn minor triads!

#### Display and Play Major Triads!

The user can select between 12 different notes from where the major triad starts. After, the user can attempt to play those notes. In this mode, the user has full access to the piano at any time and can reference how to play a specific one of these triads by holding down the corresponding key displayed above the piano to display the triad. Then the user can emulate it and learn minor triads!
