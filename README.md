# Bank-AbstractClass

this program contains three classes and one Abstract Class
-BankServices (abstract) with an abstract method debit and implemented method credit
-PrivilegedBankServices extends the BankServices and can use the credit method of BankServices directly and have to implement its own debit method
-UsualBankServices extends the BankServices and can use the credit method of BankServices directly and have to implement its own debit method

this is helpful since the implementation of credit is same for both the classes and thats not the case for the debit method
