# Week 3 

### A comparison of elements in MusicXML and MEI

- MusicXML and Music Encoding Initiative (MEI) and share many similarities, both encoding music notation and both being expressed in XML. However, MEI encodes information about notation in a systematic way, unlike MusicXML. The implication of this difference is that MEI is a more suitable form of encoded music notation as it includes more specific information for analysing the piece.

- A difference between MusixXML and MEI is the way in which the direction of a stem is represented. In MEI, this is shown within the chord tag before any information on that note is given - for example:

 < chord (other information is given here) stem.dir="down"

 < / chord >

However in MusicXML, this is shown on its own line within the note tag, and is given last after information on the pitch, step, octave, duration, tie, and voice - for example:

 < note >
  
 (other information is given here)

 < stem > down < / stem >

 (other information is given here)

 < / note >

The implication of this difference is that 


