Common Java Utility Library for Shared Features
Purpose:

Across all our applications, we have some common features which are currently developed individually for each application.
Creating a common library for these features will save development time, reduce redundancy, and enhance stability.
By standardizing these functionalities, we can ensure consistency and improve maintainability across our projects.


## Common Java Utility Library

This library provides a set of common utilities and frameworks to standardize and streamline development across all our Java projects. By using this library, we can reduce redundancy, save development time, and improve stability and maintainability.

### Features

| Feature                             | Objective                                                                                 | Implementation                                                                                                          |
|-------------------------------------|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| **Common Auditing Framework**       | Track and log entity changes across all applications.                                     | Leverage Spring Audit Framework, create a wrapper, and implement a common API for change history logs.                |
| **Dynamic Property/Config Updates** | Enable dynamic updates to application properties or configurations without restarting.    | Use a centralized configuration service or library that supports hot-reloading of configurations.                      |
| **Concurrency and Session Handling**| Provide standardized concurrency, session authentication, and lazy loading.               | Develop concurrency utilities and services to manage session states, authenticate sessions, and support lazy loading.  |
| **Common Logging Configuration**    | Standardize logging using annotations and a log roller.                                   | Create a logging service that uses annotations and includes a log roller for log file rotation and management.         |
| **Role-Based Authentication API**   | Implement common authentication and authorization framework for RBAC.                     | Develop a unified API for managing user roles and permissions, ensuring consistent security practices.                 |
| **Common Input Validations**        | Provide standardized input validation utilities for API requests.                         | Create reusable validation annotations and methods to enforce data integrity and validation rules.                     |
| **Common Upload/Download Processor**| Streamline file upload and download processes.                                            | Develop utilities to manage file uploads and downloads, including validation, storage, and retrieval functionalities.   |
| **Common Batch Query Runner**       | Facilitate efficient execution of batch database operations.                              | Create a batch query runner utility to handle large-scale database operations, ensuring optimal performance and error handling. |
| **Common Notification Service**     | Provide a standardized way to send notifications (email, SMS, push notifications).         | Develop a unified notification service with support for various channels and customizable templates.                   |
| **Common Retry Mechanism**          | Implement a consistent retry mechanism for transient failures.                            | Create a utility that automatically retries failed operations with configurable retry policies and backoff strategies. |
| **Common Rate Limiting**            | Ensure applications respect rate limits for API requests and other operations.             | Develop a rate limiting service that can be applied to methods or APIs to enforce limits and prevent abuse.            |
| **Common Metrics and Monitoring**   | Collect and report application metrics and health information.                            | Integrate with a monitoring system (e.g., Prometheus, Grafana) to collect and visualize metrics and health checks.     |
| **Common Error Handling Framework** | Provide a standardized approach to error handling and reporting.                           | Develop a framework for consistent exception handling, logging, and user-friendly error messages.                      |
| **Common Data Transformation**      | Standardize data transformation (e.g., mapping DTOs to entities).                         | Create utilities for common data transformation tasks using libraries like MapStruct.                                  |
| **Common Encryption Utilities**     | Provide utilities for encryption, decryption, and secure storage of sensitive data.        | Develop a set of encryption utilities using standard algorithms and libraries.                                         |
| **Common Scheduler**                | Standardize task scheduling and execution across applications.                            | Implement a scheduling service using Quartz or Spring Scheduler for running tasks at specified intervals.              |
| **Common Feature Toggle Service**   | Manage feature toggles to enable/disable features dynamically.                            | Develop a feature toggle service to control feature availability without redeploying applications.                     |
| **Common Localization Framework**   | Standardize internationalization and localization support.                                | Create utilities for managing localized messages and resources across applications.                                    |
| **Common API Client**               | Provide a standardized way to interact with external APIs.                                 | Develop a common API client library with consistent error handling and retry mechanisms for external service integration.|
| **Common Pagination and Sorting**   | Standardize pagination and sorting for API responses.                                     | Create utilities to handle pagination and sorting logic, ensuring consistent API responses.                            |

