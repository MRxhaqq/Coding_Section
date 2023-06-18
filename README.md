let player1 = 0;
let player2 = 0;
let billBoard = [1,1,2,2,2,2,1,1,1,2];
for(let i = 0; i <= billBoard.length - 1; billBoard++){
if(billBoard[i] === 1){
console.log('player 1 wins');
player1++;
}
else{
console.log('player 2 wins');
player2++;
}
}
console.log('player1');
console.log('player2');

if(player1 > player2){
console.log('player 1 wins the overall game');
}
else if(player2 > player1){
console.log('player 2 wins the overall game');
else{
console.log('it was a draw between both players');
}
}

