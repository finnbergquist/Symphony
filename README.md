<img width="799" alt="Screen Shot 2021-08-04 at 12 27 42 PM" src="https://user-images.githubusercontent.com/61434761/128218509-ad53f148-c5cf-4dc4-acd9-166f5fc43297.png">
# Symphony
<img width="766" alt="Screen Shot 2021-08-04 at 12 12 46 PM" src="https://user-images.githubusercontent.com/61434761/128216692-067ff64e-bac9-4508-89a1-ea2554077be5.png">

This project is still in its prototype stage. The concept was born from my obsession with musical production and education. I firmly believe that the best way for kids to learn music is through tactile experimentation. I wanted to recreate the musical sequencing that is possible in digital audio workspaces like Garage Band, Logic, and Ableton in a physical form. To do this I built a 4 step, 4 track sequencer and audio blocks that magnetically snap into place. Moving forward, I hope to find a way to layer audio files in the same track, add effects, and customize the tempo. This project has taught me about developing a concept into a prototype.



The prototype runs on a Raspberry Pi, although the next design iteration will run on a Teensy microcontroller with better audio processing capabilities. Each position has in incomplete circuit with a two strips of conductive tape where the audio file pieces can magnetically click into place. When they audio pieces firmly connected, the circuit is completed. Each audio piece has a resistor with unique resistance. This way the central processing unit can identify which piece is connected in any position at all times. One challenge I ran into was fluctuation in resistance when the central processor reads the analog signal from each circuit. This limited using resistors with similar resistance values.

<img width="442" alt="Screen Shot 2021-08-04 at 12 07 29 PM" src="https://user-images.githubusercontent.com/61434761/128216734-5f300172-b640-4185-b7fa-a839c62ed6bd.png">
<img width="495" alt="Screen Shot 2021-08-04 at 12 08 09 PM" src="https://user-images.githubusercontent.com/61434761/128216735-67c58b01-ca3e-4aab-a1c7-8bbe6f5d93b2.png">
<img width="978" alt="Screen Shot 2021-08-04 at 12 12 31 PM" src="https://user-images.githubusercontent.com/61434761/128216737-757e5d0b-3e28-4539-8019-9c8505a4c3b0.png">

