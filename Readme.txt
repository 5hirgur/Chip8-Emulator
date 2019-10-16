 ____________________________________________________________
|This is a repo for an emulator for the Chi8 system          |
|I have also included some ROMS to use ~                     |
|____________________________________________________________|



You will require SDL2 for this project


To run a ROM with the emulator simply drang n' drop a ROM into the .exe file(compile the code for a windows command line application),the game/s should run just fine.

The input keypad keys are - 

 1 2 3 4
 q w e r
 a s d f
 z x c v
 
 Not all games will support this layout, you have to figure out by mashing buttons,I hear playing God Of War helps a lot I hear~
 (for example the controls in pong for P1 is 1,q whereas for P2 is 4,r)
 
 I have tried my best to explain the working of the code in the comments,
 Here are some sources that I referred to -
 
 http://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/
 http://devernay.free.fr/hacks/chip8/C8TECH10.HTM
 https://en.wikipedia.org/wiki/CHIP-8#Opcode_table

+=============================================================================================================================================+
|Also huge thanks to JamesGriffin for his repo,at the time I did not know about graphics and rendering concepts, reading his source code      |     
|made a LOT of concepts clear(I didn't Ctrl+C and Ctrl+V his code for graphic rendering,though that section of the code might look similar:p) |
|heres a link to his repo -                                                                                                                   |
|                                                                                                                                             |
|https://github.com/JamesGriffin/CHIP-8-Emulator                                                                                              |
+=============================================================================================================================================+







                   .,,uod8B8bou,,.
              ..,uod8BBBBBBBBBBBBBBBBRPFT?l!i:.
         ,=m8BBBBBBBBBBBBBBBRPFT?!||||||||||||||
         !...:!TVBBBRPFT||||||||||!!^^""'   ||||
         !.......:!?|||||!!^^""'            ||||
         !.........||||                     ||||
         !.........||||                     ||||
         !.........||||                     ||||
         !.........||||                     ||||
         !.........||||     Et Tu Brute?    ||||
         !.........||||                     ||||
         `.........||||                    ,||||
          .;.......||||               _.-!!|||||
   .,uodWBBBBb.....||||       _.-!!|||||||||!:'
!YBBBBBBBBBBBBBBb..!|||:..-!!|||||||!iof68BBBBBb....
!..YBBBBBBBBBBBBBBb!!||||||||!iof68BBBBBBRPFT?!::   `.
!....YBBBBBBBBBBBBBBbaaitf68BBBBBBRPFT?!:::::::::     `.
!......YBBBBBBBBBBBBBBBBBBBRPFT?!::::::;:!^"`;:::       `.
!........YBBBBBBBBBBRPFT?!::::::::::^''...::::::;         iBBbo.
`..........YBRPFT?!::::::::::::::::::::::::;iof68bo.      WBBBBbo.
  `..........:::::::::::::::::::::::;iof688888888888b.     `YBBBP^'
    `........::::::::::::::::;iof688888888888888888888b.     `
      `......:::::::::;iof688888888888888888888888888888b.
        `....:::;iof688888888888888888888888888888888899fT!
          `..::!8888888888888888888888888888888899fT|!^"'
            `' !!988888888888888888888888899fT|!^"'
                `!!8888888888888888899fT|!^"'
                  `!988888888899fT|!^"'
                    `!9899fT|!^"'
                      `!^"'
