1. The cpu will run for 100% usage because with have 2 processes that will not make I/O operations
2. The processes take 11 unit of time to complete because there are 4 of full cpu than 5 of I/O + 1 of done flag.
3. Changing the order of processes first I/O then CPU takes less time to complete because while one process is block due to I/O operations the other is free to run CPU
4. With the flag SWITCH_ON_END the total time is as in question 2 bacause is asked to not switch to other processes while I/O is running
5. With the flag SWITCH_ON_IO the time is nearly halved 
6. The resource are not used effectively because the IO is running after
7. That's i good idea because the cpu time will be lower and the cpu will be at 100%
8. switching between flags lower the cpu usage
