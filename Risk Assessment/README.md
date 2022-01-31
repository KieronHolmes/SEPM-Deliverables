# Risk Assessment

## Introduction
During the course of development, a series of risks were identified. The below table shows the initial severity, followed by the residual severity following the implementation of mitigation steps.

## Risk Assessment Matrix

| Risk                                     | Likelihood (1-5) | Severity (1-5) | Mitigation Measures                                                                                                                                                                                | Residual Likelihood (1-5) | Residual Severity (1-5) |
|------------------------------------------|------------------|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|-------------------------|
| Untested code is pushed into production. | 3                | 5              | GitHub Actions have been configured to ensure that all code pushed to the `main` branch is subjected to automated testing. Pull Requests containing failed code cannot be approved until resolved. | 1                         | 5                       |
