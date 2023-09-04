ves (there are no empty spaces and no adjacent tiles with the same value), the game ends.[3][13]

## Tech Stack

Language: Python

IDE : PyCharm
## Demo

Insert gif or link to demo

https://www.reddit.com/r/2048/comments/236cbw/4096_an_animated_gif/
## Contributing

Artificial Intelligence:

The mathematical nature of 2048 has made the game of interest to AI researchers. As of 2022, AI achieved[38] over 95% (likely over 98%, but the measurement has noise) probability of making a 16384 tile, over 75% (likely over 80%) probability of making a 32768, and over 3% probability of making a 65536 (improving over the results in [39] and [40]). Due to randomness and lack of spare room, the optimal probability of making a 65536 tile is expected to be low; this is supported by optimal solutions for constrained boards.[38][41]

2048 AI strategy uses expectimax search up to a certain (variable) depth, plus transposition tables to avoid duplication. Analogously to endgame tablebases, tables are used to estimate success (for building a large enough tile without destroying the configuration) in appropriate positions with many large tiles. A position evaluation function can favor empty squares, having a large number of merge possibilities, placement of larger tiles at the edge, and monotonicity for tile sizes, especially for larger tiles.[42][43] The parameters are optimized by a search for better parameter values; some papers[39][40] used temporal difference reinforcement learning.


