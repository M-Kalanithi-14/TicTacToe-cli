![tictactoe2](https://user-images.githubusercontent.com/74541319/122644706-48834880-d134-11eb-8a38-83650e354760.jpeg)

![tictactoe1](https://user-images.githubusercontent.com/74541319/122644722-56d16480-d134-11eb-9786-f96ee904a36d.png)

For Downloading and Playing, please go to [PyPI](https://pypi.org/project/TicTacToe3/)

## Installation
***Please Note :- Requires Python Version 3.x***

**If there are 2 or more versions of Python installed in your system (which mostly occurs in UNIX/Linux systems) then please run any one of the commands in the BASH/ZSH Shell \:-**
```console
pip3 install TicTacToe3
```
```console
python3 -m pip install TicTacToe3
```

**If there is only Python 3.x installed in your system like in Windows systems then please run any one of commands in the Command Prompt \:-**
```console
pip install TicTacToe3
```
```console
python -m pip install TicTacToe3
```

## Quick Guide
***Please Read till the END***

- Import it using `import TicTacToe3 as T3`.

- Play the Game using `T3.play()`.

	- Everytime the Game Finishes it records the Output and computes the **probability** in Real-time.

		- The computed Probability is shown at the _end of every Game_.

		- To explicitly view the stats use `T3.showProbability()`.

- It _automatically_ creates a **log** of the Game that you played, in case of _future reference_.

	- The log is stored in the **Home Directory**.
