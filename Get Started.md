
To get started with **==KHQR==** payment integration you need to follow of step that involve understanding the API's functionality, authentication, making request, handle response.


![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FcjUxrV0MGUtgNMQS2hBJ%2Fuploads%2F9OWc1BKQsiR8LuRosCTS%2FKHQR%20Workflow%20Diagram%20v3.jpg?alt=media&token=f41eec7a-83d4-46f6-9b57-bb9723178483)




1. Consumer open Bank app and scan **==KHQR==** code in the invoice.

2. Consumer verify amount and other information then submit the payment.

3. Issuing Bank verify bill with Bill24(**optional**).

4. Bill24 response the verify result.

5. Issuing Bank submit payment to Payment Network follow **==KHQR==** payment instruction.

6. Acquiring Bank verify bill with Bill24 before submit payment.

7. Bill24 response the verify result.

8. Verify bill(**optional**)

9. Acquiring Bank verify bill with Bill24 before submit payment.

10. Bill24 response the verify result.

11. Submit payment(**required**)

12. Acquiring Bank submit payment to Bill24.

13. Bill24 response the payment result.

14. Bill24 send payment details to merchant system.

<h2>Roadmap</h2>

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FcjUxrV0MGUtgNMQS2hBJ%2Fuploads%2FwkSc0EE9BBtjhLQf5oJO%2FUntitledroadmap.jpg?alt=media&token=882f3544-f0c9-4663-8341-37353b4b6af4)