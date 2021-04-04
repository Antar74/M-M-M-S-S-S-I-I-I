# M&M&M, S&S&S, I&I&I
A metronome with a sequencer attached to it made with Pure Data Vanilla (0.50-0). It is a work in progress already capable of having up to 16 beats per measure, and subdivisions on each beat.

**v 5-b2** uses 5 abstractions and 1 subpatch briefly described next: 

**Transport Engine (subpatch)**: key controls for start and stop.

**Metro Engine**: a simple metronome with the metro object. 

**Step Meter**: takes a pulse and arranges it in a meter that can have up to 16 beats per measure. The measure can be shifted and shortened to achieve greater flexibility. Uses a counter object from MarkEx external library.

**Beat Multiplets (bM)**: takes a beat and subdivides it to make tuplets. 

**On**: on/off switch.

**Midi Engine**: sets channel and midi note manually or with external controller.
