# BMI-UNIQUE-CALCULATOR
Calculator for calculating body mass index
name=input("")
weight=int(input("enter your weight in pound: "))
height=int(input("enter your height in inches: "))
BMI= (weight * 703)/(height * height)
print(BMI)


if BMI>0:
    if (BMI < 18.5):
        print("you are underweight. ")
    elif (BMI<=24.9):
        print("you are normalweight. ")
    elif (BMI<=29.9):
        print("you are overweight. ")
    else:
            ("Enter value inputs")
