#Task 1 
text = input("Enter text: ")
print(text.lower())

#Task 2 
text = input("Enter text: ")
slow_text = text.replace(" ", "...")
print(slow_text)

#Task 3
text = input()
text = text.replace(":)","🙂")
text = text.replace(":(", "🙁")
print(text)

#Task 4 
mass = int(input())
c = 300000000
energy = mass * (c ** 2)
print(energy)

#task 5 
bill = float(input("how much was the bill: "))
percentage_text = input("what percentage woulkd ypou like to tip? ")
percentage_number = float(percentage_text.replace("%", ""))
tip = bill * (percentage_number / 100)
print("tip:", f"{tip:.2f}")
