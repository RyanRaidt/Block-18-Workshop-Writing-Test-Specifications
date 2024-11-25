# Block-18-Workshop-Writing-Test-Specifications

Multiplication Function

Expect multiplication(2, 4) to be 8.
Expect multiplication(4, 5) to be 20.
Expect multiplication(-5, 10) to be -50
Expect multiplication(0, 7) to be 0
Expect multiplication(2, string) to be an error

ConcatOdds Function

Expect concatOdds([13, 41], [9, 7, 1]) to be [1, 7, 9, 13, 41]
Expect concatOdds([21, 42, 84], [13, 27, 55, 111]) to be [13, 21, 27, 55, 111]
Expect concatOdds([], []) to be []
Expect concatOdds("Hello", [78, 99]) to be an error
Expect concatOdds([7, 9], null) to be an error

Functional Tests
A shopping cart checkout feature that allows guest checkout and logged-in user checkout

1.Empty Cart
    When the user attempts to check out with an empty cart, they should be prompt with a message that the cart is empty and redirected to continue shopping.

2.Guest checkout
    When the user chooses to checkout as guest, they should be prompted to enter the following information(Full name, email, address, payment details).

    When the user has successfully checks out, they should be redirected to a confirmation screen to review the user information. 

    After the user confirms the information and the checkout is finalized, they should be prompted with the chance to create a account or sign in with google. The message may say something like "Want to save time wih your next checkout? Try creating a account or sign-in with google"

3.Logged-in user
    When the user chooses to checkout, they should see their previous information(Full name, email, address, payment details) has been pre-filled.

   When the user has successfully checks out, they should be redirected to a confirmation screen to review the user information.

4.Both Guest and Logged-in user
    When a user proceeds to checkout, they should see an order summary with item details, total cost, and applied discounts.

    If the user enters invalid payment details, they should see an error message and be asked to correct the issue.

