# real-time-data-streaming-pipeline-dashboard

End to End Real Time Streaming Data Engineering System and Dashboard

Proposal:

Most up-to-date real time stock market information is critical to develop winning trading strategies and when combined with real time news sentiment gives you a better picture to make profitable buy/sell trading decisions.  We aim to bring reliable real time stock market analysis in an easy to use dashboard.

DataSources:

In this project we would be extracting real time stock market data  from Market Data API  and Alpaca Markets Websocket Stream API  and real-time news via News API websockets. 

We also make use of premier sources for financial, economic and alternative datasets.  Static Public Data Sources like  NASDAQ , Google Finance etc.,

Github: https://github.com/snehac-miner/real-time-data-streaming-pipeline-dashboard.git

Technical Implementation Details:

We will be building a real-time data streaming pipeline with multiple datasets which constitute several million records. Real Time Market data from websocket API gets produced into Kafka broker, consumes data from Kafka with Apache Flink and finally gets streamed into Kafka output stream and finally gets written into postgres or snowflake. For any datasets if needed we can TCP/IP for data transmission over Socket and batch process using Spark. New sentimental analysis is performed using Open API LLMs.  A real-time analytics dashboard is published using Apache Flink or elastic search with Kibana etc. This dashboard and data pipeline is published to the cloud and automated. Dashboard can be accessed via a web URL. 


High Level System Architecture Diagram:

