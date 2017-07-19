# WordMash
Find the two letters that end the first word and start the second word. For example in absen(..)rtain the letters ce complete absence and certain
All the words used in the answer come from the New General Service List 
http://www.newgeneralservicelist.org/s/NGSL-101-by-band-qq9o.xlsx
Conflicting answers were checked using the SOWPODS list downloaded from
https://osdn.net/projects/sfnet_scrabbledict/downloads/Dictionary%20Files/sowpods.txt.gz/

Changes Planned
1)  Get user to enter answer and check it - done
2)  UX update, Intro -> Question -> Anwser -> Question - done
3)  Keep score, totals and streaks
4)  Reactive styling
5)  Clear Scores Button
6)	 Cycle through questions in order rather than random

Bugs
1) On Answer Screen, Pressing Enter returns us to intro screen - resolved by hiding the text box on Answer screen
2) Uppercase answers are marked incorrect - resolved, answers converted to lowercase before checking
3) Pressing return should progress the game - resolved
4)	Text input box should have focus when we reach the question page - resolved
5) Should be able to start typing without deleting the ?? in the input box - resolved
