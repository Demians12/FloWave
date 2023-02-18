# FloWave
The distributed video streaming application is an opensource system project that allows large numbers of people to watch streaming video content simultaneously. It uses a variety of technologies, including Apache Kafka and Apache Cassandra for messaging and data storage, FFmpeg for encoding and streaming video content, and NGINX as a web server and load balancer to distribute traffic between different instances.

The application is hosted on AWS using the Elastic Kubernetes Service (EKS), which provides an easy way to deploy and manage Kubernetes clusters for the different components of the application. The infrastructure is managed using Terraform, which allows for easy automation and management of the infrastructure.

The design of the application includes multiple clusters of EKS, Kafka, and Cassandra, each in their own private subnets within a VPC on AWS. The clusters are spread across different availability zones to ensure high availability and redundancy.
Overall, the distributed video streaming application is designed to be highly scalable, highly available, and easy to manage, providing a reliable and efficient way to stream video content to a large number of users.
