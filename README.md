# Factwise
#TicTocGame 
positions = [ "1","2","3",
              "4","5","6",
              "7","8","9" ];
# these are the positions of x and o
player 1 = "X"
player 2 = "O"
Players = {"X"||"O"}
# players have been initialized 
# now we will put the conditions 
printBoard = { " |__|__|__|,
                 |__|__|__|,
                 |  |  |  | };
#this is the board where the 2 players will take turns to play
# 1. X wins 
# 2. O wins 
# 3. Tie 

posX = int(input("Enter the positions :")
posO = int(input("Enter The positions :")
if(posX == player 1){
print("player 1 chance done. next player ")
}
if(posO == player2){
print("player 2 chance over.Again player 1 chance")
}
# continue this process until one of the players wins 
direction = [ "vertical", "horizontal", "diagonal"]
# so possible ways a player can win either 3X's or 3O's in a row, in a column or in diagonal 
if (posX == posO){
# that is when both are in same position or if they tie then 
print("Neither X nor O wins. It's a Tie.")
}
print("If You want to continue the game.Press yes or no(y/n):")
if (posX == "1"){
print("X chance done ")}
else if(posO == "7"){
print("O chance done")}
elif(posX == "9"){
print("X is in the 9th position")}
elif(posO == "5"){
print("O is in the 5th position")}
elif(posX == "3"){
print("X is in 3rd position on the printBoard.")}
elif(posO == "2" || "6"){
print("Either of the position O is placed X wins.so X is the winner ")}
else{
print("O Wins ")}
# one of the 2 possibilities either x or o wins 
#otherwise
if(posX == "1")
{ print("Chance done")}
elif(posO == "5"){
print("Other Player chance.")
elif(posX == "7"){
print("X chance done")}
elif(posO == "4"){
print("O chance done")}
elif(posX == "6"){
print(" Player 2 turn")}
elif(posO == "any positions except already taken")
{ print("Neither of them wins. Its A tie ")
}
Else {
print("wanna Play again(y/n):)}
# if created using tf then using button we can reset the game and start the game again until one player wins or tie 
