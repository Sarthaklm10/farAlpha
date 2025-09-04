# farAlpha API

A backend API built with Node.js and Express.

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Installation

1.  Clone the repository:
    ```bash
    git clone <your-repository-url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd farAlpha
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```

## Running the Application

To start the server, run the following command:

```bash
node index.js
```

*Note: For convenience, consider adding a `"start": "node index.js"` script to your `package.json`.*

## Testing

There are currently no automated tests. If tests were configured, they could be run with:
```bash
npm test
```

## Deployment

This project is automatically deployed to an Azure VM via SSH on every push to the `main` branch using a GitHub Actions workflow.
