# Number Theory: Addition

In this lab you've learned the basics of number theory as it relates to addition.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Questions

### 1 - How might you add more than two bits together?

More than two bits can be added together by chaining multiple adders. The carry-out from one adder feeds into the carry-in of the next, letting them work together to handle more bits.

### 2 - What is the importance of the XOR gate in an adder?

The XOR gate is important because it’s what determines the sum bit in an adder. It only outputs 1 when the inputs are different, which is exactly how binary addition works. This was shown in the lab using the switches and the light switch/stair example, where flipping either switch changes the output, just like how the XOR gate behaves.

### 3 - What is the largest number a two bit adder can handle? What happens when you go over?

With a two-bit adder, the largest number it can handle is 3, which is 11 in binary. When you go over that limit, it needs another bit, and the extra bit carries over since the adder can’t show it.