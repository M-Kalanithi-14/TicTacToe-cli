# TicTacToe-cli
A Game of Tic Tac Toe that you may RARELY WIN.

It is also available on [PyPI](https://github.com/Programmin-in-Python/Differential-Calculus)

## Installation
***Please Note :- Requires Python Version 3.x***

**If there are 2 or more versions of Python installed in your system (which mostly occurs in UNIX/Linux systems) then please run any one of the commands in the BASH/ZSH Shell \:-**
```bash
$ pip3 install TicTacToe-cli
```
```bash
$ python3 -m pip install TicTacToe-cli
```

**If there is only Python 3.x installed in your system like in Windows systems then please run any one of commands in the Command Prompt \:-**
```cmd
>pip install TicTacToe-cli
```
```cmd
>python -m pip install TicTacToe-cli
```

## Quick Guide
***Please Read till the END***

- Import it using `import TTT`.

- Play the Game using `TTT.play()`.

	- Everytime the Game Finishes it records the Output and computes the **probability** in Real-time.

		- The computed Probability is shown at the _end of every Game_.

		- To explicitly view the stats use `TTT.showProbability()`.

- It _automatically_ creates a **log** of the Game that you played, in case of _future reference_.

	- The log is stored in the **Home Directory**.
