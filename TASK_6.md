We can use buttons under each square piece and then connect it with a microcontroller(like Arduino) .it can easly scan all 64 buttons and the thing is that it can detect the motion by using pressure concept. When we remove piece from somewhere then and then put somewhere there is a pressure difference, we can sense it and tell our move to robot due to microcontroller. There's no computer vision, RFID, or magnetic sensors used in this, only simple buttons with microcontrollers.



























So after this setup, we have only 20 o/i pins, but if we put pins under each square, we need 64. So the problem can be solved if we put single pins on each of eight rows and eight columns, so we only need 16 pins. This can work: one pin detects the whole row, and one pin detects the entire column, so when any piece moves, the row and column pins detect 
and meet up at the intersection point. That point is where the piece moves out . so finally we use only 16 o/i pins even we don't need 20 pins .