# ISE_tool_NoteG_extension

This Tool is an extension to the existing "NoteG" which is designed by Noble Mathews.

In the first release, we're showcasing the issues dealing with development in NoteG.

The initial refernce file is added which is of the game -> "sprite". 

The game I'm trying to build in the first release is "Pacman".
 
Reasons for choosing "Pacman" :
      
      - simpler layout and single screen
      
      - Since,there's an issue with animation and movement we're trying minimize complexity.
      
The pacman game is referenced from  "https://itnext.io/how-to-create-pac-man-in-python-in-300-lines-of-code-or-less-part-1-288d54baf939"

In the second release we try to build to multi agent game "Bomberman" using pyagme.

In addition to being an developer friendly design but also enables agents to mimic few AI qualities such as DFS,Dijsktra's algorithms.

A new addition of menu driven game feature has been added.

the new implementations observed in this bomberman game are :
       
       - Menu driven feature of game model rather than a static start screen(use of pygame_menu)
       
       - Observing paths for better movement with respect to both AI and Player
       
       - Animation becomes more fluid compared to previous Pacman game
       
       - Can produce more effects interms of motion and key control
       
Navigation and Controls inside th game :


"arrow keys / 'a','s','d',f'" - for the movement of player

" space bar" - to place the bomb

" q "  - to blast the bomb

the screenshots of menu and game will be added down here.

![image](https://github.com/RahulKrishna8029/ISE_tool_NoteG_extension/assets/75737935/860388f5-e86e-4dd2-a436-b9279ec0976a)


![image](https://github.com/RahulKrishna8029/ISE_tool_NoteG_extension/assets/75737935/a67f9fdc-723d-4066-8a5c-9855a3ebd905)




Our final goal with second release to enable Unity 2D templates as a part of the game prototype.

    The integration of unity templates require utilization of public APIs that has limited request capacity.
    
    - Even with batch APIs there's no concept of upto what part one can scrape the code from the repository
    
 
