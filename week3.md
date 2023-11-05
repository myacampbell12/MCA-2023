# Week 3 

## A comparison of elements in MusicXML and MEI

### Parents and children
- Another difference between MusicXML and MEI is the ways in which parents and children are utilised, which exemplify the heirarchy that exists within a musical score. In MusicXML, the 'note' attribute is the parent and all information about the note are within the child attributes; for example, 'pitch', 'octave', 'stem direction', 'staff', etc are all children attributes that are embedded within the parent attribute. Whereas in MEI, there are much more complicated parent and child relationships that allow for a more flexible way of representing information about the piece of music. MEI contains many parent attributes that have layer parents within them, all of which have their own children. For example; 'staff' is a parent which posesses 'chord' and 'beam' parents within them, and 'note' would be a child within that. Using MEI is a much more flexible way of representing notation due to these complex relationships. It also provides a more detailed analysis of the relationships between notes, beams, staves, etc as we can see the information more clearly. An example of the difference between MusicXML and MEI is the way in which the direction of a stem is represented. In MEI, this is shown within the chord tag before any information on that note is given. However in MusicXML, this is shown on its own line within the note tag, and is given last after information on the pitch, step, octave, duration, tie, and voice. The implication of this difference is that MEI is a more useful form of encoded music notation when anslysing this element as it includes more specific information that is organised in a more systematic way, allowing you to see and therefore edit the notation information much more effectively. 

### Technical granularity 

### Attributes 
