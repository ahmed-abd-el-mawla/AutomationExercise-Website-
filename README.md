# AutomationExercise-Website

## Description

A test automation project using selenium and Rest Assured for web application and API testing. The project is designed to be modular and customizable, allowing easy adaptation to different project requirements. It includes features such as parallel execution, data-driven testing, cross-browser testing, CI/CD integration, and custom reporting.


## 🚀 Features  

- **Web Application Testing:** Utilize Selenium for robust and reliable browser automation.  
- **API Testing:** Leverage Rest Assured for seamless API testing with detailed assertions.   
- **Customizable Framework:** Modular design allows easy adaptation to different project requirements.  
- **Parallel Execution:** Speed up test execution with multi-threading support.  
- **Capture screenshots and video recordings** of test executions for better debugging.
- **Page Object Model (POM):** Implement the POM design pattern for better maintainability and readability.
- **Design Patterns:** Utilize design patterns like Singleton, Factory, and Builder for better code organization.
- **Data-Driven Testing:** Support for data-driven testing using JSON and Excel files.
- **Cross-Browser Testing:** Test across multiple browsers and platforms with ease.
- **CI/CD Integration:** Seamless integration with CI/CD tools like GitHub Actions for automated testing and deployment.
- **Custom Assertions:** Implement custom assertions for specific validation needs.
- **Soft Assertions:** Support for soft assertions to continue test execution even when some assertions fail.
- **Custom Waits:** Implement custom wait strategies for better synchronization.
- **Custom Listeners:** Implement custom listeners for enhanced reporting and logging.
- **Custom Test Environment:** Support for multiple test environments (e.g., dev, staging, production) with environment-specific configurations.
- **Custom Test Reporting:** Generate custom test reports with detailed execution insights.
- **Custom Test Logging:** Implement custom logging strategies for better debugging and analysis.
- **Custom Test Utilities:** Implement custom utility classes for common tasks (e.g., file handling, JSON parsing, etc.).
- **Custom Test Framework:** Build a custom test framework with reusable components and utilities.


## 🛠️ Tools & Technologies  

- **Selenium:** Browser automation for web application testing.  
- **JUnit:** Test case structuring and execution.
- **TestNG:** Test case structuring and execution.  
- **Rest Assured:** API testing with simple and powerful HTTP request validation.  
- **Maven/Gradle:** Dependency management and build automation.  
- **Log4j:** Centralized logging for better debugging and analysis.  
- **Allure Reports:** Rich HTML reports with execution insights.
- **Faker:** Generate fake data for testing purposes.
- **Apache POI:** Read and write Excel files for data-driven testing.
- **JSON:** Data interchange format for API testing and configuration.
- **GitHub Actions:** CI/CD integration for automated testing and deployment.



```bash
## 📄 Project Structure
automation-exercise-test/  
├── .github
    ├── dependabot.yml
    └── workflows
    │   └── E2E Regression Pipeline.yml
├── .gitignore
├── pom.xml
└── src
    ├── main
        ├── java
        │   └── com
        │   │   └── automationexercices
        │   │       ├── FileUtils.java
        │   │       ├── apis
        │   │           ├── Builder.java
        │   │           └── UserManagementAPI.java
        │   │       ├── drivers
        │   │           ├── AbstractDriver.java
        │   │           ├── Browser.java
        │   │           ├── ChromeFactory.java
        │   │           ├── EdgeFactory.java
        │   │           ├── FirefoxFactory.java
        │   │           ├── GUIDriver.java
        │   │           ├── SafariFactory.java
        │   │           ├── UITest.java
        │   │           └── WebDriverProvider.java
        │   │       ├── listeners
        │   │           └── TestNGListeners.java
        │   │       ├── media
        │   │           ├── ScreenRecordManager.java
        │   │           └── ScreenshotsManager.java
        │   │       ├── pages
        │   │           ├── CartPage.java
        │   │           ├── CheckoutPage.java
        │   │           ├── ContactUsPage.java
        │   │           ├── DeleteAccountPage.java
        │   │           ├── LogoutPage.java
        │   │           ├── PaymentPage.java
        │   │           ├── ProductDetailsPage.java
        │   │           ├── ProductsPage.java
        │   │           ├── SignupLoginPage.java
        │   │           ├── SignupPage.java
        │   │           ├── TestCasesPage.java
        │   │           └── components
        │   │           │   └── NavigationBarComponent.java
        │   │       ├── utils
        │   │           ├── OSUtils.java
        │   │           ├── TerminalUtils.java
        │   │           ├── TimeManager.java
        │   │           ├── WaitManager.java
        │   │           ├── actions
        │   │           │   ├── AlertActions.java
        │   │           │   ├── BrowserActions.java
        │   │           │   ├── ElementActions.java
        │   │           │   └── FrameActions.java
        │   │           ├── dataReader
        │   │           │   ├── ExcelReader.java
        │   │           │   ├── JsonReader.java
        │   │           │   └── PropertyReader.java
        │   │           ├── logs
        │   │           │   └── LogsManager.java
        │   │           └── report
        │   │           │   ├── AllureAttachmentManager.java
        │   │           │   ├── AllureBinaryManager.java
        │   │           │   ├── AllureConstants.java
        │   │           │   ├── AllureEnvironmentManager.java
        │   │           │   └── AllureReportGenerator.java
        │   │       └── validations
        │   │           ├── BaseAssertion.java
        │   │           ├── Validation.java
        │   │           └── Verification.java
        └── resources
        │   ├── META-INF
        │       └── services
        │       │   └── org.testng.ITestNGListener
        │   ├── allure.properties
        │   ├── db.properties
        │   ├── environment.properties
        │   ├── extensions
        │       └── HaramBlur.crx
        │   ├── log4j2.properties
        │   ├── seleniumGrid.properties
        │   ├── video.properties
        │   ├── waits.properties
        │   └── webapp.properties
    └── test
        ├── java
            └── com
            │   └── automationexercices
            │       └── tests
            │           ├── BaseTest.java
            │           ├── api
            │               └── RegisterTestAPI.java
            │           └── ui
            │               ├── CartTest.java
            │               ├── CheckoutTest.java
            │               ├── InvoiceTest.java
            │               ├── LoginTest.java
            │               ├── PaymentTest.java
            │               ├── ProductDetailsTest.java
            │               ├── ProductsTest.java
            │               └── RegisterTest.java
        └── resources
            ├── downloads
                └── invoice.txt
            └── test-data
                ├── cart-data.json
                ├── checkout-data.json
                ├── login-data.json
                ├── product-details-data.json
                ├── products-data.json
                └── register-data.json

```

