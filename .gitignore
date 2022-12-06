
import math

def angleClock():
    time=str(input("time: "))
    list1=time.split(":")
    for i in range(len(list1)):
        list1[i]=int(list1[i])

    minuteAngle = list1[1] * 6
    hourAngle = (list1[0] * 30) + (list1[1] * 0.5)
    angle = math.fabs(hourAngle - minuteAngle)
    if (angle)<(360-angle):
        return(angle)
    else:
        return(360-angle)

print(angleClock())
