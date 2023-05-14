# ResturantManagement
IntelliJIDEA
* Serverport: 8080 (use: localhost:8080)
* Java version: 17
* Everything is present in the pom.xml (no need to download any library)

## Steps to run User Management System
* Download the source code and import in intellijIDEA.
* Go to localhost:8080/ URL * Type endpoints in The
## API Documentation
### The API endpoints will be available at http://localhost:8080.

#### Endpoints
 Restaurant-controller

 * GET /restaurants/{id}

 *  PUT /restaurants/{id}

 *  DELETE /restaurants/{id}

 *  GET /restaurants

 *  POST /restaurants

 *  Restaurant-management-controller

 *  PUT /restaurantmanagement/restaurantid/{restaurantEmployeeRecordId}

 *  GET /restaurantmanagement/restaurantid/{restaurantid}

 User-controller

 *  POST /user/signup

 *  POST /user/signin

 *  GET /user/food

Schemas
Food
 * id
* foodName

* foodPrice

*  Restaurant Restaurant

Restaurant

* RestaurantId

* RestaurantName

* RestaurantAddress

* Menu

* PersonalDetails

RestaurantManagement

* RestaurantManagementRecordId

* RestaurantDescription

* RestaurantHeadChefName

* RestaurantHeadChefSalary

* RestaurantStaffsNumber

* RestaurantStaffTotalExpense

* Restaurant Restaurant

SignUpInput

* userFirstName
 SignUpOutput

* status

* message

SignInInput

* userEmail
* serPassword
SignInOutput

 * status
*  token

Project Summary
This application has a well-defined architecture with clear separation of concerns. Each layer has its own set of responsibilities and communicates with other layers in a decoupled way. This makes the application modular and easy to maintain.
