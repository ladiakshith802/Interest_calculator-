# Interest_calculator-
#Enter the information  asked to calculate  simple and compound  interest.
#Note: please enter the time in years
 

capital =int(input("Type the principal = "))
time = int(input("Type the no. of years = "))
interestrt = int(input("Type the interest rate = "))
intafd = (int(interestrt) / 100)
#interestrt means interest rate
#intafd means interest after division 
interest = (capital * intafd * time)
amount = (int(capital) + int(interest))
intafdcd = (1 + intafd)
compounded_amt  = (capital * intafdcd ** time)
compounded_int = (int(compounded_amt) - int(capital))
print("interest:")
print(interest)
print("Total amount:")
print(amount)
print("Compound interest:")
print(compounded_int)
print("Total Compounded amount")
print(compounded_amt)
print( )
print("Thank you,for visiting.")
