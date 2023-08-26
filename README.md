# Chatapplication_using_aws_services

# Real-Time Chat Application using AWS WebSocket API and Lambda Functions

This project showcases the development of a real-time chat application that leverages the power of AWS WebSocket API, Lambda functions, and EC2 instances. The application allows users to engage in instant messaging through terminal-based EC2 instances and command lines interfaces.


## Project Description

This project demonstrates the seamless integration of cloud services, serverless functions, and traditional computing resources to create a robust real-time chat application. The application is accessible through cli and EC2 instances, catering to a wide range of users.

## Technologies Used

- **Cloud Service Provider:** Amazon Web Services (AWS)
- **Back-end:** AWS Lambda functions
- **WebSocket API:** AWS WebSocket API
- **EC2 Instances:** Amazon EC2

## Features

- Real-time message exchange through WebSocket communication.
- Seamless integration with EC2 instances for terminal-based chatting.
- connection management.
- Private messaging and group conversations.

## Getting Started

To get started with the chat application, follow these steps:

1. Clone this repository to your local machine.
2. Configure AWS credentials and permissions for Lambda functions.
3. Deploy the Lambda functions and WebSocket API using AWS services.
4. launch EC2 instances or cli to connect to the chat application.

## Usage

1. launch EC2 instances or use Command line interface to access the chat application.
2. To connect via EC2 instances or cli:
   install wscat: you can use this command "npm install -g wscat"
3. connect to the chat application using "wscat -c websocket-api url".
4. after connecting to the chat application:
5.   you can set your name using {"action":"setName","name":"enter your name "}.
6.   after that you can send public messages : {"action":"sendPublic","message":"enter message"}.
7.   to send Private message : {"action":"sendPrivate","message":"enter private message","to":"enter the person name you wanna send"}.
8.   you can disconnect from the chat application by clicking "ctrl+c".


