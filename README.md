# Digital Tic Tac Toe

A fully hardware-based implementation of the classic Tic Tac Toe game using only digital logic components — no microcontrollers, no programming.

## 🔧 How it works

- Each field is represented by two flip-flops (2 bits):  
  - `00` = Empty  
  - `01` = Player X  
  - `10` = Player O  

- Player turns are toggled using a T flip-flop.

- Win detection logic uses combinational gates to check all 8 possible winning lines for both players.

- Visual output is provided with LEDs:
  - Red = X  
  - Blue = O  
  - Green = Win indicator  

## 🧠 Features

- Pure digital logic — no code, no processor
- Player toggle and set logic
- Win detection for both players
- Draw detection

## 🚀 Built With

- Digital logic simulator (`Digital` by Helmut Neemann)
- Flip-flops, AND/OR gates, visual indicators
