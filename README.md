# Shortest-Sublist-to-Sort

>03 May 2021 02:11 PM

I did the question last night okayy 😌 I'm only writing the ReadMe now.

Also my brain is out of coding juice 💆‍♀️ I can feel it. And these are just the easy questions - lov dat. You're doing gr8 sweaty 🤯

***Question: Given a list of integers nums, return the length of the shortest sublist in nums which if sorted would make nums sorted in ascending order.***

So what we're doing is going through the list twice. In the first loop we go from left to right and we look for the **smallest number in the shorter sublist.**

For example if the shorter sublist that needs to be sorted is ``[4,3]`` in the first loop we look for where 3 is in the jumbled list. 

We store the index of this element in a variable called ``end``.

The next for loop goes from right to left and we look for the **largest number in the shorter sublist.**

For example if the shorter sublist that needs to be sorted is ``[4,3]`` in the first loop we look for where 4 is in the jumbled list. 

And store the index of this element in a variable called start.

Then in the end we return the distance between those two indexes.
