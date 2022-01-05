# Day-2-100
Day 2 project


print("Welcome to the tip calculator!")

bill = input("What was the total bill? $")

tip = input("How much tip would you like to give? 10, 12, or 15? ")

people = input("How many people to split the bill? ")

bill_f = float(bill)

t_i = int(tip)

p_i = int(people)

each = ((bill_f / p_i) * (1+ (t_i/100)))


print(f"Each person should pay: ${each:.2f}")
