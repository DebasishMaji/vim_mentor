# vim

    
   Vim is a highly configurable text editor for efficiently creating and changing any kind of text. It is included as "vi" with most UNIX systems and with Apple OS X.

   
   #### Modes in vim
   
   * Command Mode : everything you type is a command that allows you to move the cursor around, delete and copy text, search for words, save the file, quit, etc.
   
   * Insert Mode: everything you type (save for special keys) is added to the file, as would happen in a word processor; however, you can only move the cursor with the arrow keys, not the mouse.
   
   
  #### To create a file with vim:
  
  * Type the command vim file_name.extension (e.g. vim_example.txt) or vi file_name.extension
  
  * The editor starts in command mode. 
  
  * We can switch to insert mode by typing i. You should see the message -- INSERT -- appear at the bottom of your window.
   
  * To go back to command mode, press the escape key. The message should now disappear. Toggle back and forth between the two modes.

   #### Command mode cheat sheet:
   
   * Saving and quiting:
    
        * :w - save
        
        * :wq - save and quit
        
        * :q - quit

        * :q! - quit, ignoring changes

        * :u - undo
       
   * Moving the cursor:
   
        * 0 - first column of the line
        * ^ - first non-blank character of the line
        * $ - jump to the last character of the line
        * w - jump to next word
        * b - jump to word-beginning
        * } - jump over a block of lines
        * % - jump to matching bracket
        * '*' - go to next occurrence of word under cursor
        * '#' - go to previous occurrence of word under cursor
        
   * Copy and Paste
   
        * yy - copy current line
        * 10yy copy 10 lines
        * p - paste
   
   * Search:
   
        * /word_to_search - search the document for the next occurrence of word_to_search
        * ?word_to_search - search the document for the previous occurrence of word_to_search