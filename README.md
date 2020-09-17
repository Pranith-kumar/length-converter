print("Wellcome to pk’s unit convertor")
print("1.cm to m")
print("2.m to cm")
print("3.cm to inch")
print("4.in ch tocm")
print("5.m to inch")
print("6.inch to m")
print("7.m to feet")
print("8.feet to m")
print("9.feet to yard")
print("10.m to yard")
print("11.inch to yard")
print("12.m to mile")
choice=input("enter the choice  :")
if choice in('1','2','3','4','5','6','7','8','9','10','11','12'):
    i=int(input("Enter the value   :"))
    if choice=='1':
        print("The distance in meter is {} m.\n".format(i / 100))
    elif choice=='2':
        print("The distance in centimeter is {} cm.\n".format(i * 100))
    elif choice=='3':
        print("The distance in inches is {} in.\n".format(i * 0.3937008))
    elif choice=='4':
        print("The distance in centimeter is {} cm.\n".format(i / 0.3937008))
    elif choice=='5':
        print("The distance in inches is {}in.\n".format(i * 39.37008))
    elif choice=='6':
        print("The distance in meters is {} m.\n".format(i / 39.37008))
    elif choice=='7':
        print("The distance in feet is {}feet.\n".format(i * 3.28084))
    elif choice=='8':
        print("The distance in meters is {} m.\n".format(i / 3.28084))
    elif choice=='9':
        print("The distance in yards is {}.\n".format((i / 3.28084) * 1.09361))
    elif choice=='10':
        print("The distance in yards is {}.\n".format(i * 1.09361))
    elif choice=='11':
        print("The distance in yards is {} inches.\n".format((i / 39.370078) * 1.09361))
    elif choice=='12':
        print("The distance in miles is {} miles.\n".format(i * 0.000621371))
else:
    print("invalid input")
