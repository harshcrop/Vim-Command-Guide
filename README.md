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
                                                             

