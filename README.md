# MusicImitationAI

A Max/MSP/Jitter project designed to imitate the melodic tendencies of a piece of music. The imitator isolates the melody of a given MIDI file (there are example options in the code), and creates a probability table of the note connections (e.g. the frequency of going from A->C#) and the space between notes (e.g. the frequency of an A->C# having a 30ms delay between notes), then plays back the song based on these probabilities to give a familiar but unique version of the song. The most interesting part of the project is that I created a quantizer, which can change the mode of the song. For example, you can play back an imitation of the Pirates of the Caribbean theme that imitates its rhythm and melody, but plays it in a minor key so that it sounds sad (to the western ear). 

Project is slightly buggy, but all bugs encountered are fixed upon restart. 
