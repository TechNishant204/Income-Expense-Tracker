<h1>Income Expense Tracker</h1>
<img src="https://github.com/user-attachments/assets/96e8ea0a-dabb-4b98-80aa-23d2f9d53e77" alt ="website"/>

<h3>Click for Live Preview: </h3>
<a href="https://track-income-expenses.netlify.app/">Click here</a>
<h2>Overview</h2>
The Income Expense Tracker is a robust web application designed to help users efficiently manage their financial transactions. Whether you're tracking daily expenses or monitoring your income, this tool provides a seamless experience for recording, editing, and analyzing your financial activities. All data is securely stored in the browser's local storage, ensuring your information remains intact even after closing or refreshing the page.

<h2>Key Features</h2>

**Add Transactions**: Easily log income and expense entries with a description and amount.

**Edit Transactions**: Modify existing transactions to correct errors or update details.

**Delete Transactions**: Remove individual transactions with a single click.

**Bulk Delete**: Clear all transactions at once with the "Delete All" option.

**Persistent Data**: All transactions are saved in local storage, ensuring data persistence across sessions.

**User-Friendly Interface**: Intuitive design for a smooth and hassle-free experience.


<br/>
<h3>ScreenShot</h3>
![image](https://github.com/user-attachments/assets/7c72d553-7892-4e82-bc81-be9d1649177a)

<h2>Installation</h2>
Follow these steps to set up the Income Expense Tracker on your local machine:

<h3>Clone the Repository:</h3>

<pre>  
git clone https://github.com/yourusername/income-expense-tracker.git
Navigate to the Project Directory:
</pre>

<pre>
  cd income-expense-tracker
  Install Dependencies:
</pre>

<pre>
npm install
Start the Development Server:  
</pre>

<pre>  
npm start
</pre>

<h3>Access the Application:</h3>
<pre>Open your browser and navigate to http://localhost:3000 (or the port specified in your terminal).</pre>

<h2>How to Use</h2>
<h3>Adding a Transaction</h3>
**Enter a description** (e.g., "Groceries" or "Paycheck").

Input the amount (positive for income, negative for expenses).

Click the "Add" button to save the transaction.

**Editing a Transaction**
Click the edit icon (✏️) next to the transaction you wish to modify.

Update the description or amount in the input fields.

Save your changes by clicking the "Save" button.

**Deleting a Transaction**

Click the delete icon (🗑️) next to the transaction you want to remove.

Confirm the deletion if prompted.

<h2>Deleting All Transactions</h2>
Click the "Delete All" button to clear all transactions.

Confirm the action if prompted.

<h2>Data Persistence with Local Storage</h2>
The application leverages the browser's local storage to save all transactions. This means:

Your data remains accessible even after closing or refreshing the browser.

No need to worry about losing your financial records.

<h2>Technologies Used1</h2>
**Frontend**: HTML, CSS, JavaScript (React.js recommended for a modern approach).

**State Management**: Local Storage for persistent data storage.

**Styling**: CSS or libraries like Tailwind CSS for a clean and responsive design.

<h2>Future Enhancements</h2>
**Categorization**: Add categories (e.g., Food, Rent, Entertainment) for better organization.

**Visual Analytics**: Include charts and graphs to visualize income vs. expenses.

**Export Data**: Allow users to export transactions as a CSV or PDF file.

**Multi-Device Sync**: Integrate cloud storage for syncing data across devices.
