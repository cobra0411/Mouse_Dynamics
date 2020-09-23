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
