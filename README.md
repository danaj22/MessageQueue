# MessageQueue

My application to get skills in working with RabbitMQ

To run:

docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management

cd ./Receive
dotnet run

cd ./Send
dotnet run


Tech Stack:

RabbitMQ
.NET 5
