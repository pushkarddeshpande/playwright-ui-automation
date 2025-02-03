playwright-ui-automation
/* To Run Playwright tests for html playwright reporter */
npx playwright test 
/* To Run Playwright tests with line allure playwright reporter */
npx playwright test --reporter=line, allure-playwright 
npx allure generate ./allure-results 
npx allure open ./allure-report
