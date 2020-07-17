# LastRitesRepo
LastRites is an Application Management Platform as a One Stop Solution intended for the smartphone users developed by CloudRainbow Technologies for managing the needs of 
the people during the emergency of someone’s demise. This document discusses the requirements for different modules that need to be incorporated in the application. 
There is a scope for the same application to be developed as a web application.

High level steps:
=================================

1. There are total 12 modules in the application
2. Main module is - Information system and customer database
3. If we consider the whole process as a workflow, it will be a sequential workflow with many merge and split actions between starting point and end point.
4. The application can be used in 2 ways - Mobile application and Web application.
5. The user will connect to the application and request for some services.
6. The user information is saved in the database
7. For some sensitive services - the application needs to verify the user information with some special services like - hospital, and/or law and/or order and/or government agencies.
   Once the user is proved to be authenticated then only he will be allowed for requesting other services like insurance, bank, employment etc.
8. Once the special services send the confirmation or verification status then the user's request which was pending till that point by the application can proceed with his requests for all the sensitive services.
9. The user has 2 options for payment - 1. Cash on delivery 2. Online
10. In case of online payment by the user, the service will be handled completely through the payment/ gateway.
11. With each user request for any service, the app will redirect the user to the corresponding service.
12. The service will send the acknowledgement or delivery information to the user.
