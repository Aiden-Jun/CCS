
# CCS
Run and test your chess bot. CCS runs a subprocess of your engine to test, play, and analyze your engine.
## Commands
Your engine should accept these commands through stdin

### Find best move
```
f w  rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR w KQkq - 0 1
```
- f - command
- w - color to find best move for (w/b)
- Fen string

#### Engine stdout example
```
e2e4
```
Move should be in universal chess interface



### Evaluate board
```
e rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR w KQkq - 0 1
```
- e - command
- Fen string

#### Engine stdout example
```
0
```
Evaluation as a number
