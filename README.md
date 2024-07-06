# Minesweeper

Minesweeper made with Python and Pygame ! 

<img src="https://private-user-images.githubusercontent.com/51634013/346259995-4640face-4719-487d-96c8-77f9b8d84a11.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAyNTI1NjYsIm5iZiI6MTcyMDI1MjI2NiwicGF0aCI6Ii81MTYzNDAxMy8zNDYyNTk5OTUtNDY0MGZhY2UtNDcxOS00ODdkLTk2YzgtNzdmOWI4ZDg0YTExLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzA2VDA3NTEwNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWYzYmU2YWM3OTcwMjRlNWY4NzY2Y2U5Yjc0YjA2MTMxYjQ5NjE1NTcwMGEyYWVlZjIwOWYxMTBhNjBiYmZjY2ImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.3kZufkf7MCENlJBG_j6UoMlk_yUo5mO79iF_ueHkEtU" width=30% height=30%>


## Prerequisites 
* [Python >= 3.10](https://www.python.org/)

* Pygame or [pygame-ce](https://pyga.me/) (I used pygame-ce)

## How to play
* git clone this repository
  ```bash
  git clone git@github.com:LucasColas/Minesweeper.git
  ```
* go to the directory
  ```bash
  cd Minesweeper
  ```
* run `main.py`
* Enjoy !

## More explanation
main.py is the entry point. The folder called Game contains the code of the game. The game uses a Piece call to display and rotate a piece. And there's a grid that helps to store the previous pieces and check if a line is complete of if it's the end of the game.
