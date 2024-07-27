##Rule Engine With AST
A React application for creating, combining, and evaluating rules using Abstract Syntax Trees (AST). Visualize and test rules with ease.

##Features

Create Rule: Input rules in the format field operator value (e.g., age > 30). Automatically validated and converted into an AST.
Combine Rules: Merge multiple rules with logical operators (AND, OR) to form a complex rule represented as a unified AST.
Evaluate Rule: Test the combined AST against provided JSON data to see if it meets the criteria.
Visualize AST: View the AST of individual rules and combined rules as interactive tree structures using react-d3-tree.

##Prerequisites
Node.js (v14 or later)
npm (v6 or later)
Getting Started
Clone the Repository
bash
Copy code
git clone https://github.com/your-username/rule-engine.git
cd rule-engine
Backend Setup
Navigate to the backend directory:

bash
Copy code
cd backend
Install dependencies:

bash
Copy code
npm install
Start the backend server:

bash
Copy code
npm start
The backend server will be available at http://localhost:5000.

Frontend Setup
Navigate to the frontend directory:

bash
Copy code
cd frontend
Install dependencies:

bash
Copy code
npm install
Start the frontend development server:

bash
Copy code
npm start
The frontend server will be accessible at http://localhost:3000.

##Usage

Open your web browser and go to http://localhost:3000.

Create Rule: Enter a rule in the input field (e.g., age > 30) and click "Create Rule". The rule is validated and converted into an AST.

Combine Rules: After creating at least two rules, click "Combine Rules" to merge them into a single AST.

Evaluate Rule: Input JSON data in the textarea (e.g., {"age": 32, "department": "Sales"}) and click "Evaluate Rule" to see if the data meets the combined rule's criteria.

Visualize AST: View the AST of individual rules and the combined AST as interactive tree structures.

##Example

Create Rules:

age > 30
department = Sales
age < 25
department = Marketing
Combine Rules: Combine the rules using logical operators.

Evaluate Rule:

json
Copy code
{
  "age": 32,
  "department": "Sales"
}
The result should be true if the combined AST is satisfied by the provided data.

##Contributing

We welcome contributions! If you'd like to help, please fork the repository, make your changes, and submit a pull request. For detailed guidelines, check out the CONTRIBUTING.md file.

##License
This project is licensed under the MIT License - see the LICENSE file for details.

##Contact
For questions or feedback, please reach out to us at contact@example.com.
