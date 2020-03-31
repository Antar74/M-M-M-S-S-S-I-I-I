# Master-Metronome
A metronome with a sequencer attached to it made with Pure Data Vanilla (0.50-0). It is a work in progress already capable of having up to 16 beats per measure, and subdivisions on each beat.

**v 5-b6** uses 5 abstractions and 1 subpatch briefly described next: 

**Transport Engine (subpatch)**: key controls for start and stop.

**Metro Engine**: a simple metronome with the metro object. 

**Step Meter**: takes a pulse and arranges it in a meter that can have up to 16 beats per measure. The measure can be shifted and shortened to achieve greater flexibility. Uses a counter object from MarkEx external library.
**UPDATED** (v 2-b2) now has a GUI with a control to change direction. Also redundant objects have been deleted.

**Beat Multiplets**: takes a beat and subdivides it to make tuplets. 
**UPDATED**: (v 2-b3) now has an extra inlet-outlet to pass on ACTUAL MS from Metro Engine. Also redundant objects have been deleted.

**On**: on/off switch.

~~**Midi Engine**: sets channel and midi note manually or with external controller.~~ No longer used.

**Midi Rec**: (v 2-b4) has 2 main sections, one for recording and one for playing. Uses a table array to record midi notes. A GUI enables sending MIDI out, channel, displaying note number, recording, inserting silence, and seting steps range. A third section, not fully operational, enables playing chords.
