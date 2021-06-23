

<!-- ABOUT THE PROJECT -->
## About The Project

[![Load Testing][product-screenshot]](https://example.com)

The project is aimed at getting started with load testing a microservice before taking it to production. We use FastAPI microservice (to predict weather) and Locust to load test the service (locally or on cloud).



### Built With

Major frameworks used to build the project:
* [FastAPI](https://fastapi.tiangolo.com/)
* [Docker](https://www.docker.com/)
* [Locust](https://locust.io/)



<!-- GETTING STARTED -->
### Installation

These are instructions to install and get the services up and running. 

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
2. Install Locust.io
   ```sh
   pip install locust
   ```   
3. Go to FastAPI_microservice folder and build the FastAPI service docker image 
   ```sh
   docker build -t fastapi .
   ```
4. Run the FastAPI service docker container locally
   ```sh
   docker run -d -p 80:80 fastapi
   ```
5. Go to Load_testing folder and run locust.io service for load testing
   ```sh
   Locust -f load_test-py
   ```   




<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Emmanuel Raj - [Linkedin](https://twitter.com/your_username) 

Project Link: [https://github.com/emmanuelraj7/mlopscommunity_meetup](https://github.com/emmanuelraj7/mlopscommunity_meetup)

Engineering MLOps (book): [Amazon](https://www.amazon.com/Engineering-MLOps-Rapidly-production-ready-learning/dp/1800562888)