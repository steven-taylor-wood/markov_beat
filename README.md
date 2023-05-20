**emct-final-project
goldsmiths university - emct final project**

   _____                    __                    __________                   __   
  /     \  _____   _______ |  | __  ____  ___  __ \______   \  ____  _____   _/  |_ 
 /  \ /  \ \__  \  \_  __ \|  |/ / /  _ \ \  \/ /  |    |  _/_/ __ \ \__  \  \   __\
/    Y    \ / __ \_ |  | \/|    < (  <_> ) \   /   |    |   \\  ___/  / __ \_ |  |  
\____|__  /(____  / |__|   |__|_ \ \____/   \_/    |______  / \___  >(____  / |__|  
        \/      \/              \/                        \/      \/      \/        


Markov Beat - MIDI Effect

By Steven Taylor-Wood

------------------------------------------------------------------------------------------------

Harness the power of Markov chains to create interesting variations of your MIDI input

Demo: 

------------------------------------------------------------------------------------------------

**SYSTEM REQUIREMENTS**

	1. Max Version 8.3.3
	2. Ableton Live 11 Suite
	3. ml.* Machine Learning Toolkit for Max
		- Available to download for free in Max using the package manager

**INSTRUCTIONS FOR USE**

	1. Load Ableton Live.
	2. Open a new MIDI track in Live using ctrl+shift+t.
	3. Load Markov Beat at the beginning of the MIDI track.
	4. Play your MIDI sequence to input the data into Markov Beat.
	5. Once youre happy with the input, click "build".
	6. If the blue button at the top of the plugin is flashing, that means Markov Beat is working.
	7. Alter the "order" to change the result of the output.
	8. Press "build" again to generate a new sequence.
	9. To input new MIDI data to Markov Beat, click "clear" and repeat the process.
	10. Press "bypass" to hear your original MIDI signal.

**TROUBLESHOOTING**

	1. Ensure the "ml.*" package installed from the Max Package Manager, otherwise the plugin won't work.
	2. Make sure your version of Ableton Live and Max are up to date.
	3. Not hearing output from the Markov Beat is normal until the Markov model has been "built"
		- Same applies when pressing "clear"
		- Just bypass the plugin while you are making adjustments to the input data
