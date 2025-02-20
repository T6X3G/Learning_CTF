LOG
1. head log.log
2. wc -l log.log
3. cat log.log | sort > sorted.log
4.  ```py 
     flag = ''

     with open('sorted.log', 'r') as file:
     for line in file:
       flag += line.strip()[148:149]

     print(flag)
``` 
