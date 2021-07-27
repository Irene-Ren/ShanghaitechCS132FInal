# ShanghaitechCS132FInal
Developed HuaRongDao Game, wrote requirements for Drugpump and do validation to Elevator

#### HuaRongDao

![image-20210727233002432](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233002432.png)

- Choose one set beginning of the game
  The player can choose one beginning form the nine start state that has been set. 

  First, click the select menu button “▼” of "选择关卡". A selection menu will pop up, which contains the names of nine start state that have been set.

  Second, click the name of beginning state that you want to play with. Then the beginning state will be shown on the right in the form of a picture. For example, choose the beginning state of “兵来将阻”:

  Finally, the start of the game has been set. The selection menu will pop back automatically. If the player wants to reset, just repeat the above steps.

- Custom beginning
  To custom beginning, click the button “自定义” and system will automatically switch to selMenu interface. The following operation steps will be explained in its section.

- Start game
  To start Huarong Path game, click the “开始” button and the game will start with the set beginning state. If the player has not made any settings before, the game will start in the default state of "横刀立马".

- selMenu
  The Huarong Path APP has a menu for custom beginning named “selMenu”, which is shown below: ![image-20210727233219365](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233219365.png)

- Custom beginning
  The system will provide a series of chess pieces in the order of “曹操、张飞、赵云、黄忠、马超、卒、卒、卒、卒”. The player needs to select the position of the chess pieces in the grid shown on the right. The image of the current chessboard state will be displayed on the left. The "start" button can only be pressed after all pieces have been placed.
  This is an example:
  First, the chess piece is “曹操”, click a position in the grid to place it.

![image-20210727233514676](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233514676.png)

​		The selected position is the position corresponding to the upper left square of the chess piece. “曹操” is then placed in this 		position. The squares that have been placed will turn grey and cannot be clicked.

![image-20210727233537490](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233537490.png)

​		The next chess piece is “张飞”, click a position in the grid to place it.

![image-20210727233547137](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233547137.png)

​		“张飞” is placed then. 

![image-20210727233556675](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233556675.png)

​		Repeat this step until all pieces are placed. Only at this time, the "开始" button can be pressed.

![image-20210727233603932](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233603932.png)

​		Click the start button, and the player can start the game with custom beginning. 
​		If the player wants to rearrange the pieces, just press the "重置" button and the game will return to its original state.

![image-20210727233812520](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233812520.png)

- Return to the main menu
  The player can click “返回主菜单” button to return to the main menu.

- mainInterface
  The Huarong Path APP has a UI named ”mainInterface” for player to play the game: ![image-20210727233926055](C:\Users\asus\AppData\Roaming\Typora\typora-user-images\image-20210727233926055.png)

- Choose and move chess piece
  First, click the figure of a chess piece that the player wants to move. For example, the solder in the lower left corner:

  If the player accidentally clicks on the wrong pieces, he can simply switch by clicking on other pieces.
   Second, click the corresponding button that the player wants to move. A wrong mov is considered as an invalid operation and will not be performed by the system. For example, move the pieces to the outside of the board, or cause the pieces to overlap. In the example, we can only click the "右" button here.

  After moving the pieces, the number of steps in the game will be automatically increased by one.
  Repeat the above steps until the player wins the game.
  The player can simply move the pieces in the opposite direction to achieve the effect of withdrawal. But as a punishment, it will also cause game steps added with 1. The player can reset the game or exit the game to return to the main menu. These two functions are described below.

- Reset the game
  The player can click “重置” button to reset the game. The positions of all chess pieces will return to the set starting state.  The default starting state without setting is ”横刀立马”. The game steps will also be cleared. For example:

  Click the “重置” button:

- Return to the main menu
    The player can click “返回主菜单” button to exit the game and return to the main menu.

- WinWindow
    After the player wins, the game will pop up a victory interface named “WinWindow”, asking the player whether to start again or quit the game.

- Choose to replay or exit the game
    If the player click “是”, the system will return to the main menu.  The player can choose the beginning state and start again.
    If the player click “否”, the system will exit. 