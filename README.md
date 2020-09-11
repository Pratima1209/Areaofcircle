# Areaofcircle
#Python Program for Program to find area of a circle
#here area=pi*(r*r)

r=int(input("Enter the radius:"))
def findcircle(r):
    pi=3.142
    area=pi*(r*r)
    return area

ans=findcircle(r)
print("Area of Circle is {1}".format(r,ans))


