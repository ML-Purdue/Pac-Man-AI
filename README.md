# Pac-Man-AI
This project is taken from Berkeley's CS188 class. You can find more information about it [here](http://ai.berkeley.edu/project_overview.html).

Slides on Uniform Cost Search can be found [here](https://l.facebook.com/l.php?u=https%3A%2F%2Fdocs.google.com%2Fpresentation%2Fd%2F1LS2_Twa4h0xNbTRw2fg5kAEaHMi79CjRidCXKhlYfx8%2Fedit%3Fusp%3Dsharing&h=ATPs2ttj-OFBOoGqcLMYoLo8pI0Dtr7tZ3eCc-3_s_Grc89aABnKfTJjsyX_6CAXDOt2irS7iqyVLzvE5iF6AlnSDuYG8uGrrPj0VwPrCYGR1RrFyxGtV5XTsCuX5vMFFyMWJHZ4ZphGuQ).

Slides on A* can be found [here](https://docs.google.com/presentation/d/1aNpwBkHV2YU0g_PDH1Msqg_fs1AwmOp0QIXnOJANgmM/edit?usp=sharing)

Slides on MiniMax can be found [here](https://docs.google.com/presentation/d/1rytUj8KX6VS1dtYSCM9JOWBLQWFK-GF5yfmocGmXNT0/edit#slide=id.p)

Slides on Alpha-Beta Pruning can be found [here](https://docs.google.com/presentation/d/1VRX5_HVNtHFApuWscfXN7uZ7udZq8vWyvenLz-gtONw/edit#slide=id.p)
```
Search
	Implement depth-first, breadth-first, uniform cost, and A* search algorithms. 
	Used to solve navigation and traveling salesman problems in the Pacman world.
	
	Files you'll edit (There are lots of comments to help guide you):
	search.py	Where all of your search algorithms will reside.
	searchAgents.py	Where all of your search-based agents will reside.
	
	You can run bfs using these commands:
	python pacman.py -l tinyMaze -p SearchAgent
	python pacman.py -l mediumMaze -p SearchAgent
	python pacman.py -l bigMaze -z .5 -p SearchAgent
	
	If you want to run bfs add the "-a fn=bfs", e.g. python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs


	Learn more here: http://ai.berkeley.edu/search.html
	Check out Questions 1 and 2. They give further advice and clear things up a bit. 
	
Multiagent
	Implement the Minimax and Alpha-Beta Pruning algorithms. (You can also try your hand at Expectimax algorithm)
	Used to make Pacman aware of the dangers around him.
	
	Files you'll edit/look at (There are lots of comments to help guide you):
	multiAgents.py	Where all of your multi-agent search agents will reside.
	pacman.py	The main file that runs Pacman games. This file also describes a Pacman GameState type, which you will use 				extensively in this project
	game.py		The logic behind how the Pacman world works. This file describes several supporting types like AgentState, 				Agent, Direction, and Grid.
	util.py		Useful data structures for implementing search algorithms.
	
	Learn more here: http://ai.berkeley.edu/multiagent.html
	We are interested in Questions 2 and 3.

