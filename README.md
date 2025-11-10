# BankApp
Приложение банковской системы
UML диаграмма класса Account
classDiagram
    class Account {
        -int id
        -double balance
        -double annualInterestRate
        -Date dateCreated
        +Account()
        +Account(int id, double balance)
        +getId() int
        +setId(int id) void
        +getBalance() double
        +setBalance(double balance) void
        +getAnnualInterestRate() double
        <img width="476" height="513" alt="Снимок экрана 2025-11-10 в 11 27 47" src="https://github.com/user-attachments/assets/58e2e4ee-c291-4589-a727-1d4c5d7725d6" />

        +setAnnualInterestRate(double annualInterestRate) void
        +getDateCreated() Date
        +getMonthlyInterest() double
        +withdraw(double sum) void
        +deposit(double sum) void
        +toString() String
    }

