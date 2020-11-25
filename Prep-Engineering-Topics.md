## Wiki Entry - _Notes in Outline Form_

## `Quantity over Quality`

1. The more we produce, the more we learn.
    - It seems backwards to everything we are taught.
    - Quality is often a by-product of quantity.

## `Clean Code`

1. Have a purpose
    - Each function should have one, clear purpose.
    - The purpose of the function should be evident.
        - This allows for clearer error handling.
1. Easy to read
    - Code should be easy for others who come after you to read.
        - low WTF/minute rate
    - Time spent reading code is often much greater than the time spent writing it.
        - Find ways to make your code more readable
1. Leave the code cleaner than you found it.
    - Boy Scout Rule adaptation
    - Would it be easy for someone else to read that has limited knowledge on your code? 

## `TDD`

1. Red
    - First focus on writing a test for a specific function or feature.
    - The test will likely fail, but that's ok.
1. Green
    - Work on finding a solution; a way to create an accurate passing test.
    - Once you pass, you are 'in the green.' 
1. Refactor
    - Now take time to refactor. 
    - Is there a better way to write this? Is there another way that will result in the test code running faster while still passing?
        - Milliseconds add up.