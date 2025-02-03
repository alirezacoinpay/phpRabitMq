# RabbitMQ PHP Producer

This project demonstrates how to send messages to a RabbitMQ queue using PHP and the `PhpAmqpLib` library. It establishes a connection to a RabbitMQ server and sends messages to a specified queue.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **RabbitMQ Server**: Make sure RabbitMQ is installed and running on your machine on port 5672 . You can download it from [RabbitMQ's official website](https://www.rabbitmq.com/download.html).
- **Erlang**: RabbitMQ requires Erlang to be installed. You can find the installation guide on [Erlang's website](https://www.erlang.org/downloads).
- **PHP**: Ensure you have PHP installed (preferably PHP 7.0 or higher).
- **Composer**: Install Composer for managing PHP dependencies. You can download it from [getcomposer.org](https://getcomposer.org/download/).

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/alirezacoinpay/phpRabitMq.git
   cd YOUR_REPOSITORY_NAME

2. Install the required dependencies:
   ```bash
   composer install

## Usage
 Run the Workers :
   ```bash
   php worker.php
   ```

   and then Run the Producer :
   ```bash
   php new_task.php
   ```
   
### Or You Can Do This Instead
this is a simpler way to test the rabbitMQ

Run the Worker :
   ```
   php worker.php
   ```

and then Run the Producer :
   ```
   php send.php
   ```