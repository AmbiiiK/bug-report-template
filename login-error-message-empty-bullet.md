# Bug report – Login error message shows empty bullet
#### Type: Bug
#### Severity: 3 (Medium)  
#### Priority: 3 (Medium)
#### Status: To Do

## Steps to Reproduce
1. Open the login page: https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Account/Login
2. Do not fill in Username or Password.
3. Click on Log In.
4. Observe the error message displayed above the form.

## Actual Result

- Above the form, an error message is displayed with the following text:
“There were one or more problems that prevented you from logging in:”
- Below this text there is only a single bullet point without any explanation.
- The only text below is “Username” and “Password”, which do not clearly describe the problem.
- The user does not know:
whether both Username and Password are mandatory,
what exactly is wrong and what needs to be fixed.

## Expected Result

- In the error box above the form, a clear validation message is displayed, for example:
 - "The Username is required."
 - "The Password is required."
- The user can easily understand from the message what is missing or wrong in the form and how to fix it.

## Example of expected state: ##
<img width="597" height="562" alt="login_page_empty_bullet" src="https://github.com/user-attachments/assets/a2a667d3-e535-4d65-b3cc-647261ac29c9" />


## Environment

- Environment: Production / QA environment (demo login page)
- URL: https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Account/Login
- OS: Windows 11 / macOS 14
- Browser: Chrome 130 / Firefox 132
