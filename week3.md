# Week 3 

## Task 2

### A comparison of elements in MusicXML and MEI

### Access my MusicXML file: [here](mymusicxmlfile.musicxml)

### Access my MEI file: [here](mymeifile.mei)

<b>Stem direction</b>

An example of the difference between MusicXML and MEI is the way in which the direction of a stem is represented. 
In MEI, the 'stem direction' element is a child attribute within the 'chord' parent attribute, then after stem direction comes the 'note' which acts as a layer parent element as it contains its own child elements containing further information on the note. 
The parents and children utilised here exemplify the heirarchy that exists within a notated musical score, showing which attributes are needed to be shown first. In this case, MEI sees stem direction as higher up in the heirarchy than MusicXML does. Using MEI is a much more flexible way of representing notation due to these complex relationships. Whereas in MusicXML, the 'stem direction' element is a child attribute that exists within the 'note' parent attribute. 
The implication of this difference is that MEI is a more useful form of encoded music notation when anslysing this element as it includes more specific information that is organised in a more systematic way, allowing you to see and therefore edit the notation information much more effectively. 

<b>Key signature</b>

Another example of the difference between MusicXML and MEI is the way in which the key signature is represented.
In MEI, this element is shown as 'keySig' in which 'accid' provides information on the key and 'mode' for information on the tone.
In MusicXML, the key element contains attributes that provide information on sharp notes and flat notes.
For both MEI and MusicXML, the 'key' or 'keySig' element is a child of the parent 'measure' element. 
The implication of this difference is that the structure of MEI is much more detailed and comprehensive than that of MusicXML, meaning MEI is more useful for music notation and encoding. 

<b>Clef</b> 

Another example of the difference between MusicXML and MEI is the way in which the clef is represented. 
In MEI, the 'clef' element contains attributes like 'shape' which indicates the note, or 'oct' for the octave of the section. The 'clef' here is the child of the 'staff' parent element, giving control over over clef timing and ay changes to it. 
In MusicXML, the 'clef' element contains attributes like 'line' and 'octave change' which gives information on the position of the clef as well as the octave placement of the clef. The 'clef' here is the child of the 'measure' parent element, showing this clef represents the entire section. 
The implication of this difference is that MEI provides much more flexibility over representing clef changes, which is useful for encoding music. MusicXML only offers a basic representation of the clef. 
