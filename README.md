# BankingTest
Welcome to the AngularJS Protractor Banking Project's Testing and Quality Assurance Repository! This project is dedicated to ensuring the AngularJS-based application's robustness and reliability through a thorough testing process.

Manual Testing
Bug Report: Deposit and Withdrawal Functionality

Issue 1: Deposit Section - Handling Negative Amounts and Zero Value

Description: Currently, the website's deposit functionality permits users to deposit amounts less than or equal to zero, including negative numbers.
Impact: Allowing negative or zero deposits can result in faulty financial transactions, potentially causing discrepancies in the user's account balance. Furthermore, it does not display any result on the page.
Steps to Reproduce:
Navigate to the deposit section on the website.
Enter a negative number or zero as the deposit amount.
Attempt to complete the deposit transaction.
Issue 2: Withdrawal Section - Transaction Failure for Excessive Withdrawals

Description: The withdrawal functionality on the website does not prevent users from attempting to withdraw amounts greater than their available balance.
Impact: Allowing withdrawals greater than the available balance can lead to misleading information, as the transaction fails without providing clear feedback on the reason.
Steps to Reproduce:
Navigate to the withdrawal section on the website.
Enter an amount greater than the current account balance.
Attempt to complete the withdrawal transaction.
Expected Behavior:
In the deposit section, the system should validate and reject transactions with negative or zero amounts, providing an appropriate error message to the user.
In the withdrawal section, the system should validate and reject transactions with amounts exceeding the available balance, providing a clear error message explaining the reason for the transaction failure.
Conclusion
Addressing these deposit and withdrawal issues will enhance the overall reliability and user experience of the website's financial transactions, preventing potential errors and providing clear feedback to users during the process.

JIRA User Stories

User Story 1: Customer Login

As a customer, I want to easily log in to the XYZ website using my unique credentials for convenient access to personalized features.
User Story 2: Character Selection

As a customer, I want the ability to select "Hermione Granger" from the drop-down menu after successfully logging into the XYZ website.
User Story 3: Transaction Details

As Hermione Granger, I aim to access a dedicated page on the XYZ website, offering options such as transactions, deposits, and withdrawals after selecting my character. Additionally, I want to click on the "Transactions" option to view a detailed list including information like date, amount, and more.
User Story 4: Deposit

As Hermione Granger, I desire a straightforward process for depositing funds on the XYZ website. I want to click on the "Deposit" option, be prompted to enter a value for the deposit, and then proceed to complete the deposit.
User Story 5: Withdrawal

As Hermione Granger, I seek a seamless process for withdrawing funds on the XYZ website. I want to click on the "Withdrawal" option, be prompted to enter a value for the withdrawal, and then proceed to complete the withdrawal.
User Story 6: Bank Manager Login

As a bank manager, I want to access the XYZ website easily using my designated credentials. Once logged in, I expect to see options such as "Add Customer," "Open Account," and "Customers" to efficiently manage and oversee banking operations.
User Story 7: Add Customers

As a bank manager, I wish to efficiently add new customers to the XYZ bank system. I expect to click on the "Add Customer" option, be prompted to enter essential details such as first name, last name, and postcode, and then click the "Add Customer" button to successfully record the customer information.
User Story 8: Open an Account

As a bank manager, I aim to efficiently open new accounts for customers on the XYZ website. I expect to click on the "Open Account" option, be prompted to select a customer name and currency from drop-down menus, and then click the "Process" button to successfully open the account.
User Story 9: Customer Details

As a bank manager, I intend to efficiently view and manage customer information on the XYZ website. I expect to click on the "Customers" option and see a comprehensive list that includes customer details such as first name, last name, and postcode.
User Story 10: Delete Customer

As a bank manager, I want to efficiently manage customer records on the XYZ website. I expect to click on the "Customers" option, view a list of all customers, and have the ability to delete a customer by clicking the "Delete" button next to their name.

# Load Testing on JMeter

![image](https://github.com/minayemsv/BankingTest/assets/93090255/c20a2d27-326f-4a43-bc71-1140600fca96)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/73ea9252-b948-4555-82cf-14e8187b4b00)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/4d5626e7-3941-4a8d-8264-031130aebb14)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/8860fa37-1ece-4964-b908-ac698be1559b)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/39bdb9a9-bb8a-466c-a8bb-b28d925c3e9a)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/2ca2d617-a901-412f-a132-9d5620beabaa)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/414580c3-977b-465e-b9e7-b0c79b776ada)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/d7a82e2b-a451-489b-9870-43d055bba269)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/497212d4-e07f-41c2-b80e-25acde41239e)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/25f8266c-f613-4cee-b0b0-ef4c26cb98d3)
![image](https://github.com/minayemsv/BankingTest/assets/93090255/8b256404-8601-4887-95ac-2ecfa30d9828)

# Conclusion
We have a comprehensive testing strategy in place for the AngularJS Protractor Banking Project, covering all aspects to ensure its reliability and user-friendliness. Our approach involves a combination of automated tests for efficiency, manual testing for detailed scrutiny, and load performance testing to guarantee the application's resilience during peak usage. This testing synergy serves as our secret sauce, allowing us to create a robust and user-friendly project. Together, we are dedicated to ensuring every facet is solid, dependable, and prepared for a successful launch.








