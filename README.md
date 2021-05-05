
 # Understanding Base 2 / Binary
- Binary is simply another number system and can be used in different ways to represent any number
- Unlike the number system that we use most frequently (which is in base 10), **binary is in base 2**. This means that each digit can be represented by a 0 or a 1 instead of 0 up to 9.
- This is incredibly useful due to the simplicity of the system and is **the most frequently used number system** in most computers today
- In computer terms, one base 2 digit is considered a bit, with 8 bits making one byte. (You may have heard of this term before!)
### How can we represent numbers in base 2?
 - The first digit in base ten is in the one's place, the second is in the 10's place, and so on. Each digit can be viewed as ![image](https://user-images.githubusercontent.com/70238458/117087405-f36ead00-ad14-11eb-809a-591d0b4f4bf0.png) with the first "x" starting at 0 with increments of 1. 
 
 For example...
| 100's place | 10's place | 1's place |
| --- | --- | --- |
| ![image](https://latex.codecogs.com/gif.latex?10%5E2) | ![image](https://latex.codecogs.com/gif.latex?10%5E1) | ![image](https://latex.codecogs.com/gif.latex?10%5E0) |

Let's try to represent a number, say 245, with this idea in mind.

| 2 | 4 | 5 |
| --- | --- | --- |
| ![image](https://latex.codecogs.com/gif.latex?10%5E2) | ![image](https://latex.codecogs.com/gif.latex?10%5E1) | ![image](https://latex.codecogs.com/gif.latex?10%5E0) |

2(![image](https://latex.codecogs.com/gif.latex?10%5E2)) + 4(![image](https://latex.codecogs.com/gif.latex?10%5E1)) + 5(![image](https://latex.codecogs.com/gif.latex?10%5E0)) = 245

This same principle can be applied to base 2 as well. Let's try the number 00101110 and convert this into base ten

| 0 | 0 | 1 | 0 | 1 | 1 | 1 | 0 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ![image](https://latex.codecogs.com/gif.latex?2%5E7) | ![image](https://latex.codecogs.com/gif.latex?2%5E6) | ![image](https://latex.codecogs.com/gif.latex?2%5E5) | ![image](https://latex.codecogs.com/gif.latex?2%5E4) | ![image](https://latex.codecogs.com/gif.latex?2%5E3) | ![image](https://latex.codecogs.com/gif.latex?2%5E2) | ![image](https://latex.codecogs.com/gif.latex?2%5E1) | ![image](https://latex.codecogs.com/gif.latex?2%5E0) |

0(![image](https://latex.codecogs.com/gif.latex?2%5E7)) + 0(![image](https://latex.codecogs.com/gif.latex?2%5E6)) + 1(![image](https://latex.codecogs.com/gif.latex?2%5E5)) + 0(![image](https://latex.codecogs.com/gif.latex?2%5E4)) + 1(![image](https://latex.codecogs.com/gif.latex?2%5E3)) + 1(![image](https://latex.codecogs.com/gif.latex?2%5E2)) + 1(![image](https://latex.codecogs.com/gif.latex?2%5E1)) + 0(![image](https://latex.codecogs.com/gif.latex?2%5E0)) = 46

Hopefully, this tutorial shed some light on binary. For a challenge, try to find out the maximum amount of numbers that can be represented with one byte!
