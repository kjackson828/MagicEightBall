# MagicEightBall

//User asks question and an answer is randomly generated.
var userQuestion = 'Will I grow to be 7 feet tall?';
var randomNumber = Math.floor(Math.random() * 7);
var eightBall = '';
switch(randomNumber){
  case 0:
    eightBall = 'It is certain';
    break;
  case 1:
    eightBall = 'It is decidely so';
    break;
  case 2:
    eightBall = 'Reply hazy try again';
    break;
  case 3:
    eightBall = 'Cannot predict now';
    break;
  case 4:
    eightBall = 'Don\'t count on it';
    break;
  case 5:
    eightBall = 'My sources say no';
    break;
  case 6:
    eightBall = 'Outlook not so good';
    break;
  case 7: 
    eightBall = 'Signs point to yes';
    break;
 }
 
console.log(userQuestion);
console.log(eightBall);
