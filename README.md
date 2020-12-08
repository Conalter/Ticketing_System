# Ticketing_System

Background
A ticketing system is required for the collection, logging and management of IT support requests from users of IT systems in your organisation. Information about the requirements are detailed below.

Registration:
Before the ticketing system can be used, an account must be created. During the account creation process, the following details must be collected: first name, last name, department name, office/room location, email address and of course, password.

Creating support requests:
A registered (and logged in) user should be able to create an IT support request by providing a title for the request and some notes (information about the request). A case reference should then be generated and displayed to the user.

Managing support requests:
An administrator should be able to pick up requests that have been created, review, add notes to them and close them when the issue has been resolved. It should also be possible for users to add notes to open requests (that they have created), close a request if they have managed to resolve the issue and reopen a request if the user is not satisfied with the resolution provided by the administrator. Every action on the system (such as creating requests, adding notes, closing requests, etc.) should be timestamped. New notes should generate notifications for the relevant users when they are logged in. For example, when a user adds a note to a request, the administrator should see a notification after logging in and when an administrator adds a note to a request, the owner of the request should see a notification after logging in. Such notifications should appear only for notes that are unread.

Other considerations:
A basic user should not be able to see other users’ requests, but an administrator should be able to see all requests. All form data should be validated, for example, you may want to prevent users from adding empty notes or notes that do not meet a character length criterion. You should decide the validation rules and document it in your design report. An administrator should be able to reset forgotten user password.
