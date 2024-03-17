I built this thing using a form of Monte Carlo algorithm to try a bunch of moves and select whichever move won the most often. The algorithm runs each possible move for a 3/4 second before picking whichever move won the most often.
The computer plays as player 2 by default. It's very possible to beat, and I'm guessing it isn't picking optimal moves. It might be more accurate if I made it run longer, but then it'd be less playable.

I've actually gotten really good at beating it. It pretty much picks the same moves over and over again, and its very aggressive in its moves: often to its own detriment. It can't play the long game, so if you're patient, you can
beat it really consistently. At this speed, its not really feasible to make it run longer. If I wanted to make it smarter, I'd need to update its algorithm: it needs some updates to its move selection algorithm. The random game finisher will always return that the current player won more often if the current player has threats on the board, so it defaults to selecting the move that creates the immediate threat. The randomizer isn't smart enough to block obvious threats, so those moves will win out more often than not.
On the bright side though, the computer is really good about blocking obvious threats to itself. It doesn't usually falter with blocking a cheap attack by the player. It also doesn't falter at going in for the kill when it has 3 adjacent pieces on the board.
