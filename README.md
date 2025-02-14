# PPS-MINI-PROJECT-_2ND-SEM

<!DOCTYPE html>
<html>
<head>

</head>
<body>
    <h1>Bank Management System</h1> 
    <h2>Introduction</h2>
    <p>The <strong>Bank Management System</strong> is a Python-based project that helps manage bank accounts efficiently. It automates various banking operations, including account creation, customer management, transactions, and balance inquiries. The system is designed to enhance user experience and improve banking operations.</p>
    <h2>Features</h2>
    <ul>
        <li>User authentication for employees and customers</li>
        <li>Account creation and management</li>
        <li>Secure login for users</li>
        <li>Deposit and withdrawal functionality</li>
        <li>View account details</li>
        <li>Transaction history tracking</li>
        <li>Random promotional loan offers</li>
    </ul>
    <h2>Technologies Used</h2>
    <ul>
        <li><strong>Programming Language:</strong> Python</li>
        <li><strong>Database:</strong> MySQL</li>
        <li><strong>Frameworks/Libraries:</strong>
            <ul>
                <li><code>colorama</code> (for terminal color formatting)</li>
                <li><code>playsound</code> (for enhancing user interaction)</li>
                <li><code>random</code> (for generating account numbers and loan offers)</li>
                <li><code>datetime</code> (for date-based operations)</li>
                <li><code>mysql.connector</code> (for database connectivity)</li>
            </ul>
        </li>
    </ul>
    <h2>Installation and Setup</h2>
    <ol>
        <li>Install Python (if not already installed).</li>
        <li>Install required dependencies using pip:
            <pre><code>pip install colorama playsound mysql-connector-python</code></pre>
        </li>
        <li>Set up a MySQL database and create necessary tables.</li>
        <li>Update the database connection details in the Python script.</li>
        <li>Run the Python script:
            <pre><code>python bank_management.py</code></pre>
        </li>
    </ol>    
    <h2>Usage</h2>
    <ol>
        <li>Run the script to access the bank management system.</li>
        <li>Choose the user type (Employee, Customer, Manager, Head).</li>
        <li>Login or register as required.</li>
        <li>Perform banking operations such as account creation, deposits, and withdrawals.</li>
    </ol>
    <h2>System Design</h2>
    <h3>Database Tables</h3>
    <ul>
        <li><code>AddNewCustomer</code> - Stores customer details.</li>
        <li><code>cusid</code> - Stores customer login credentials.</li>
        <li><code>manage</code> - Stores employee login credentials.</li>
        <li><code>transaction</code> - Stores transaction records.</li>
    </ul>    
    <h3>Main Functionalities</h3>
    <ul>
        <li><strong>Employee Panel:</strong> Manages customers and transactions.</li>
        <li><strong>Customer Panel:</strong> Allows customers to view balance and details.</li>
        <li><strong>Manager Panel:</strong> Oversees employee operations.</li>
        <li><strong>Head Panel:</strong> Admin-level control over all accounts.</li>
    </ul>
    <h2>Future Enhancements</h2>
    <ul>
        <li>Implement a graphical user interface (GUI) for better usability.</li>
        <li>Add encryption for password security.</li>
        <li>Integrate with online banking APIs for real-time transactions.</li>
    </ul>
    <h2>Authors</h2>
    <ul>
        <li><strong>Aditya Raj</strong> (RA2311004010310)</li>
        <li><strong>Amit Chauhan</strong> (RA2311004010332)</li>
    </ul>
    <h2>Acknowledgment</h2>
    <p>This project was developed as part of <strong>SRM Institute of Science and Technology's</strong> <strong>Programming for Problem Solving</strong> course under the guidance of <strong>Dr. K. Kalimuthu, Assistant Professor, Department of ECE</strong>.</p>
    <h2>License</h2>
    <p>This project is for educational purposes only and is not intended for commercial use.</p>
</body>
</html>

