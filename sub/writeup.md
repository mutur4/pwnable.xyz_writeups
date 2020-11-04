# Challenge Description 
 >  **Do you know some basic math?**
 >
 > **svc.pwnable.xyz : 30001**
 
 
 ## Solution 
 
This was one of the easiest challenges. According to the description all you have to do 
was some basic math to get the flag.
 
The Binary is an elf binary that takes two integer inputs using `scanf` and subtracts them.
But we have a problem =( Some criteria should be met for us to get the flag.

> The first value should not be greater than 0x1336
>
> The second value should be less than or equal t0 0x1337
>
> The final value should be 0x1337

Some basic math right? The values tha we give they get subtracted 
Therefore I chose `0x3336` and `-1`. Their subtraction gives us '0x1337'. Remember from your basic math class
the `0x1336 - (-1)` this gives us a `0x1336 + 1` and we get the flag. That was easy right =)
