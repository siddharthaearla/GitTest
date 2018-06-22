# LeoFeedback - Leoforce Feedback System

### Class Diagram

### API Design

  - /api/employees/

| Description | get list of all employee details |
| ------ | ------ |
| Method | GET |
| Access | Admin |
| Optional Parameters | sortby, count, team, since, to|


  - /api/employees/

| Description | add employee with given parameters|
| ------ | ------ |
| Method | POST |
| Access | Admin |
| Body Parameters |  |


  - /api/employees/

| Description | update employee details of given id|
| ------ | ------ |
| method | PUT |
| Access | Admin, user with emp_id |


   - /api/employees/

| Description | delete employee of given id|
| ------ | ------ |
| method | DELETE |
| Access | Admin|


  - /api/employees/emp_id

| Description | get employee details of given id|
| ------ | ------ |
| method | GET |
| Access | Admin, user with emp_id |
