**API Testing Using Rest Assured*
---


````markdown
# 🧪 API Testing with Rest Assured 🚀

![RestAssured Banner](https://i.imgur.com/p2rIuc5.png)

> A hands-on Coursera project to automate REST API testing using Java + Rest Assured + TestNG.

---

## 🌟 Project Overview

This project demonstrates how to perform **automated API testing** using the **Rest Assured** library in Java. The tests validate the functionality of a REST API (e.g., BestBuy API) by sending HTTP requests (GET, POST, PUT, DELETE) and asserting the JSON responses.

---

## 🎯 Learning Objectives

✅ Understand APIs and REST architecture  
✅ Send HTTP requests with Java (GET, POST, PUT, DELETE)  
✅ Work with JSON request/response  
✅ Add assertions using TestNG  
✅ Automate API tests using Maven + Eclipse

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Java | Programming Language |
| Rest Assured | API Testing Library |
| TestNG | Testing Framework |
| Eclipse IDE | Code Editor |
| Maven | Dependency Management |
| JSON | Data Format |

---

## 🧪 Sample Test – GET Request

```java
@Test
public void test_GetAllProducts() {
    given()
        .when()
        .get("http://localhost:3030/products")
        .then()
        .statusCode(200)
        .body("limit", equalTo(10));
}
````

---

## 🗂️ Project Structure

```
rest-assured-api-testing-coursera/
├── src/test/java/
│   └── BestBuyApiTesting.java
├── pom.xml
└── README.md
```

---

## 🚀 How to Run the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/Ahmed-Al-Sabagh/rest-assured-api-testing-coursera.git
   cd rest-assured-api-testing-coursera
   ```

2. **Import into Eclipse IDE**

   * File > Import > Maven > Existing Maven Projects

3. **Run Test with TestNG**
   Right-click `BestBuyApiTesting.java` > Run As > TestNG Test

---

## 🎓 Certificate

This project is part of the Coursera course:
https://www.coursera.org/account/accomplishments/certificate/P33YMDXZPRJH
Instructor: *Saurabh Dhingra*

---

## 🧠 Lessons Learned

✅ How to use `given-when-then` syntax from Rest Assured
✅ Understand JSON assertions
✅ Integrate Rest Assured with Maven/TestNG
✅ Troubleshoot API response structures

--

## 🏁 Final Words

This mini project demonstrates how powerful and easy **REST API automation** can be with the right tools.
It’s ideal for QA engineers, automation testers, and developers interested in building fast feedback loops with APIs.

---

> 💬 Have questions or want to contribute? Open an issue or fork the repo.
> ⭐ Don't forget to star the project if you find it useful!

````

---
