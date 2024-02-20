# COS_101_PROJECT
principal = int(input("  initial principal amount :"))

rate = int(input(" annual interest rate : "))

time = int(input(" number of years: "))

n = int(input(" number of times interest is compounded per year: "))

# Calculate the simple and compound interest

simple_interest = principal * (1 + rate * time)

compound_interest = principal * (1 + rate / n) - principal

# print the results
print("Yusuf & Sons")

print("Simple Interest: {:.2f}".format(simple_interest))

print("Compound Interest:{:.2f}".format(compound_interest))
