  <!-- // As a player
  // So that I can record my score for a game of bowling
  // I can start a new game


  // As a player,
  // So that I can keep a record of my scores,
  // I want to be able to add a score for a roll

  // As a player
  // So that I can view game progress
  // I can see the full scorecard after adding a score

  // As a player
  // So that I know where I am in the game
  // I can check which number frame I am currently playing
  
  // As a Player
  // So that I know how well I am playing
  // I can see my current score
  
  // As a Player
  // So that I can see when I have scored a spare (scored 10 on the second roll of a frame)
  // The second roll is marked with a '/' in the scorecard
  // The previous frame score update after next roll
  
  // As a Player
  // So that I can see when I have scored a strike (scored 10 in the first roll of a frame)
  // It is marked with an 'X' in the scorecard
  
  // The frame score update after every next two rolls -->


  <!-- CONSOLE -->
<!-- 
  game = new Game()
// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')

// game.roll(10)
// console.log('current frame number: ' + game._currentFrameNumber)
// console.log('each frame roll: ')
// console.log(game._frames)
// console.log('each frame score: ')
// console.log(game._frameScore)
// console.log('totalscore: '+game.totalScore());
// console.log('final score board')
// console.log(game._totalScoreDisplay)
// console.log('------------')


//************************----------------------***********************



game.roll(9)
game.roll(0)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(4)
game.roll(6)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(10)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(8)
game.roll(1)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(5)
game.roll(3)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(10)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(10)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(9)
game.roll(1)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(5)
game.roll(4)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

game.roll(8)
game.roll(1)
console.log('current frame number: ' + game._currentFrameNumber)
console.log('each frame roll: ')
console.log(game._frames)
console.log('each frame score: ')
console.log(game._frameScore)
console.log('totalscore: '+game.totalScore());
console.log('final score board')
console.log(game._totalScoreDisplay)
console.log('------------')

// ---------------**********************------------------*******************
// game.roll(1)
// game.roll(8)
// game.roll(10)
// game.roll(9)
// game.roll(1)
// game.roll(10)
// game.roll(10)
// game.roll(3)
// game.roll(7)
// game.roll(6)
// game.roll(4)
// game.roll(3)
// game.roll(3)
// game.roll(3)
// game.roll(3)
console.log(game.totalScore()) -->

    