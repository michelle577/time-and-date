#1 & 2
import sys
import datetime as dt
for line in sys.stdin:

    data = line.strip().split("\t")
    print(data)

    if len(data) == 4:
        store, item, cost, payment = data
        break
    date = dt.datetime.now().date + timedelta(days=730) - dt.timedelta(seconds=60)
    time = dt.datetime.now().time()
print("{0}\t{1}".format(date, time))

#3 
d = dt.timedelta(days=100,hours=10,minutes=13)

#4 
def SomeFunction(feet,inches):
    datetime_object = dt.datetime.now()
    print(datetime_object)
    return feet,inches
