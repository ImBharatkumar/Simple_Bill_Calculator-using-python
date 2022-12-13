# Simple_Bill_Calculator-using-python
# Simple Bill calculator
print("Welcome to Hotel ")
menu={"idli":25,"vada":30,"tea":7,"puri":40,"dosa":50,"uttappa":160}
print(menu,"\n")
gst=0.18
print("plz order order below")
order=menu[str(input())]
print("plz order quantity")
quantity=int(input())
bill=(order*quantity*gst)+order
print("Thanku you\nyour bill is",bill,"Rs")
