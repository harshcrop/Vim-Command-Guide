# Vim Command Guide

     ## Basics                                                  |  ## Navigation 
                                                                |  
       * :e filename    Open filename for editing Save file     | * e          go to end of word
       * :w             Save file                               | * b          go to brginning of word
       * :x             Write file (if changed) and exit        | * 0          go to beginning of line
       * :sav filename  Saves file as filename                  | * G          go to end of file
       * :q             Exit Vim                                | * gg         go to beginnging of file
       * :q!            Quit without saving                     | * L          go to bottom of screen
                                                                | * %          go to matching parenthesis
                                                                | * [[         jump to function start
                                                                | * ]]         jump to block start
                                                                | * :<number>  go to line <number>
                                                                | * <number>|  go to column <number>

     ## Text Indent                                             |  ## Cut/Copy/Paste 
                                                                |  
       * :set autoindent    Turn on auto-indent                 | * y          Copy selected text to clipboard
       * :set smartindent   Turn on intelligent auto-indent     | * dd         Cut current line
       * :set shiftwidth=4  Define 4 spaces as indent size      | * yy         Copy current line
       * :sav filename      Saves file as filename              | * ys         Copy to end of line
       * >>                 Indent                              | * D          Cut to end of line
       * <<                 Un-indent                           | * yw         Copy word
       * =%                 Indent the code between parenthesis | * p          Paste clipboard contents 
       * 16VG=              Indent the whole file               | 


    # File Explorer                                             |  ## Alignment 
                                                                |  
       * :args*.php             Open file list                  | * :%!fmt     Align all lines
       * :grep expression*.php  Returns a list of .php files    | * !}fmt      Align all lines at the current position
                                containing expresson            | * 5!!fmt     Align the next 6 lines
                                                                | 
       * gf                     Open file name under cursor     |  
       * :Sex                   Split window and open           |  ## Marks
                                integrated file exploer         |
                                                                | * m{a-z}     Marks current position as {a-z}
       * :Sex!                  Same as:Sex but split vertically| * '{a-z}     Move to position {a-z}                      
       * :browse                eGraphical file explorer        | * "          Move to previos position                 
       * :ls                    List buffers                    | 
       * :cd ..                 Move to parent directory        |
       * :args                  List files                      |    
                                                             

