# BlockChainTransaction--shop
Blockchain-ShOp-Transaction
Overview
The Product Transaction History Viewer is a Python application created using the Tkinter library. It allows users to dive into the transaction history of various products stored within a CSV file. The application leverages blockchain technology concepts to represent transaction data as blocks within a blockchain.

Features
Product Selection: Users can conveniently pick a product from the list of available products presented as clickable buttons. Each button corresponds to a distinct product listed in the CSV file.

Blockchain Representation: Upon selecting a product, the application dynamically generates a blockchain that visually portrays the transaction history of the chosen product. Each transaction is encapsulated as a block within the blockchain, containing crucial details like transaction number, date, product number, product name, price, quantity, customer number, and country.

Dynamic Data Loading: The application smartly fetches product names from the CSV file, ensuring that any newly added products instantly become accessible to users.

User-Friendly Interface: The graphical user interface (GUI) delivers an intuitive and visually pleasing experience. Products are neatly organized in rows, and transaction history is presented in a well-structured manner.

How to Use
Select Product: Simply click on the product button corresponding to the product you're interested in viewing the transaction history for.

View Transaction History: The application promptly retrieves transaction data for the selected product from the CSV file and displays it as blocks within a blockchain. Each block provides detailed insights into a specific transaction, including timestamps, transaction numbers, and other relevant particulars.

No Transactions Found: In case there are no transactions for the selected product, a message will be displayed to indicate the absence of transactions.

Requirements
Python: Ensure Python is installed on your system to run the application.
Pandas: The Pandas library is utilized for reading and manipulating data from the CSV file.
Tkinter: Tkinter is employed for constructing the user-friendly graphical interface.
Hashlib and Time: These libraries are used for generating hashes and timestamps, respectively.
How to Run
Confirm that you have Python installed on your system.

If not already installed, make sure to install the required libraries (pandas and tkinter).

Place your transaction data in a CSV file named "transaction_details.csv."

Run the Python script. This will open the GUI, allowing you to seamlessly select and explore the transaction history of various products.

Note
CSV Data Format: The CSV file should be structured with columns such as TransactionNo, Date, ProductNo, ProductName, Price, Quantity, CustomerNo, and Country to provide precise transaction details.

Enjoy the journey of exploring your product's transaction history with the Product Transaction History Viewer!
