# hrm
a hierarchical recommendation model used to predict what user will buy in the next basket

java -cp hrm.art hrm.learn 0.05 25 10 50 50 0.01 0.9 0.5

Parameter defination:
1 learning rate
2 negative sample count
3 thread count, >1
4 user dimension count
5 item dimension count
6 regulation
7 decay of learning rate for each iteration
8 dropout probability
