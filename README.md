# number-of-days-of-living
import datetime
from datetime import date

year=int(input("birth year: "))
month=int(input("birth month (in number): "))
day=int(input("birth day (in number): "))
date1 = date(year,month,day)

y=int(input("current year: "))
m=int(input("current month (in number): "))
d=int(input("current day (in number): "))
date2= date(y,m,d)

print("number of days you have survived are:",date2-date1)
