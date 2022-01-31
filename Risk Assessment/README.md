# Risk Assessment

## Introduction
During the course of development, a series of risks were identified. The below table shows the initial severity, followed by the residual severity following the implementation of mitigation steps.

## Risk Assessment Matrix

| Risk                                                      | Likelihood (1-5) | Severity (1-5) | Mitigation Measures                                                                                                                                                                                | Residual Likelihood (1-5) | Residual Severity (1-5) |
|-----------------------------------------------------------|------------------|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|-------------------------|
| Untested code is pushed into production.                  | 3                | 5              | GitHub Actions have been configured to ensure that all code pushed to the `main` branch is subjected to automated testing. Pull Requests containing failed code cannot be approved until resolved. | 1                         | 5                       |
| Code is not compatible with specific software versions.   | 2                | 4              | Automated testing will be conducted on all major releases of Python 3.x.                                                                                                                           | 1                         | 5                       |
| Sudden unavailability of development staff.               | 3                | 5              | Code is to be developed in an open-source environment, ensuring all comments are descriptive so other developers can maintain code.                                                                | 2                         | 5                       |
| Product is delivered with un-met requirements.            |                  |                |                                                                                                                                                                                                    |                           |                         |
| Product cannot be delivered within the agreed timeframes. |                  |                |                                                                                                                                                                                                    |                           |                         |

## Guidance Notes

## References
