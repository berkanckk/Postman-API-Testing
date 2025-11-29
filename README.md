#  Postman API Test Portfolio

This project demonstrates **Automated API Testing** using **Postman** and **JavaScript**.
I used the [ReqRes.in](https://reqres.in/) fake data API to simulate real-world backend testing scenarios.

##  Test Scenarios Covered
In this collection, I implemented the following checks using Postman Scripts:

1.  **Status Code Validation:** Verified that the API returns `200 OK` for successful requests.
2.  **Performance Testing:** Asserted that response time is below **500ms**.
3.  **Data Verification:** Validated specific JSON fields (e.g., `page: 2`, user data existence).
4.  **Negative Testing:** (Planned) Handling 404 and 400 bad request scenarios.

##  Tools Used
* **Postman** (for API Request & Collections)
* **JavaScript** (for Assertion Scripts within Postman)
* **Git & GitHub** (for Version Control)

##  How to Run
1.  Download the `.json` file from this repository.
2.  Open **Postman**.
3.  Click **Import** and select the file.
4.  Run the collection to see the test results (PASS/FAIL).
