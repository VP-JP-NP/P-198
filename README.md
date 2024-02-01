while True:
  total = 0
  customer_name = input("Name of Customer:")
  while True:
    print("Enter the cost and quantity of the item:")
    cost = float(input("Cost:"))
    quantity = int(input("Quantity"))
    total += cost*quantity
    repeat = input("Do you want to add more item say y or n:")
    if repeat == 'n': 
      break
  print("Name:", customer_name)
  print("Total Bill Cost:", total)
  print("Thank You For Shopping With Us!!")
