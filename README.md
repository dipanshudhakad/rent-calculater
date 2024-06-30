
rent = float(input("Enter your hostel rent: "))
food = float(input("Enter the amount spent on food: "))
electricity_spend = float(input("Enter the total electricity spend: "))
charge_per_unit = float(input("Enter your charge per unit: "))
person = float(input("Enter the number of people: "))

total_bill = electricity_spend * charge_per_unit
output = (food + rent + total_bill)/persons

print("Each person's bill: $", output)
