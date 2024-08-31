# Architecture Selection for API: REST vs GraphQL

## Project Overview

This project presents a comprehensive comparative analysis of REST and GraphQL APIs, focusing on their performance in handling multiple concurrent users and various data request types. The decision between using REST or GraphQL often poses a significant challenge, as the choice can significantly impact the performance, scalability, and overall user experience of an application. This study provides insights into the scalability and reliability of each API architecture across different domains and offers practical guidance on architectural selection.

## Team Members

- **Arsalan Imran** - Masters in Science, Computer Science, Bishop’s University
- **Dan Luo** - Masters in Science, Computer Science, Bishop’s University
- **Guan Wang** - Masters in Science, Computer Science, Bishop’s University

## Key Features

- **Comparative Analysis**: We evaluated REST and GraphQL APIs based on key performance metrics such as throughput, response times, and error rates using a dataset of 1,500 responses across 15 different business areas.
- **Use Case Identification**: The project identifies specific use cases where either REST or GraphQL excels, providing developers with data-driven insights to make informed decisions.
- **Performance Modeling**: A Random Forest regression model was trained to predict the performance metrics, helping to recommend the best API architecture for different business needs and user loads.
- **Practical Implementation**: We built two CRUD-based applications using REST and GraphQL, comparing their performance under various conditions to highlight the strengths and weaknesses of each architecture.

## Methodology

1. **Data Collection**: Collected data from 150 REST APIs and 150 GraphQL APIs across 15 categories, including Animal, Art & Design, Business, and more.
2. **Load Testing**: Used JMeter to test APIs with varying user loads (1, 20, 50, 100, and 1000 concurrent users).
3. **Statistical Analysis**: Conducted statistical significance tests on average response times, throughput, and error rates.
4. **Performance Modeling**: Employed a Random Forest model to predict API performance and provide recommendations based on specific use cases.

## Findings

- **REST APIs**: Generally offered higher throughput and data transmission rates, making them preferable for applications requiring high throughput.
- **GraphQL APIs**: Showed more stable response times and lower error rates, making them advantageous for applications where efficient data retrieval and reliability are critical.
- **CRUD Comparison**: REST APIs demonstrated better performance in CRUD-based applications, while GraphQL APIs were found to be more reliable with fewer errors.

## Conclusion

The choice between REST and GraphQL should depend on the specific requirements of the application. REST is preferable for scenarios demanding high throughput, while GraphQL is better suited for applications where efficient data retrieval and stability are critical.

## References

- REST or GraphQL? A Performance Comparative Study, Universidade Federal do Pará, Brasil.
- Facebook Inc., “GraphQL specification (draft),” 2015.
- R. T. Fielding, “Architectural styles and the design of network-based software architectures,” University of California, 2000.

## How to Use

To explore the findings and data, clone this repository and review the provided datasets, code, and documentation. The project includes both the data collected for analysis and the implementation of the comparative CRUD applications in REST and GraphQL.

