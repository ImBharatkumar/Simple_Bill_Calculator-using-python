# Simple_Bill_Calculator-using-python
print("Welcome to Hotel Paradise")
menu={"idli":25,"vada":30,"tea":7,"puri":40,"dosa":50}     #used dict to create a simple menu
print(menu,"\n")
gst=0.18
order=menu[str(input())]
quantity=int(input())
bill=(order*quantity*gst)+order
print("Thanku you\nyour bill is",bill,"Rs")
