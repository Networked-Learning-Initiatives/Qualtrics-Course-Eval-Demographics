Qualtrics-Course-Eval-Demographics
==================================

pull demographics from banner for CAS-authenticated users.

The code in index.html should be copied and pasted into the Qualtrics survey builder as follows:

1. Edit your qualtrics survey
    1. go to "Look and Feel"
        1. Choose advanced, near "Header"
            1. click edit
                1. click the "<>source" button
                    1. paste the entire contents of THIS project's index.html in the box.
                    
This code asssumes that the user is being redirected from a source that knows their position, college, and department, and has included those in the location hash as in 
    
    ...#position=Student&college=College%20of%20Engineering&department=Computer%20Science
