# Product Recommendation System

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

## Screenshots

<img width="1496" alt="Screenshot 2024-04-12 at 12 40 53 AM" src="https://github.com/ameyagidh/GoRecommendation-System/assets/65457905/b06ba73a-327b-4bc1-9015-97a3cd094e78">
<img width="1496" alt="Screenshot 2024-04-12 at 12 40 40 AM" src="https://github.com/ameyagidh/GoRecommendation-System/assets/65457905/d61ea370-3655-4637-961a-5a14f5ee9ecd">
<img width="1496" alt="Screenshot 2024-04-12 at 12 40 27 AM" src="https://github.com/ameyagidh/GoRecommendation-System/assets/65457905/d5eee207-94ad-42e9-a055-98051aba1a2d">
<img width="1496" alt="Screenshot 2024-04-12 at 12 43 13 AM" src="https://github.com/ameyagidh/GoRecommendation-System/assets/65457905/069e7e09-ba5f-4707-8a09-496554ca767b">
<img width="1496" alt="Screenshot 2024-04-12 at 12 42 54 AM" src="https://github.com/ameyagidh/GoRecommendation-System/assets/65457905/7c79a64b-cb98-4bf8-8875-dc6a562f32e9">
<img width="1496" alt="Screenshot 2024-04-12 at 12 42 48 AM" src="https://github.com/ameyagidh/GoRecommendation-System/assets/65457905/629aa6be-b7c6-4e20-8b7e-4ed819220288">
<img width="1496" alt="Screenshot 2024-04-12 at 12 41 03 AM" src="https://github.com/ameyagidh/GoRecommendation-System/assets/65457905/48e83305-f8c5-4c8f-bca6-1a92e80c5d3c">

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
