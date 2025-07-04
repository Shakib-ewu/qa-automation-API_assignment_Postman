# 🧪 API Automation - QA Assignment

This project contains automated API tests for creating and deleting a list using Postman.

---

## ✅ Features

- Create a new list
- Delete the newly created list
- Uses environment variable `listId` for chaining
- Status code and response assertions

---


## 🛠️ How to Use

### 1. Import Collection in Postman

- Open Postman
- Click `Import` > Upload `QA_Assignment_Collection.postman_collection.json`

### 2. Import Environment

- Click `Environments` > `Import`
- Upload `QA_Assignment_Environment.postman_environment.json`

### 3. Run in Postman Runner

- Click `Runner` (top-left)
- Select the collection
- Set environment (if any)
- Click **Run**

---

## ✅ Tests Covered

| Test                          | Description                        |
|------------------------------|------------------------------------|
| ✔️ Add New List               | Sends `POST` request to create list |
| ✔️ Delete Created List        | Deletes the list created above      |

---

## 🧑‍💻 Author

**Sakib Sarkar**  
GitHub: [Shakib-ewu](https://github.com/Shakib-ewu)
