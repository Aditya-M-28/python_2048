# 2048 Game

2048 is a single-player sliding tile puzzle video game written by Italian web developer Gabriele Cirulli and published on GitHub.[2] The objective of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048; however, one can continue to play the game after reaching the goal, creating tiles with larger numbers. It was originally written in JavaScript and CSS over a weekend, and released on 9 March 2014 as free and open-source software subject to the MIT License. Versions for iOS and Android followed in May 2014.

2048 was intended to be an improved version of two other games, both of which were clones of the iOS game Threes released a month earlier. Cirulli himself described 2048 as being "conceptually similar" to Threes.[3] The release of 2048 resulted in the rapid appearance of many similar games, akin to the flood of Flappy Bird variations from 2013. The game received generally positive reviews from critics, with it being described as "viral" and "addictive".
Strategy:

Strategies in 2048 include keeping the largest tiles in a specific corner and to keep that tile in that corner and to fill the specified row with the largest numbers.[14][15]



## Authors


Nineteen-year-old Gabriele Cirulli created the game in a single weekend as a test to see if he could program a game from scratch.[16] "It was a way to pass the time", he said.[17] He described it as being "conceptually similar" to the recently released iOS game Threes,[3][18] and a clone of another game, 1024.[19] Developed by Veewo Studio,[20] 1024 is itself a clone of Threes, with its App Store description once reading "no need to pay for Threes".[21] Cirulli's README for 2048 cites another 1024 clone as influence: the homonymous but slightly different in terms of mechanics 2048 by Saming.[22]

Cirulli was surprised when his weekend project received over 4 million visitors in less than a week.[4][23] The game is free to play, Cirulli having said that he was unwilling to make money "from a concept that [he] didn't invent".[24] He released ports for iOS and Android in May 2014.[25]
## Gameplay:

2048 is played on a plain 4×4 grid, with numbered tiles that slide when a player moves them using the four arrow keys.[4] The game begins with two tiles already in the grid, having a value of either 2 or 4, and another such tile appears in a random empty space after each turn.[5] Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided.[6][7] The resulting tile cannot merge with another tile again in the same move. Higher-scoring tiles emit a soft glow;[5] the largest possible tile is 131,072.[8]

If a move causes three consecutive tiles of the same value to slide together, only the two tiles farthest along the direction of motion will combine. If all four spaces in a row or column are filled with tiles of the same value, a move parallel to that row/column will combine the first two and last two.[9] A scoreboard on the upper-right keeps track of the user's score. The user's score starts at zero, and is increased whenever two tiles combine, by the value of the new tile.[5]

The game is won when a tile with a value of 2048 appears on the board. Players can continue beyond that to reach higher scores.[10][11][12] When the player has no legal moves (there are no empty spaces and no adjacent tiles with the same value), the game ends.[3][13]

## Tech Stack

Language: Python

IDE : PyCharm

Python Package used: pygame, random
## Demo

Insert gif or link to demo

![Alt text](image.png)

https://www.reddit.com/r/2048/comments/236cbw/4096_an_animated_gif/
## Contributing

Artificial Intelligence:

The mathematical nature of 2048 has made the game of interest to AI researchers. As of 2022, AI achieved[38] over 95% (likely over 98%, but the measurement has noise) probability of making a 16384 tile, over 75% (likely over 80%) probability of making a 32768, and over 3% probability of making a 65536 (improving over the results in [39] and [40]). Due to randomness and lack of spare room, the optimal probability of making a 65536 tile is expected to be low; this is supported by optimal solutions for constrained boards.[38][41]

2048 AI strategy uses expectimax search up to a certain (variable) depth, plus transposition tables to avoid duplication. Analogously to endgame tablebases, tables are used to estimate success (for building a large enough tile without destroying the configuration) in appropriate positions with many large tiles. A position evaluation function can favor empty squares, having a large number of merge possibilities, placement of larger tiles at the edge, and monotonicity for tile sizes, especially for larger tiles.[42][43] The parameters are optimized by a search for better parameter values; some papers[39][40] used temporal difference reinforcement learning.


2048 AI strategy uses expectimax search up to a certain (variable) depth, plus transposition tables to avoid duplication. Analogously to endgame tablebases, tables are used to estimate success (for building a large enough tile without destroying the configuration) in appropriate positions with many large tiles. A position evaluation function can favor empty squares, having a large number of merge possibilities, placement of larger tiles at the edge, and monotonicity for tile sizes, especially for larger tiles.[42][43] The parameters are optimized by a search for better parameter values; some papers[39][40] used temporal difference reinforcement learning.

