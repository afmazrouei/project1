# project1
Project Title: Wavetable Symphony
Group Members:
•	Abdulrahman Almazrouei
Format of Score Files:
•	The score file format used for this project is .score, a structured XML-based format that defines the musical notes, timing, and synthesis parameters for the program.
•	The format provides detailed instructions to the sequencer, including start time, note duration, pitch, and effects to be applied.
Actual Score File:
•	The score file used for the main selection is test1.score.
Component Descriptions:
1. Wavetable Synthesizer:
Functionality:
•	The Wavetable Synthesizer component is designed to play short audio waveforms on demand as directed by the sequencer.
•	Features Supported:
o	Wave Playback: The component plays back selected waveforms as indicated by the score file.
o	Envelope Generation: Implements an ADSR (Attack, Decay, Sustain, Release) envelope to shape the sound and avoid abrupt start/stop "pops."
o	Pitch Manipulation: The component can adjust the pitch by varying the playback rate of the waveforms.
o	Attack and Sustain Waves: Supports initial attack wave followed by sustained playback for continuous sound.
o	Table Cross-Fading: Gradually interpolates between different wavetables for richer, evolving sound textures.
2. Effects Component:
Functionality:
•	The Effects Component processes the audio output from the synthesizer to apply various modifications.
•	Features Supported:
o	Reverb Effect: Adds a natural reverberation to simulate different acoustic environments.
o	Chorus Effect: Modifies the input audio to create a fuller, layered sound by slightly delaying and detuning the original signal.
o	Compression/Limiting: Ensures the output levels stay within a desirable range for consistent volume control.
o	Controllable Effects Send: Allows for a mix of "dry" (unprocessed) and "wet" (processed) signals for each effect, providing more versatility in sound output.
Summary: Each of these components has been crafted to fulfill the project requirements and grading rubric, ensuring an integrated, streaming audio system that outputs a coherent musical selection.
