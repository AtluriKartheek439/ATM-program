# ATM-program
# code of ATM Machine
pin=int(input("Enter your 4-Digit pin number"))
spin=1234
balance=50000
if pin==spin:
    print("Acess Granted !!")
    withdraw=int(input("Enter amount:"))
    if withdraw>balance:
        print("Insufficent Balance")
    else:
        print("Amount withdraw:",withdraw)
        print("Remaining balance:",balance-withdraw)
        print("Thankyou for banking with SBI....")
else:
    print("Acess Denied.....Invalid pin")
    
