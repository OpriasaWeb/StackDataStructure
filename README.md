# Stack - Data Structure

Instructions: You need to make a back button for a browser.
You use a stack to store the website links visited. Each new link visited is pushed onto the stack.
The back button needs to pop the top link from the stack and navigate to it.

The given code declares a Browser class as a stack and implements some of its methods. Then, some links are pushed onto the stack.
A while loop is then used to go back to all links and print them.

Implement the required pop() method for the Browser, so that the given code works as expected.

Pseudocode:





            BEGIN
              DECLARE class named Browser

                DEFINE initialization of self equals to an empty lists named links
              
                DEFINE is_empty of self to compare it into an empty links

                DEFINE push equals to insert to links

                DEFINE pop to remove the first element in the links

              DECLARE_END

              DECLARE x equals to class Browser

              PUSH the 'about:blank' to x variable
              PUSH the 'www.sololearn.com' to x variable
              PUSH the 'www.sololearn.com/courses/' to x variable
              PUSH the 'www.sololearn.com/courses/python/' to x variable

              WHILE the x is not is_empty
                DECLARE popped_value = x.pop()
                PRINT popped_value
              ENDWHILE

            END