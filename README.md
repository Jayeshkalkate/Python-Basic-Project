# Python-Basic-Project-8
By using python programming language

# Sum of Natural Numbers: 
# Compute the sum of the first n natural numbers.
# Ex :- 1,2,3,4,4,5,6,,7,8,9,10 , ..... n

start_number = (int(input("Enter the starting of natural number : ")))

end_number = (int(input("Enter the ending of natural number : ")))

print(f"The natural number is start from {start_number} and end to {end_number} is given :-\n")

for natural in range (start_number , end_number + 1) :
    print(natural)
