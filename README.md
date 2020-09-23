# Mouse_Dynamics


## Mouse_Dynamics
    |
    |-->training_files
    |       |
    |       |-->User1
    |       |       |
    |       |       |--> Session1_user1
    |       |       |
    |       |       |-->Session2_user1
    |       |       :
    |       |
    |       |-->User2
    |       |       |
    |       |       |--> Session1_user2
    |       |       |
    |       |       |-->Session2_user2
    |       :       :
    |
    |-->testing_files
    |       |
    |       |-->User1
    |       |       |
    |       |       |--> Session1_user1
    |       |       |
    |       |       |-->Session2_user1
    |       |       :
    |       |
    |       |-->User2
    |       |       |
    |       |       |--> Session1_user2
    |       |       |
    |       |       |-->Session2_user2
    |       :       :



    ## SessionX_userY
    
    Fields  : record timestamp, client timestamp, button,   state,      x,      y
                 |                      |           |         |         |       |
    Datatype:   Double,              Double,      string,  string,   Integer,   Integer
    
    Example: 0.351000070572,0.342999999877,NoButton,Move,367,241
             1.36800003052,1.37300000014,Left,Pressed,290,53
             1.5759999752,1.57599999988,Left,Released,292,52
    
    # button -> NoButton, Left
    # Move   -> Move, Released, Pressed,
    
