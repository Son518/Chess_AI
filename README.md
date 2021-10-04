AI Chess App incoperate Reinforcement and Deep Learning based techniques having state of an art GUI design.In Reinforcement Learning Chess App our Agent(Computer) try to
improves it's actions in an environment through it's past experience which enables smart behavior when a user play against a machine.In this Reinforcement Learning Algo,
training of the models is done such that two players take turns resulting actions which try to maximize their own expected discounted total reward. In simple words chances or
probability of any move in chess which can have highest chances to be called as 'Successful Move' which can put opponent in tough situation and this is applicable for
both user and Agent(Computer) which is ultimate goal of training the Reinforcement Learning model. Multiple parameters are used to tune Chess model trying to get optimal
model meanwhile preventing overfitting and underfitting situation producing a generalized model for RL chess App.Through Deep learning techniques we introduce weights and biases,
activation function,forward and backward propogation to RL Chess model.
Main Features of this web applications is as follows:

1) Ease of use

2) Each move displays probability of particular move along with graphical evaluation.

3) All moves history is traceable and visible in the App and user can simply copy those history files with
  .pgn extensions for later use.

4) "Moves" Table assisting user to quickly provide preview for available legal moves in the app. This evaluating table provide information probability about next moves.

5) In the Menu "Engine Depth" is important. It should be around (5-10) to get quick preview for next legal moves in fast manner howver if "Engine Depth" is set higher  moves will be more Suuccesful but there is
   tradeoff between time and speed.

6) You can play "Player vs Player","Player vs Engine", "Analyze Board" for two players playing in the same device "Flip option" is available in the menu.
7) Shortcut keys are added to quickly execute commands by players.

8) Different Chesssboard theme colors are available in the Menu option.

9) Chessboard have state of art display along with resizing functionlity according to ease of user.

10) The edit mode is extra added functionality which will help user to analyze chess game enabling user to add as many pieces according his own choice while replacing other pieces. But this mode is helpful
    if used within legal parameter of the game chess.

11) "Arrow marker" helps in visualizing moves in chessboard in a better way

12) Our team tried to train our Agent to respond to any move as logically as possible in any situation during the game

Important Instructions:

1)  Use Any IDE(Pycharm Recommanded)

2)  Download all required packages if not installed on machine

3)  Press 2 to enable AI functionality (play against AI engine)

4)  To upload PGN,FEN File just open desired pgn file with notepad++ or simple notepad and select the content in pgn file and and paste it above "search wrapper" which is just above to chessboard having
    placeholder "Enter FEN,PGN or command". In this way all pieces will attain the position according to pgn file and then move pieces according to your way.

5)  User can upload as many pgn or fen files data into "search wrapper" and then can analyze the "History of Moves" Table and can get back to previos moves just by clicking on any past spacific move in the table
    "History of Moves" Table.

6)  User authentication is added each user have to register first for the app then he can login to move towards RL Chess main app. Database support is added using SQLite maininting
    database of users.

7)  Any registered user can select or copy content of "History of Moves" Table which is basically pgn data by adding .pgn extension when saving file into computer.
8)  In the SQL Lite database ADMIn of software can delete any registered player from database.

9)  User can anytime save History of moves adding .pgn extension to file as highlighted above.

10) Each move probability is added using "Evaluation Graph" for layman to analyze, "Moves" table is added to so that each player can analyze what type of legal moves User can play next while showing probability
    of each next move int the chessboard box's

11) Run App using pyhton server.py or running server.py file (Instruction to Deployment Team)

11) Now simply start playing RL Chess App and try to checkmate your opponent with all assistance provided in the App:)





