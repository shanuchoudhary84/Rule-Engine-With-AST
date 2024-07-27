# Rule Engine

A React application that allows users to create, combine, and evaluate rules. The rules are represented as Abstract Syntax Trees (AST) and can be visualized using a tree structure.

## Features

- **Create Rule**: Allows users to input a rule in the format `field operator value` (e.g., `age > 30`). The rule is validated and converted into an AST.
- **Combine Rules**: Combines multiple rules using logical operators (`AND`, `OR`) to create a more complex rule represented as a single AST.
- **Evaluate Rule**: Evaluates the combined AST against provided JSON data to determine if the data satisfies the rule.
- **Visualize AST**: Displays the AST of individual rules and the combined AST as a tree structure using `react-d3-tree`.

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/rule-engine.git
cd rule-engine



Backend Setup
Navigate to the backend directory:

---cd backend



Install dependencies:

---npm install



Start the backend server:

---npm start

The backend server will run on http://localhost:5000.





Frontend Setup

Navigate to the frontend directory:

---cd frontend

Install dependencies:

---npm install


Start the frontend development server:

---npm start
The frontend server will run on http://localhost:3000.





Usage
Open your web browser and navigate to http://localhost:3000.

Create Rule: Enter a rule in the input field and click "Create Rule". The rule should be in the format field operator value (e.g., age > 30).

Combine Rules: After creating at least two rules, click "Combine Rules" to combine them into a single AST.

Evaluate Rule: Enter JSON data in the textarea (e.g., {"age": 32, "department": "Sales"}) and click "Evaluate Rule". The result (true/false) will be displayed based on whether the data satisfies the combined rule.

Visualize AST: The AST for individual rules and the combined AST will be displayed as tree structures.

Example : 
Create the following rules:

age > 30
department = Sales
age < 25
department = Marketing
Combine the rules.

Enter the following JSON data for evaluation:
{
  "age": 32,
  "department": "Sales"
}
The evaluation result should be true if the combined AST is satisfied by the provided data.