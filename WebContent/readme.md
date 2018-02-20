
1. LoginActivity


    The launcher activity used to login, contains login and register buttons

    Entrance input: none

    Output: username to main activity. If login successfully, the user name will be shown on main activity.


2.	RegisterActivity


	This is the activity used for registering a player.

	Entrance input: none

	Output: create a new player, and then login with the newly created username to MainActivity. If register successfully, the username will be shown on main activity.


3. MainActivity


	The main activity serves as main menu, displayed after successful login. It contains entrances to activities of view statistic, create puzzle, create tournament, play tournament and play puzzle. 

	Entrance input: username

	Output: provides username to CreatePuzzleActivity, CreateTournamentAcvitity, ViewStatisticActivity, PlayTournamentActivity and PlayPuzzleActivity. The username will be transferred and displayed into corresponding activities.


4. ViewStatisticActivity


	This is the activity for displaying player statistics, such as the list of puzzles and tournaments completed by that player, with corresponding score, and all puzzles and tournaments with top score and top player.

	Entrance input: username

	Output: provides username while back to MainActivity.


5. CreatePuzzleActivity

	
	This is the activity used to display related UI and form to create a puzzle.

	Entrance input: userName

	Output: newly created puzzle. If created successfully, the unique identifier for the puzzle will be displayed, then back to MainActivity.


6. CreateTournamentActivity


	This is the activity used to display related UI and form to create a tournament.

	Entrance input: userName

	Output: newly created tournament. If created successfully, a confirmation message will be display showing the tournament has been created, and return to the MainActivity.



7. PlayTournamentActivity


	This is the activity that provides all related UI and functions for playing a tournament. It also provides entrance for PlayPuzzleActivity.

	Entrance input: username, tournament name

	Output: The game statistic will be updated accordingly while player playing the tournament. 



8. 	PlayPuzzleActivity


	This is the activity that provides all related UI and functions for playing a puzzle.

	Entrance input: username, puzzle id

	Output: The game statistic will be updated accordingly while player playing the puzzle. 

