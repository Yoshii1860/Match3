# Match3

This is a coursework project from Harvard University`s CS50G.

# Implemented Features:

Time Bonus on Match: A scoring system was implemented where successful matches add one second to the game timer per tile matched. This rewards skilled players with extended playtime for their strategic block clearing.

Level-Based Block Variation: The game introduces a difficulty progression system through levels.
- Level 1: Utilizes basic, unpatterned blocks for simpler matching, providing a gentle learning curve for new players.
- Higher Levels: Progressively increase difficulty by introducing blocks with distinct patterns (triangle, cross, etc.). These patterned blocks award bonus points for successful matches, encouraging strategic thinking and rewarding skilled play.

Shiny Block Powerup: A special block type, the "Shiny Block," has been implemented.
- Strategic Advantage: Matching a Shiny Block triggers the destruction of the entire row it occupies, offering a powerful strategic tool for manipulating the board and clearing large sections efficiently.
- Bonus Points: Additionally, upon destroying a row with a Shiny Block, players receive bonus points for each block cleared in that row, further incentivizing the use of this valuable powerup.

Restricted Swapping: To promote strategic planning and thoughtful block manipulation, the game enforces a "restricted swapping" mechanic. Players can only swap blocks that result in a valid match. If no possible matches exist on the board, the entire block layout is reset, encouraging players to analyze the board state and plan their moves carefully.

Mouse-Controlled Block Swapping: An intuitive user interface element using mouse controls has been implemented for block swapping. This allows players to easily interact with the game by clicking and dragging on adjacent blocks to initiate swaps.
