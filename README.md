# 🌐 API Testing with Postman and Newman

Automated API testing for [Automation Exercise](https://www.automationexercise.com) using Postman and Newman.

## 📖 About

This project contains Postman collections for testing the [Automation Exercise](https://www.automationexercise.com) website API. The goal is to automate API testing, ensuring the backend services work as expected and return the correct responses.

---

## 🚀 Prerequisites

Make sure you have the following installed before starting:

-   [Node.js](https://nodejs.org/)
-   [Git](https://git-scm.com)

---

## 🔧 Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/AgneKal/postman-testing.git
cd your-repository-name
npm install
```

---

## ▶️ Running API Tests

### 1. Running Tests with Postman

-   Import the Postman collection from the `/postman` directory into your Postman app.
-   Use Postman to manually run the API requests.

### 2. Running Tests with Newman

To run the tests using Newman in the command line, execute the following:

```bash
npm test
```

You can also generate HTML reports with Newman:

```bash
newman run report
```

---

## 🧩 Test Structure

The test files are structured as follows:

```bash
📁 postman
 ┗📄 Automation-exercise.postman_collection.json    # Postman collection
```

Example API request:

```json
{
    "method": "GET",
    "url": "https://automationexercise.com/api/products",
    "header": [],
    "body": {},
    "description": "Get all products"
}
```

---

## 📝 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE.txt) file for details.

---

### 🔗 Useful Links

-   [Postman Documentation](https://learning.postman.com/docs/getting-started/introduction/)
-   [Newman Documentation](https://www.npmjs.com/package/newman)
-   [Node.js Documentation](https://nodejs.org/en/docs/)

---

### 👩‍💻 Author

Agne: [Github](https://github.com/AgneKal)
