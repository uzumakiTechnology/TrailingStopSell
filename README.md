
# Trailing Stop Sell Order System
## Getting Started

#### Python 3.9.18
#### Apache Kafka 1.3.5
#### ReactJS 18
#### Apache Cassandra  Latest Version

## Cloning Repository

``` git clone https://github.com/uzumakiTechnology/TrailingStopSell.git```








## Authors

- [@Nguyen Hoang Anh Tuan - ITITIU19233](https://www.github.com/atuans)



## Documentation

* [Installing and Set up Apache Cassandra](https://cassandra.apache.org/doc/latest/cassandra/installing/installing.html)
* [Installing and Set up Apache Spark](https://cassandra.apache.org/doc/latest/cassandra/installing/installing.html)
* [Installing and Set up Apache Kafka with Docker Desktop](https://www.conduktor.io/kafka/how-to-start-kafka-using-docker/)
* [Installing and Set up FastAPI and Postman](https://www.postman.com/solar-shuttle-642701/workspace/fastapi-tutorial/overview)

In order to avoid the conflict of version, py-env will be recommended, py-env can easily using directly in the project which already attached, just `copy path` of the `bin`  folder in myenv folder then run the command `source your_path/activate`

For exmaple, with my set up, I will get the path look like 
``source /Users/ITITIU19233/trailing_stop_sell/myenv/bin/activate``

After installing the  requirement tech, forward to ``main`` folder and enter command : ```pip install -r requirements.txt```

On `Front-end` side, move forward to frontends folder and type command `npm install`


## Demo

To run and Test the usage of the system, run both file `kafka_producer.py` and `data_processings.py`, the first file will responsible for generating the simulator when the second file will processing the data.

#### Run 
```bash
python3 kafka_producer.py 
```
#### Run 

```bash
python3 data_processings.py 
```

#### Review the change made on Cassandra local server

```bash
select * from orders;
```



### Monitoring Interface 

#### Forward to src folder on frontends folder, run:

```bash
yarn dev
```

or 

```bash
npm start
```

## Learn More

#### Learn about Kafka, and system model of Kafka, Spark and Cassandra:

* [Apache Model on Real-time system](https://medium.com/building-the-open-data-stack/build-an-event-driven-architecture-with-apache-kafka-apache-spark-and-apache-cassandra-6f0fc0c87e42)
* [How to choose and evaluation](https://opensource.com/article/20/2/real-time-data-processing)

#### React
To learn more about React, take a look at the following resources:

- [React Documentation](https://react.dev/) - learn about React features.
- [Learn React](https://react.dev/learn) - an interactive React tutorial.

You can check out [React GitHub repository](https://github.com/facebook/react/releases) - your feedback and contributions are welcome!
