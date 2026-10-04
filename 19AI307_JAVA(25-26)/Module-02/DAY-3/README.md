# Ex.No:2(C) ACCESS SPECIFIERS





## PROGRAM:
 ```
/*
Program to implement a Access Specifiers using Java
Developed by: HARISH KUMAR S
RegisterNumber: 212224230091
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class BankAccount {
   
    private String accountNumber;
    private double balance;

    
    public String getAccountNumber() {
        return accountNumber;
    }
    public void setAccountNumber(String accountNumber) {
        this.accountNumber = accountNumber;
    }

   
    public double getBalance() {
        return balance;
    }
    public void setBalance(double balance) {
        this.balance = balance;
    }
}

public class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        BankAccount account = new BankAccount();

        String accNo = sc.nextLine();
        double bal = sc.nextDouble();

        account.setAccountNumber(accNo);
        account.setBalance(bal);

        System.out.println("Account Number: " + account.getAccountNumber());
        System.out.println("Balance: " + account.getBalance());

        sc.close();
    }
}
```

## OUTPUT:
<img width="826" height="465" alt="image" src="https://github.com/user-attachments/assets/972c4fcf-d9d0-43f8-bc30-518764a4d55e" />



## RESULT:
Therfore the program successfully stores account details using setter methods and retrieves them using getter methods.




