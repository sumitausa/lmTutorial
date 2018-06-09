# lmTutorial

## Excercise for the understanding lm on the states dataset

The dataset compares the data from 6 states , containing information about the region, population, are, density , csat, vsat, percent, expense

The Excercise involves changing the lm equation to include a new interation to see how the csat value is affected

'''{r}
sat.expense.metro.by.percent <- lm(csat ~ expense*metro,
                             data=states.data) 
'''
