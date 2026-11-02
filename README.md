PIN: 1234
# ATM_Management_System
Atm Management System using C Language DSA Concepts.

A console-based application designed to simulate core banking and ATM operations using fundamental Data Structures and Algorithms (DSA) like arrays, searching, and sorting.

🛠️ Main DSA Concepts Covered

• Arrays: Used for storing user account data and tracking transaction history logs dynamically.
• Searching: Linear or Binary search algorithms implemented to locate specific accounts or find transactions by unique IDs/types.
• Sorting: Algorithms (e.g., Bubble Sort, Insertion Sort, or Quick Sort) applied to organize transaction history by date or transaction amount.

🧩 Project Modules & Architecture

The system is divided into four distinct modules, each handling specific operations:

1. Account Creation and Management

• Description: Handles new user onboarding and account administration.
• Key Features:
	• Generates/registers accounts with details: Account Number, Account Holder Name, Secure PIN, and Initial Balance.
	• Provides functionality to view and update existing account details securely.

2. Balance Inquiry and Deposit

• Description: Manages basic credential validation and incoming funds.
• Key Features:
	• PIN Verification: Restricts access to balance inquiries until a correct PIN is provided.
	• Cash Deposit: Allows users to add money to their balance and instantly updates the account record.

3. Cash Withdrawal and Balance Validation

• Description: Governs secure outgoing transactions with standard banking constraints.
• Key Features:
	• Validates transaction against sufficient funds and ensures the account maintains a minimum balance requirement.
	• Enforces a daily withdrawal limit to simulate real-world banking security measures.

4. Transaction History (Sorting & Searching)

• Description: Tracks and filters user activity data.
• Key Features:
	• Appends every successful deposit/withdrawal into an internal array structure.
	• Sorting: Allows users to sort their bank statement by Date or Amount.
	• Searching: Enables users to look up past activities instantly by Transaction ID or Transaction Type (Deposit/Withdrawal).

