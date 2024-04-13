# Shopping Recommendation System

This project implements a robust product recommendation backend using Golang and Neo4j. The backend provides personalized product recommendations based on customer behavior and preferences.

## Features

- **Personalized Recommendations**: Offers personalized product suggestions tailored to individual customer preferences.
- **Efficient Data Storage**: Utilizes Neo4j graph database for efficient storage and retrieval of customer and product data.
- **Scalable Architecture**: Designed with scalability in mind to handle large volumes of customer and product data.
- **Algorithmic Recommendations**: Implements advanced recommendation algorithms to improve suggestion accuracy.
- **API Integration**: Provides easy-to-use APIs for loading test data, getting recommendations, adding products, and adding customers.

## Technologies Used

- **Golang**: Backend development language for its efficiency and concurrency support.
- **Neo4j**: Graph database used for storing and querying complex relationships between customers and products.
- **APIs**: Utilizes RESTful APIs for communication between frontend and backend systems.
- **Algorithms**: Incorporates recommendation algorithms for generating personalized suggestions.
- **GitHub**: Hosted on GitHub for version control and collaboration.

## Usage

### Load Test Data

To load test data into the system, send a request as shown in the [testData.png](./testData.png) image.

### Get Recommendations

To get recommendations, send a request with the appropriate parameters (e.g., `customerId`, `type`) as depicted in the [rec.png](./rec.png) image.

### Add Products

To add products to the system, send a request as demonstrated in the [ap.png](./ap.png) image.

### Add Customers

To add customers, send a request as illustrated in the [ac.png](./ac.png) image.

## Neo4j Graph

The structure of the Neo4j graph used in the project can be visualized in the [graph.png](./graph.png) image.

## Contribution

Contributions are welcome! If you'd like to contribute to the project, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
