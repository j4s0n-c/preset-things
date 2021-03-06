# Custom firmwares for the Polyend Preset eurorack module.

## First app is an extended version of the Euclidean example in the Polyend Preset Sandbox at https://github.com/polyend/PresetSandbox

## Current Progress:
### Original features:
* Implements 3-track Euclidean sequencer.
* Input receives clock signal.
* Outputs 1, 4, 7 send trigger signals.
* Encoders modify 3 parameters of each track (each row for the output on left):
   sequence length, number of events, offset
* Pads visualize sequences as they are played, switching pages for sequences longer than 8.
* Button Rec pauses/resumes playback.
* Button Clear resets playback in all channels (jump to step 0).
### Added/modified features:
* Expanded to 9 tracks over 3 banks
* Pad rows 1-3 reset just that generator to the selected step
* Bottom row pads 1-3 select and indicate current bank (Bank button also cycles thru)
* Outputs: Bank 1=1,4,7 Bank 2=2,5,8 Bank 3=3,6,9
