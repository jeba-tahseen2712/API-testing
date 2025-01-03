## Automated-Testing-of-Student Information Management System-with-Newman-Report

<p>This project showcases API testing using Postman, offering a comprehensive collection of tests designed to validate and verify the functionality of various API endpoints. The tests aim to ensure the reliability, correctness, and performance of the API by covering a wide range of scenarios and use cases.</p>

## Features

- Tests for `GET`, `POST`, `PUT`, `DELETE` requests
- Collection of tests covering various API endpoints
- Environment setup for seamless switching between environments
- Pre-request scripts for data initialization
- Test scripts for assertions and validations

## API Documentation

- [[https://documenter.getpostman.com/view/13082503/2sA2xmUAJ1](https://thetestingworldapi.com)].

## Technology Used

- **Postman**
- **Newman**

## Prerequisites

1. **Node.js**  
2. **Newman**
3. **Newman HTML Report Library**


## Installation

### 1. Postman
If you haven't already, [download and install Postman](https://www.postman.com/downloads/).
### 2. Clone the Repository
Clone this repository to your local machine:  
```bash
git clone https://github.com/jeba-tahseen2712/API-testing.git
```
### 3. Import the Postman Collection
-Open Postman.
-Click on the Import button.
-Select the Postman collection file from the cloned repository.
### 4. Import the Postman Environment
-In Postman, click on the gear icon in the top-right corner.
-Select **Import** and choose the Postman environment file from the cloned repository.

### 5. Newman and Report Installation:<br>
-Install Newman globally & Newman Html Report Install Command:
```bash
npm install -g newman
npm install -g newman-reporter-htmlextra
```

## Usage

### 1. Select Environment
- In **Postman**, choose the appropriate environment (e.g., Development, Production) from the dropdown menu in the top-right corner.

### 2. Run Collection
1. Select the imported collection from the **Collections** sidebar.
2. Click on the **Runner** button to open the Collection Runner.
3. Choose the desired environment.
4. Click **Start Test** to execute the collection.

### 3. View Results
- Once the tests are complete, view the results in the **Runner** tab.
- Detailed test results can be reviewed for each request.

