# Nawy-Task
 "https://www.demoblaze.com/"

playwright-project/ Structure (POM) 

├── tests/               # Folder containing all test files#
│   ├── addToCart.spec.js  
│   ├── userLogin.spec.js    
│   ├── userLogout.spec.js 
│   ├── userRegister.spec.js 

├── pages/               # Folder containing all Locators and Actions for each page#
│   ├── basePage.js  
│   ├── cartPage.js    
│   ├── homePage.js 
│   ├── registerPage.js
│   ├── loginPage.js

├── TestData/               # Folder containing all Data that test case needs#
│   ├── registrationData.js  
│   ├── cartTestData.js    
│   ├── loginData.js 
        
├── playwright.config.js # Playwright configuration file
├── package.json         # Project dependencies and scripts
├── package-lock.json    # Auto-generated dependency lock file
└── node_modules/        # Installed Node.js dependencies
│   ├── faker.js		  # dependency that use to generate random data that make script reusable 

To run the below scenarios you can use this command " npx playwright test ".

● Scenario 1: The user can register with valid data.
● Scenario 2: The user can log in with a valid email and password.
● Scenario 3: The user can log out.
● Scenario 4: Successfully create an order for an Apple monitor 24 
