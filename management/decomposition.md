# Decomposition

Software development is an unpredictable process and contains a lot of tasks that are hard to estimate upfront. It’s better to have more small tasks than less big ones. [Source](https://doitsmartly.ru/all-articles/management/99-agile/117-decomposition-techniques.html)

## Approaches

- Horizontal
  - Development -> testing -> documentation.
- Vertical
  - Feature 1 -> feature 2 -> feature 3.
  - Benefits:
    - Feature can be implemented, tested and demonstrated to customers.
    - Implemented feature can be used in feature for estimation and prioritization of other features.
    - Difficulties can be revealed because Dev, QA etc. participate in implementation.

## Methods

| Method                                                      | Description                                                                                                |
| ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Breakdown into stages \ phases of a business process        | Login, View, Buy, Notification. The process is understandable. Implementation of stages can be prioritized |
| Positive and negative scenario breakdown                    | Helps to highlight, analyze and plan exceptional scenarios                                                 |
| Breakdown by the rules \ conditions of the business process | Helps to highlight, analyze and plan exceptional cases of business processes                               |
| Breakdown by type of operation                              | CRUD                                                                                                       |
| Decomposition by platform / OS type                         | Devices, OS, browsers Example: Browsers -> mobile devices                                                  |
| Breakdown by data types and parameters                      | Example: search by text, numbers, regexp                                                                   |
| Roles / Permissions                                         | Customer view, Admin view, User view                                                                       |
| Decomposition of test scripts \ test cases                  | Benefits: Easy to understand, Result can be considered as a description for user story, Uses methods above |
