# Thread-safe-library
Class: CS453 p2
Author: Shinji Kasai

# To compile
$ make
$ pc <poolsize> <#items/producer> <#producers> <#consumers> <sleep interval(microsecs)>

# Example
example -> $ pc 10 1000 8 4 0

Output below when the example command was typed.

8 producers 4 consumers 8000 items 10 pool size

I am producer thread 7 (with thread id = 7F5DD27D4700)

I am producer thread 4 (with thread id = 7F5DD0FD1700)

I am producer thread 6 (with thread id = 7F5DD1FD3700)

I am producer thread 5 (with thread id = 7F5DD17D2700)

I am producer thread 3 (with thread id = 7F5DCFFCF700)

I am producer thread 2 (with thread id = 7F5DD07D0700)

I am producer thread 1 (with thread id = 7F5DCF7CE700)

I am producer thread 0 (with thread id = 7F5DCEFCD700)

I am consumer thread 3 (with thread id = 7F5DCE7CC700)

I am consumer thread 2 (with thread id = 7F5DCDFCB700)

I am consumer thread 1 (with thread id = 7F5DCD7CA700)

I am consumer thread 0 (with thread id = 7F5DCCFC9700)

producer 0 finished

producer 1 finished

producer 2 finished

producer 3 finished

producer 4 finished

producer 5 finished

producer 6 finished

producer 7 finished

consumer 0 finished

consumer 1 finished

consumer 2 finished

consumer 3 finished

#items produced = 8000   #items consumed = 8000 
 


