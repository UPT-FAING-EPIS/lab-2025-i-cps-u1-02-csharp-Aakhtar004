```mermaid
classDiagram
    class BankAccount {
        - string m_customerName
        - double m_balance
        + BankAccount(string customerName, double balance)
        + void Debit(double amount)
        + void Credit(double amount)
    }
