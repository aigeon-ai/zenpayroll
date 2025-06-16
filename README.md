# ZenPayroll MCP Server

## Overview

ZenPayroll is a modern, delightful payroll solution designed to simplify the complexities of payroll management for businesses. With ZenPayroll, companies can easily set up and run payroll from any web-enabled device in just a few minutes. Our service ensures that all government payroll taxes, reporting, and compliance requirements are handled automatically and paperlessly.

The ZenPayroll MCP Server transforms payroll into a versatile platform that seamlessly integrates with HR, time tracking, accounting, and other crucial back-office functions. This integration improves efficiency and enhances data quality by enabling systems to communicate effectively with payroll processes. In the long term, this opens up innovative ways to manage work and compensate employees, such as dynamic sales incentives or real-time employee rewards.

## Key Features

- **Seamless Integration**: Connect ZenPayroll with various applications to enhance back-office operations.
- **Automatic Compliance**: All government payroll taxes, reporting, and compliance are managed automatically.
- **Efficient Payroll Setup**: Set up and run payroll effortlessly from any web-enabled device.
- **Improved Data Quality**: Enable systems to "talk" to payroll for better data exchange and accuracy.

## Tool List

ZenPayroll offers a range of tools designed to manage different aspects of payroll and employee information. Below is a list of available tools and their functionalities:

1. **User Information**
   - **Function**: `/api/v1/me`
   - **Description**: Retrieves information about the currently authenticated user.

2. **Company Information**
   - **Function**: `/api/v1/companies/:company_id`
   - **Description**: Provides details about a particular company.

3. **Pay Periods**
   - **Function**: `/api/v1/companies/:company_id/pay_periods`
   - **Description**: Lists all pay periods, both past and current, for a specified company.

4. **Employee Information**
   - **Function**: `/api/v1/companies/:company_id/employees`
   - **Description**: Returns an array of all employees currently employed with the specified company.

## Tool Declarations

Each function within the ZenPayroll MCP Server has specific parameters to ensure flexible and comprehensive data retrieval:

- **User Information Function**
  - Parameter: `access_token` (String) - Automatically populated based on authorization settings.

- **Company Information Function**
  - Parameter: `access_token` (String) - Automatically populated based on authorization settings.

- **Pay Periods Function**
  - Parameters:
    - `access_token` (String) - Automatically populated.
    - `start_date` (String) - Optional parameter.
    - `end_date` (String) - Optional parameter.

- **Employee Information Function**
  - Parameter: `access_token` (String) - Automatically populated based on authorization settings.

## Conclusion

ZenPayroll MCP Server is designed to streamline payroll processes, integrate seamlessly with various applications, and enhance overall business efficiency. Explore the tools available to see how ZenPayroll can benefit your organization.