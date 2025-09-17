# first
the first one
                                      
minute=108
hours=minute//60
m=minute-hours*60
print(m)
print(hours,m)

t=input('the minutes')
T=int(t)
h=T//60
print(h,T-60*h)

T=int(input('the minutes'))
h=T//60
print(h,T-60*h)

T=int(input('the minutes'))
h=T//60
print(h,'h',T-60*h)

T=int(input('the minutes'))
h=T//60
print(h,'h',T%60)

t=float(input('the number of the year'))
p=10000
n=12
r=0.08
A=p*(1+r/n)**(n*t)
print(A,'$')

t=float(input('the time right now'))
c=float(input('the clock hours'))
a=c+t
r=int(a%24)
print(r,':00')
