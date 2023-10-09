# Week 3 

## A comparison of elements in MusicXML compared to MEI

1. A difference between MusicXML and MEI is that MEI represents sheet music by having two elements to the score, the "parent" and the "child", shown in the same section of code in order to represent the sense of heirarchy that sheet music possesses. However, MusicXML does not distinguish between the two but rather represents each bar as one large section.

2. A difference between MusixXML and MEI is the way in which the direction of a stem is represented. In MEI, this is shown within the chord tag before any information on that note is given - for example:

  < chord (other information is given here) stem.dir="down"

  < / chord >

However in MusicXML, this is shown on its own line within the note tag, and is given last after information on the pitch, step, octave, duration, tie, and voice - for example:

  < note >
  
  (other information is given here)

  < stem > down < / stem >

  (other information is given here)

  < / note >

The implication of this difference is that 

3. One similarity between MusicXML and MEI is 
