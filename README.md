YouTube Data Harvesting and Warehousing
Overview:
This project aims to harvest data from YouTube using the YouTube Data API, warehouse it in a SQL database, and provide a user interface for interacting with the data using Streamlit. Docker is utilized for containerization and execution, ensuring portability and scalability of the application.

Components:
Data Harvesting: Data is collected from YouTube using the YouTube Data API, including video metadata, comments, likes, and other relevant information.
Warehousing: The harvested data is stored in a SQL database for efficient querying and retrieval. This allows for easy organization and management of the collected data.
User Interface: Streamlit is employed to create a user-friendly interface for users to interact with the stored data. Users can perform various queries and analysis on the YouTube data directly through the web interface.
Dockerization: Docker containers are used to package the application along with its dependencies, ensuring consistency and ease of deployment across different environments.
Setup and Execution:
Clone the repository to your local machine.
Ensure Docker is installed and running.
Build the Docker image using the provided Dockerfile.
Run the Docker container, exposing the necessary ports for accessing the Streamlit interface.
Access the application through your web browser and start exploring the YouTube data.
Dependencies:
YouTube Data API
SQL database (e.g., MySQL, PostgreSQL)
Streamlit
Docker
Future Enhancements:
Implement real-time data streaming for continuous updates.
Enhance user interface with additional visualizations and insights.
Implement user authentication and access control for secure data management.
