# Taxi service authentication 

- Read [the guideline](https://github.com/mate-academy/py-task-guideline/blob/main/README.md) before start

In this task, you will implement a visit counter, login/logout functionality, and make your site available only 
authenticated users.

1. Implement a visit counter on the home screen. It should show how many times a user visited the home page before.

2. Create login/logout screens. Provide authentication to your project using built-in Django authentication.

3. Display the username on the top of the sidebar and login/logout button depending on if the user is authenticated.
If the driver clicks on username - the corresponding Driver detail page must open.

4. Protect all your views from unauthenticated users.

5. In Driver's list view add (Me), if this is a current user:
    
Example:
```
- John Smith
- Alice Black
- Mate student (Me)
- Bob White
```

NOTE: Attach screenshots of all created or modified pages to pull request. It's important to attach images not links to them. See example:

![image](https://mate-academy-images.s3.eu-central-1.amazonaws.com/python_pr_with_images.png)
