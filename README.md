# Python Application

This repository contains a Python application that is set up to automatically install dependencies, run tests, and perform linting using GitHub Actions.

## Features

- **Continuous Integration**: Automatically runs tests and linting on every push and pull request to the main branch.
- **Python 3.10**: The application is set up to run with Python version 3.10.
- **Linting and Testing**: Uses `flake8` for linting and `pytest` for running tests.

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

Make sure you have Python 3.10 installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
2.  Install the required dependencies:
bash

python -m pip install --upgrade pip
pip install flake8 pytest
if [ -f requirements.txt ]; then pip install -r requirements.txt; fi

Running Tests
To run the tests, use the following command:

bash
pytest

Logging Information
The application logs various events, including startup, shutdown, and command executions. Below is an example of the log output:

2024-10-18 12:06:23,709 - root - INFO - Built-in commands registered.
2024-10-18 12:06:23,709 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:06:23,709 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:06:23,709 - root - INFO - Application shutdown.
2024-10-18 12:06:23,712 - root - INFO - Built-in commands registered.
2024-10-18 12:06:23,712 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:06:23,712 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:06:23,712 - root - INFO - Application shutdown.
2024-10-18 12:06:23,743 - root - INFO - Built-in commands registered.
2024-10-18 12:06:23,743 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:06:23,743 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:06:23,743 - root - INFO - Application interrupted by user.
2024-10-18 12:06:23,743 - root - INFO - Application shutdown.
2024-10-18 12:06:23,746 - root - INFO - Built-in commands registered.
2024-10-18 12:06:23,746 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:06:23,746 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:06:23,746 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:06:23,746 - root - INFO - Application shutdown.
2024-10-18 12:07:53,969 - root - INFO - Built-in commands registered.
2024-10-18 12:07:53,969 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:07:53,969 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:07:53,969 - root - INFO - Application shutdown.
2024-10-18 12:07:53,972 - root - INFO - Built-in commands registered.
2024-10-18 12:07:53,972 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:07:53,972 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:07:53,972 - root - INFO - Application shutdown.
2024-10-18 12:07:54,004 - root - INFO - Built-in commands registered.
2024-10-18 12:07:54,004 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:07:54,004 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:07:54,004 - root - INFO - Application interrupted by user.
2024-10-18 12:07:54,005 - root - INFO - Application shutdown.
2024-10-18 12:07:54,008 - root - INFO - Built-in commands registered.
2024-10-18 12:07:54,008 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:07:54,008 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:07:54,008 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:07:54,008 - root - INFO - Application shutdown.
2024-10-18 12:10:58,486 - root - INFO - Built-in commands registered.
2024-10-18 12:10:58,487 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:10:58,487 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:10:58,487 - root - INFO - Application shutdown.
2024-10-18 12:10:58,490 - root - INFO - Built-in commands registered.
2024-10-18 12:10:58,490 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:10:58,490 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:10:58,490 - root - INFO - Application shutdown.
2024-10-18 12:10:58,521 - root - INFO - Built-in commands registered.
2024-10-18 12:10:58,521 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:10:58,521 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:10:58,521 - root - INFO - Application interrupted by user.
2024-10-18 12:10:58,521 - root - INFO - Application shutdown.
2024-10-18 12:10:58,525 - root - INFO - Built-in commands registered.
2024-10-18 12:10:58,525 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:10:58,525 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:10:58,525 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:10:58,525 - root - INFO - Application shutdown.
2024-10-18 12:11:08,648 - root - INFO - Built-in commands registered.
2024-10-18 12:11:08,648 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:08,649 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:08,649 - root - INFO - Application shutdown.
2024-10-18 12:11:08,651 - root - INFO - Built-in commands registered.
2024-10-18 12:11:08,652 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:08,652 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:08,652 - root - INFO - Application shutdown.
2024-10-18 12:11:08,681 - root - WARNING - Skipping plugin 'greet' due to import error.
2024-10-18 12:11:08,687 - root - INFO - Built-in commands registered.
2024-10-18 12:11:08,687 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:08,687 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:08,688 - root - INFO - Application interrupted by user.
2024-10-18 12:11:08,688 - root - INFO - Application shutdown.
2024-10-18 12:11:08,691 - root - INFO - Built-in commands registered.
2024-10-18 12:11:08,691 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:08,691 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:08,691 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:11:08,691 - root - INFO - Application shutdown.
2024-10-18 12:11:14,460 - root - INFO - Built-in commands registered.
2024-10-18 12:11:14,460 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:14,460 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:14,460 - root - INFO - Application shutdown.
2024-10-18 12:11:14,463 - root - INFO - Built-in commands registered.
2024-10-18 12:11:14,463 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:14,463 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:14,463 - root - INFO - Application shutdown.
2024-10-18 12:11:14,491 - root - WARNING - Skipping plugin 'greet' due to import error.
2024-10-18 12:11:14,497 - root - INFO - Built-in commands registered.
2024-10-18 12:11:14,497 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:14,498 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:14,498 - root - INFO - Application interrupted by user.
2024-10-18 12:11:14,498 - root - INFO - Application shutdown.
2024-10-18 12:11:14,500 - root - INFO - Built-in commands registered.
2024-10-18 12:11:14,501 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:14,501 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:14,501 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:11:14,501 - root - INFO - Application shutdown.
2024-10-18 12:11:19,979 - root - INFO - Built-in commands registered.
2024-10-18 12:11:19,979 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:19,979 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:19,979 - root - INFO - Application shutdown.
2024-10-18 12:11:19,982 - root - INFO - Built-in commands registered.
2024-10-18 12:11:19,982 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:19,982 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:19,982 - root - INFO - Application shutdown.
2024-10-18 12:11:20,011 - root - WARNING - Skipping plugin 'greet' due to import error.
2024-10-18 12:11:20,017 - root - INFO - Built-in commands registered.
2024-10-18 12:11:20,018 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:20,018 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:20,018 - root - INFO - Application interrupted by user.
2024-10-18 12:11:20,018 - root - INFO - Application shutdown.
2024-10-18 12:11:20,020 - root - INFO - Built-in commands registered.
2024-10-18 12:11:20,020 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:20,020 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:20,020 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:11:20,021 - root - INFO - Application shutdown.
2024-10-18 12:11:55,494 - root - INFO - Built-in commands registered.
2024-10-18 12:11:55,495 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:55,495 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:55,495 - root - INFO - Application shutdown.
2024-10-18 12:11:55,497 - root - INFO - Built-in commands registered.
2024-10-18 12:11:55,498 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:55,498 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:55,498 - root - INFO - Application shutdown.
2024-10-18 12:11:55,529 - root - INFO - Built-in commands registered.
2024-10-18 12:11:55,529 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:55,529 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:55,529 - root - INFO - Application interrupted by user.
2024-10-18 12:11:55,529 - root - INFO - Application shutdown.
2024-10-18 12:11:55,532 - root - INFO - Built-in commands registered.
2024-10-18 12:11:55,532 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:11:55,532 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:11:55,532 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:11:55,532 - root - INFO - Application shutdown.
2024-10-18 12:16:14,565 - root - INFO - Built-in commands registered.
2024-10-18 12:16:14,565 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:16:14,565 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:16:14,565 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:16:14,566 - root - INFO - Application shutdown.
2024-10-18 12:16:20,709 - root - INFO - Built-in commands registered.
2024-10-18 12:16:20,709 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:16:20,709 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:16:20,709 - root - INFO - Application shutdown.
2024-10-18 12:16:20,712 - root - INFO - Built-in commands registered.
2024-10-18 12:16:20,713 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:16:20,713 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:16:20,713 - root - INFO - Application shutdown.
2024-10-18 12:16:20,744 - root - INFO - Built-in commands registered.
2024-10-18 12:16:20,744 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:16:20,744 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:16:20,744 - root - INFO - Application interrupted by user.
2024-10-18 12:16:20,745 - root - INFO - Application shutdown.
2024-10-18 12:16:20,747 - root - INFO - Built-in commands registered.
2024-10-18 12:16:20,747 - root - INFO - Plugin 'greet' loaded successfully.
2024-10-18 12:16:20,747 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:16:20,747 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:16:20,747 - root - INFO - Application shutdown.
2024-10-18 12:20:11,494 - root - INFO - Built-in commands registered.
2024-10-18 12:20:11,494 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:20:11,494 - root - INFO - Application shutdown.
2024-10-18 12:20:11,497 - root - INFO - Built-in commands registered.
2024-10-18 12:20:11,497 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:20:11,497 - root - INFO - Application shutdown.
2024-10-18 12:20:11,527 - root - INFO - Built-in commands registered.
2024-10-18 12:20:11,527 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:20:11,527 - root - INFO - Application interrupted by user.
2024-10-18 12:20:11,527 - root - INFO - Application shutdown.
2024-10-18 12:20:11,529 - root - INFO - Built-in commands registered.
2024-10-18 12:20:11,530 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:20:11,530 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:20:11,530 - root - INFO - Application shutdown.
2024-10-18 12:20:46,475 - root - INFO - Built-in commands registered.
2024-10-18 12:20:46,475 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:20:46,475 - root - INFO - Application shutdown.
2024-10-18 12:20:46,478 - root - INFO - Built-in commands registered.
2024-10-18 12:20:46,478 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:20:46,479 - root - INFO - Application shutdown.
2024-10-18 12:20:46,508 - root - INFO - Built-in commands registered.
2024-10-18 12:20:46,509 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:20:46,509 - root - INFO - Application interrupted by user.
2024-10-18 12:20:46,509 - root - INFO - Application shutdown.
2024-10-18 12:20:46,511 - root - INFO - Built-in commands registered.
2024-10-18 12:20:46,511 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:20:46,511 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:20:46,511 - root - INFO - Application shutdown.
2024-10-18 12:21:27,029 - root - INFO - Built-in commands registered.
2024-10-18 12:21:27,029 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:27,029 - root - INFO - Application shutdown.
2024-10-18 12:21:27,032 - root - INFO - Built-in commands registered.
2024-10-18 12:21:27,032 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:27,032 - root - INFO - Application shutdown.
2024-10-18 12:21:27,062 - root - INFO - Built-in commands registered.
2024-10-18 12:21:27,062 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:27,062 - root - INFO - Application interrupted by user.
2024-10-18 12:21:27,062 - root - INFO - Application shutdown.
2024-10-18 12:21:27,064 - root - INFO - Built-in commands registered.
2024-10-18 12:21:27,064 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:27,065 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:21:27,065 - root - INFO - Application shutdown.
2024-10-18 12:21:32,570 - root - INFO - Built-in commands registered.
2024-10-18 12:21:32,574 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:39,607 - root - INFO - Application shutdown.
2024-10-18 12:21:43,525 - root - INFO - Built-in commands registered.
2024-10-18 12:21:43,525 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:43,525 - root - INFO - Application shutdown.
2024-10-18 12:21:43,528 - root - INFO - Built-in commands registered.
2024-10-18 12:21:43,528 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:43,528 - root - INFO - Application shutdown.
2024-10-18 12:21:43,557 - root - INFO - Built-in commands registered.
2024-10-18 12:21:43,558 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:43,558 - root - INFO - Application interrupted by user.
2024-10-18 12:21:43,558 - root - INFO - Application shutdown.
2024-10-18 12:21:43,560 - root - INFO - Built-in commands registered.
2024-10-18 12:21:43,560 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:43,560 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:21:43,561 - root - INFO - Application shutdown.
2024-10-18 12:21:51,042 - root - INFO - Built-in commands registered.
2024-10-18 12:21:51,042 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:51,042 - root - INFO - Application shutdown.
2024-10-18 12:21:51,045 - root - INFO - Built-in commands registered.
2024-10-18 12:21:51,045 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:51,046 - root - INFO - Application shutdown.
2024-10-18 12:21:51,075 - root - INFO - Built-in commands registered.
2024-10-18 12:21:51,075 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:51,075 - root - INFO - Application interrupted by user.
2024-10-18 12:21:51,075 - root - INFO - Application shutdown.
2024-10-18 12:21:51,078 - root - INFO - Built-in commands registered.
2024-10-18 12:21:51,078 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:21:51,078 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:21:51,078 - root - INFO - Application shutdown.
2024-10-18 12:22:52,703 - root - INFO - Built-in commands registered.
2024-10-18 12:22:52,703 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:22:52,703 - root - INFO - Application shutdown.
2024-10-18 12:22:52,706 - root - INFO - Built-in commands registered.
2024-10-18 12:22:52,706 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:22:52,706 - root - INFO - Application shutdown.
2024-10-18 12:22:52,736 - root - INFO - Built-in commands registered.
2024-10-18 12:22:52,736 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:22:52,736 - root - INFO - Application interrupted by user.
2024-10-18 12:22:52,736 - root - INFO - Application shutdown.
2024-10-18 12:22:52,739 - root - INFO - Built-in commands registered.
2024-10-18 12:22:52,739 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:22:52,739 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:22:52,739 - root - INFO - Application shutdown.
2024-10-18 12:23:09,048 - root - INFO - Built-in commands registered.
2024-10-18 12:23:09,049 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:09,049 - root - INFO - Application shutdown.
2024-10-18 12:23:09,051 - root - INFO - Built-in commands registered.
2024-10-18 12:23:09,052 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:09,052 - root - INFO - Application shutdown.
2024-10-18 12:23:09,081 - root - INFO - Built-in commands registered.
2024-10-18 12:23:09,081 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:09,081 - root - INFO - Application interrupted by user.
2024-10-18 12:23:09,082 - root - INFO - Application shutdown.
2024-10-18 12:23:09,084 - root - INFO - Built-in commands registered.
2024-10-18 12:23:09,084 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:09,084 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:23:09,085 - root - INFO - Application shutdown.
2024-10-18 12:23:14,842 - root - INFO - Built-in commands registered.
2024-10-18 12:23:14,843 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:14,843 - root - INFO - Application shutdown.
2024-10-18 12:23:14,845 - root - INFO - Built-in commands registered.
2024-10-18 12:23:14,846 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:14,846 - root - INFO - Application shutdown.
2024-10-18 12:23:14,874 - root - INFO - Built-in commands registered.
2024-10-18 12:23:14,874 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:14,875 - root - INFO - Application interrupted by user.
2024-10-18 12:23:14,875 - root - INFO - Application shutdown.
2024-10-18 12:23:14,877 - root - INFO - Built-in commands registered.
2024-10-18 12:23:14,877 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:14,877 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:23:14,877 - root - INFO - Application shutdown.
2024-10-18 12:23:43,781 - root - INFO - Built-in commands registered.
2024-10-18 12:23:43,781 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:43,781 - root - INFO - Application shutdown.
2024-10-18 12:23:43,784 - root - INFO - Built-in commands registered.
2024-10-18 12:23:43,784 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:43,785 - root - INFO - Application shutdown.
2024-10-18 12:23:43,815 - root - INFO - Built-in commands registered.
2024-10-18 12:23:43,816 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:43,816 - root - INFO - Application interrupted by user.
2024-10-18 12:23:43,816 - root - INFO - Application shutdown.
2024-10-18 12:23:43,818 - root - INFO - Built-in commands registered.
2024-10-18 12:23:43,818 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:43,819 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:23:43,819 - root - INFO - Application shutdown.
2024-10-18 12:23:47,965 - root - INFO - Built-in commands registered.
2024-10-18 12:23:47,965 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:47,965 - root - INFO - Application shutdown.
2024-10-18 12:23:47,968 - root - INFO - Built-in commands registered.
2024-10-18 12:23:47,968 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:47,968 - root - INFO - Application shutdown.
2024-10-18 12:23:47,998 - root - INFO - Built-in commands registered.
2024-10-18 12:23:47,998 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:47,998 - root - INFO - Application interrupted by user.
2024-10-18 12:23:47,998 - root - INFO - Application shutdown.
2024-10-18 12:23:48,001 - root - INFO - Built-in commands registered.
2024-10-18 12:23:48,001 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:48,001 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:23:48,001 - root - INFO - Application shutdown.
2024-10-18 12:23:53,862 - root - INFO - Built-in commands registered.
2024-10-18 12:23:53,862 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:53,862 - root - INFO - Application shutdown.
2024-10-18 12:23:53,865 - root - INFO - Built-in commands registered.
2024-10-18 12:23:53,865 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:53,865 - root - INFO - Application shutdown.
2024-10-18 12:23:53,895 - root - INFO - Built-in commands registered.
2024-10-18 12:23:53,895 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:53,895 - root - INFO - Application interrupted by user.
2024-10-18 12:23:53,895 - root - INFO - Application shutdown.
2024-10-18 12:23:53,898 - root - INFO - Built-in commands registered.
2024-10-18 12:23:53,898 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:23:53,898 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:23:53,898 - root - INFO - Application shutdown.
2024-10-18 12:24:23,174 - root - INFO - Built-in commands registered.
2024-10-18 12:24:23,174 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:24:23,174 - root - INFO - Application shutdown.
2024-10-18 12:24:23,177 - root - INFO - Built-in commands registered.
2024-10-18 12:24:23,177 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:24:23,177 - root - INFO - Application shutdown.
2024-10-18 12:24:23,207 - root - INFO - Built-in commands registered.
2024-10-18 12:24:23,207 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:24:23,207 - root - INFO - Application interrupted by user.
2024-10-18 12:24:23,207 - root - INFO - Application shutdown.
2024-10-18 12:24:23,210 - root - INFO - Built-in commands registered.
2024-10-18 12:24:23,210 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:24:23,210 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:24:23,210 - root - INFO - Application shutdown.
2024-10-18 12:25:19,009 - root - INFO - Built-in commands registered.
2024-10-18 12:25:19,009 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:25:19,009 - root - INFO - Application shutdown.
2024-10-18 12:25:19,012 - root - INFO - Built-in commands registered.
2024-10-18 12:25:19,013 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:25:19,013 - root - INFO - Application shutdown.
2024-10-18 12:25:19,043 - root - INFO - Built-in commands registered.
2024-10-18 12:25:19,043 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:25:19,043 - root - INFO - Application interrupted by user.
2024-10-18 12:25:19,043 - root - INFO - Application shutdown.
2024-10-18 12:25:19,046 - root - INFO - Built-in commands registered.
2024-10-18 12:25:19,047 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:25:19,047 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:25:19,047 - root - INFO - Application shutdown.
2024-10-18 12:26:29,229 - root - INFO - Built-in commands registered.
2024-10-18 12:26:29,230 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:26:29,230 - root - INFO - Application shutdown.
2024-10-18 12:26:29,233 - root - INFO - Built-in commands registered.
2024-10-18 12:26:29,233 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:26:29,233 - root - INFO - Application shutdown.
2024-10-18 12:26:29,263 - root - INFO - Built-in commands registered.
2024-10-18 12:26:29,263 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:26:29,263 - root - INFO - Application interrupted by user.
2024-10-18 12:26:29,264 - root - INFO - Application shutdown.
2024-10-18 12:26:29,266 - root - INFO - Built-in commands registered.
2024-10-18 12:26:29,266 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:26:29,266 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:26:29,267 - root - INFO - Application shutdown.
2024-10-18 12:27:05,873 - root - INFO - Built-in commands registered.
2024-10-18 12:27:05,873 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:27:05,873 - root - INFO - Application shutdown.
2024-10-18 12:27:05,876 - root - INFO - Built-in commands registered.
2024-10-18 12:27:05,876 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:27:05,877 - root - INFO - Application shutdown.
2024-10-18 12:27:05,907 - root - INFO - Built-in commands registered.
2024-10-18 12:27:05,907 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:27:05,907 - root - INFO - Application interrupted by user.
2024-10-18 12:27:05,907 - root - INFO - Application shutdown.
2024-10-18 12:27:05,910 - root - INFO - Built-in commands registered.
2024-10-18 12:27:05,910 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:27:05,910 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:27:05,910 - root - INFO - Application shutdown.
2024-10-18 12:27:21,553 - root - INFO - Built-in commands registered.
2024-10-18 12:27:21,553 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:27:21,553 - root - INFO - Application shutdown.
2024-10-18 12:27:21,556 - root - INFO - Built-in commands registered.
2024-10-18 12:27:21,556 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:27:21,557 - root - INFO - Application shutdown.
2024-10-18 12:27:21,585 - root - INFO - Built-in commands registered.
2024-10-18 12:27:21,585 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:27:21,585 - root - INFO - Application interrupted by user.
2024-10-18 12:27:21,586 - root - INFO - Application shutdown.
2024-10-18 12:27:21,588 - root - INFO - Built-in commands registered.
2024-10-18 12:27:21,589 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:27:21,589 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:27:21,589 - root - INFO - Application shutdown.
2024-10-18 12:30:42,982 - root - INFO - Built-in commands registered.
2024-10-18 12:30:42,983 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:30:42,983 - root - INFO - Application shutdown.
2024-10-18 12:30:42,986 - root - INFO - Built-in commands registered.
2024-10-18 12:30:42,986 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:30:42,986 - root - INFO - Application shutdown.
2024-10-18 12:30:43,016 - root - INFO - Built-in commands registered.
2024-10-18 12:30:43,016 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:30:43,016 - root - INFO - Application interrupted by user.
2024-10-18 12:30:43,016 - root - INFO - Application shutdown.
2024-10-18 12:30:43,019 - root - INFO - Built-in commands registered.
2024-10-18 12:30:43,019 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:30:43,019 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:30:43,019 - root - INFO - Application shutdown.
2024-10-18 12:30:49,362 - root - INFO - Built-in commands registered.
2024-10-18 12:30:49,362 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:30:49,362 - root - INFO - Application shutdown.
2024-10-18 12:30:49,365 - root - INFO - Built-in commands registered.
2024-10-18 12:30:49,365 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:30:49,366 - root - INFO - Application shutdown.
2024-10-18 12:30:49,396 - root - INFO - Built-in commands registered.
2024-10-18 12:30:49,396 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:30:49,396 - root - INFO - Application interrupted by user.
2024-10-18 12:30:49,396 - root - INFO - Application shutdown.
2024-10-18 12:30:49,399 - root - INFO - Built-in commands registered.
2024-10-18 12:30:49,399 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:30:49,399 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:30:49,399 - root - INFO - Application shutdown.
2024-10-18 12:32:29,395 - root - INFO - Built-in commands registered.
2024-10-18 12:32:29,396 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:32:29,396 - root - INFO - Application shutdown.
2024-10-18 12:32:29,399 - root - INFO - Built-in commands registered.
2024-10-18 12:32:29,399 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:32:29,399 - root - INFO - Application shutdown.
2024-10-18 12:32:29,431 - root - INFO - Built-in commands registered.
2024-10-18 12:32:29,431 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:32:29,431 - root - INFO - Application interrupted by user.
2024-10-18 12:32:29,432 - root - INFO - Application shutdown.
2024-10-18 12:32:29,439 - root - INFO - Built-in commands registered.
2024-10-18 12:32:29,443 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:32:29,443 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:32:29,444 - root - INFO - Application shutdown.
2024-10-18 12:34:31,196 - root - INFO - Built-in commands registered.
2024-10-18 12:34:31,196 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:34:31,196 - root - INFO - Application shutdown.
2024-10-18 12:34:31,199 - root - INFO - Built-in commands registered.
2024-10-18 12:34:31,199 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:34:31,199 - root - INFO - Application shutdown.
2024-10-18 12:34:31,229 - root - INFO - Built-in commands registered.
2024-10-18 12:34:31,230 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:34:31,230 - root - INFO - Application interrupted by user.
2024-10-18 12:34:31,230 - root - INFO - Application shutdown.
2024-10-18 12:34:31,233 - root - INFO - Built-in commands registered.
2024-10-18 12:34:31,233 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:34:31,233 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:34:31,233 - root - INFO - Application shutdown.
2024-10-18 12:37:05,498 - root - INFO - Built-in commands registered.
2024-10-18 12:37:05,498 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:37:05,498 - root - INFO - Application shutdown.
2024-10-18 12:37:05,501 - root - INFO - Built-in commands registered.
2024-10-18 12:37:05,501 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:37:05,501 - root - INFO - Application shutdown.
2024-10-18 12:37:05,532 - root - INFO - Built-in commands registered.
2024-10-18 12:37:05,532 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:37:05,532 - root - INFO - Application interrupted by user.
2024-10-18 12:37:05,532 - root - INFO - Application shutdown.
2024-10-18 12:37:05,534 - root - INFO - Built-in commands registered.
2024-10-18 12:37:05,535 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:37:05,535 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:37:05,535 - root - INFO - Application shutdown.
2024-10-18 12:37:59,010 - root - INFO - Built-in commands registered.
2024-10-18 12:37:59,011 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:37:59,011 - root - INFO - Application shutdown.
2024-10-18 12:37:59,014 - root - INFO - Built-in commands registered.
2024-10-18 12:37:59,014 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:37:59,014 - root - INFO - Application shutdown.
2024-10-18 12:37:59,044 - root - INFO - Built-in commands registered.
2024-10-18 12:37:59,044 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:37:59,044 - root - INFO - Application interrupted by user.
2024-10-18 12:37:59,044 - root - INFO - Application shutdown.
2024-10-18 12:37:59,047 - root - INFO - Built-in commands registered.
2024-10-18 12:37:59,047 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:37:59,047 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:37:59,047 - root - INFO - Application shutdown.
2024-10-18 12:41:53,181 - root - INFO - Built-in commands registered.
2024-10-18 12:41:53,182 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:41:53,182 - root - INFO - Application shutdown.
2024-10-18 12:41:53,185 - root - INFO - Built-in commands registered.
2024-10-18 12:41:53,185 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:41:53,185 - root - INFO - Application shutdown.
2024-10-18 12:41:53,196 - root - INFO - Built-in commands registered.
2024-10-18 12:41:53,196 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:41:53,197 - root - INFO - Application interrupted by user.
2024-10-18 12:41:53,197 - root - INFO - Application shutdown.
2024-10-18 12:41:53,199 - root - INFO - Built-in commands registered.
2024-10-18 12:41:53,200 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:41:53,200 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:41:53,200 - root - INFO - Application shutdown.
2024-10-18 12:42:28,607 - root - INFO - Built-in commands registered.
2024-10-18 12:42:28,608 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:42:28,608 - root - INFO - Application shutdown.
2024-10-18 12:42:28,610 - root - INFO - Built-in commands registered.
2024-10-18 12:42:28,611 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:42:28,611 - root - INFO - Application shutdown.
2024-10-18 12:42:28,641 - root - INFO - Built-in commands registered.
2024-10-18 12:42:28,641 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:42:28,641 - root - INFO - Application interrupted by user.
2024-10-18 12:42:28,641 - root - INFO - Application shutdown.
2024-10-18 12:42:28,644 - root - INFO - Built-in commands registered.
2024-10-18 12:42:28,644 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:42:28,644 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:42:28,644 - root - INFO - Application shutdown.
2024-10-18 12:43:16,167 - root - INFO - Built-in commands registered.
2024-10-18 12:43:16,167 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:16,167 - root - INFO - Application shutdown.
2024-10-18 12:43:16,170 - root - INFO - Built-in commands registered.
2024-10-18 12:43:16,170 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:16,170 - root - INFO - Application shutdown.
2024-10-18 12:43:16,201 - root - INFO - Built-in commands registered.
2024-10-18 12:43:16,201 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:16,201 - root - INFO - Application interrupted by user.
2024-10-18 12:43:16,201 - root - INFO - Application shutdown.
2024-10-18 12:43:16,204 - root - INFO - Built-in commands registered.
2024-10-18 12:43:16,204 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:16,204 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:43:16,204 - root - INFO - Application shutdown.
2024-10-18 12:43:27,941 - root - INFO - Built-in commands registered.
2024-10-18 12:43:27,941 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:27,942 - root - INFO - Application shutdown.
2024-10-18 12:43:27,949 - root - INFO - Built-in commands registered.
2024-10-18 12:43:27,950 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:27,950 - root - INFO - Application shutdown.
2024-10-18 12:43:27,982 - root - INFO - Built-in commands registered.
2024-10-18 12:43:27,982 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:27,982 - root - INFO - Application interrupted by user.
2024-10-18 12:43:27,982 - root - INFO - Application shutdown.
2024-10-18 12:43:27,985 - root - INFO - Built-in commands registered.
2024-10-18 12:43:27,985 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:27,985 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:43:27,985 - root - INFO - Application shutdown.
2024-10-18 12:43:39,184 - root - INFO - Built-in commands registered.
2024-10-18 12:43:39,184 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:39,185 - root - INFO - Application shutdown.
2024-10-18 12:43:39,187 - root - INFO - Built-in commands registered.
2024-10-18 12:43:39,187 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:39,188 - root - INFO - Application shutdown.
2024-10-18 12:43:39,218 - root - INFO - Built-in commands registered.
2024-10-18 12:43:39,218 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:39,218 - root - INFO - Application interrupted by user.
2024-10-18 12:43:39,219 - root - INFO - Application shutdown.
2024-10-18 12:43:39,221 - root - INFO - Built-in commands registered.
2024-10-18 12:43:39,221 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:43:39,221 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:43:39,221 - root - INFO - Application shutdown.
2024-10-18 12:44:11,807 - root - INFO - Built-in commands registered.
2024-10-18 12:44:11,807 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:44:11,808 - root - INFO - Application shutdown.
2024-10-18 12:44:11,810 - root - INFO - Built-in commands registered.
2024-10-18 12:44:11,811 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:44:11,811 - root - INFO - Application shutdown.
2024-10-18 12:44:11,840 - root - INFO - Built-in commands registered.
2024-10-18 12:44:11,840 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:44:11,840 - root - INFO - Application interrupted by user.
2024-10-18 12:44:11,841 - root - INFO - Application shutdown.
2024-10-18 12:44:11,843 - root - INFO - Built-in commands registered.
2024-10-18 12:44:11,844 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:44:11,844 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:44:11,844 - root - INFO - Application shutdown.
2024-10-18 12:45:48,067 - root - INFO - Built-in commands registered.
2024-10-18 12:45:48,068 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:45:48,068 - root - INFO - Application shutdown.
2024-10-18 12:45:48,071 - root - INFO - Built-in commands registered.
2024-10-18 12:45:48,071 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:45:48,071 - root - INFO - Application shutdown.
2024-10-18 12:45:48,082 - root - INFO - Built-in commands registered.
2024-10-18 12:45:48,082 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:45:48,082 - root - INFO - Application interrupted by user.
2024-10-18 12:45:48,082 - root - INFO - Application shutdown.
2024-10-18 12:45:48,085 - root - INFO - Built-in commands registered.
2024-10-18 12:45:48,085 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:45:48,085 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:45:48,085 - root - INFO - Application shutdown.
2024-10-18 12:47:12,790 - root - INFO - Logging configured.
2024-10-18 12:47:12,792 - root - INFO - Environment variables loaded.
2024-10-18 12:47:12,794 - root - INFO - Logging configured.
2024-10-18 12:47:12,794 - root - INFO - Environment variables loaded.
2024-10-18 12:47:12,795 - root - INFO - Command 'greet' from plugin 'greet' registered.
2024-10-18 12:47:12,795 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:47:12,795 - root - INFO - Application exit.
2024-10-18 12:47:12,795 - root - INFO - Application shutdown.
2024-10-18 12:47:12,804 - root - INFO - Logging configured.
2024-10-18 12:47:12,805 - root - INFO - Environment variables loaded.
2024-10-18 12:47:12,805 - root - INFO - Command 'greet' from plugin 'greet' registered.
2024-10-18 12:47:12,805 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:47:12,805 - root - INFO - Application exit.
2024-10-18 12:47:12,805 - root - INFO - Application shutdown.
2024-10-18 12:47:12,811 - root - INFO - Logging configured.
2024-10-18 12:47:12,811 - root - INFO - Environment variables loaded.
2024-10-18 12:47:12,812 - root - WARNING - Plugins directory 'app/plugins' not found.
2024-10-18 12:47:12,815 - root - INFO - Logging configured.
2024-10-18 12:47:12,816 - root - INFO - Environment variables loaded.
2024-10-18 12:47:12,817 - root - INFO - Logging configured.
2024-10-18 12:47:12,818 - root - INFO - Environment variables loaded.
2024-10-18 12:47:12,818 - root - INFO - Command 'greet' from plugin 'greet' registered.
2024-10-18 12:47:12,818 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:47:12,818 - root - INFO - Application interrupted and exiting gracefully.
2024-10-18 12:47:12,818 - root - INFO - Application shutdown.
2024-10-18 12:47:12,826 - root - INFO - Logging configured.
2024-10-18 12:47:12,826 - root - INFO - Environment variables loaded.
2024-10-18 12:47:12,827 - root - INFO - Command 'greet' from plugin 'greet' registered.
2024-10-18 12:47:12,827 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:47:12,827 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:47:12,827 - root - INFO - Application exit.
2024-10-18 12:47:12,827 - root - INFO - Application shutdown.
2024-10-18 12:47:20,273 - root - INFO - Built-in commands registered.
2024-10-18 12:47:20,274 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:47:20,274 - root - INFO - Application shutdown.
2024-10-18 12:47:20,277 - root - INFO - Built-in commands registered.
2024-10-18 12:47:20,277 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:47:20,277 - root - INFO - Application shutdown.
2024-10-18 12:47:20,287 - root - INFO - Built-in commands registered.
2024-10-18 12:47:20,287 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:47:20,287 - root - INFO - Application interrupted by user.
2024-10-18 12:47:20,287 - root - INFO - Application shutdown.
2024-10-18 12:47:20,290 - root - INFO - Built-in commands registered.
2024-10-18 12:47:20,290 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:47:20,290 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:47:20,290 - root - INFO - Application shutdown.
2024-10-18 12:49:09,490 - root - INFO - Built-in commands registered.
2024-10-18 12:49:09,491 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:49:09,491 - root - INFO - Application shutdown.
2024-10-18 12:49:09,494 - root - INFO - Built-in commands registered.
2024-10-18 12:49:09,494 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:49:09,494 - root - INFO - Application shutdown.
2024-10-18 12:49:09,504 - root - INFO - Built-in commands registered.
2024-10-18 12:49:09,504 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:49:09,504 - root - INFO - Application interrupted by user.
2024-10-18 12:49:09,504 - root - INFO - Application shutdown.
2024-10-18 12:49:09,507 - root - INFO - Built-in commands registered.
2024-10-18 12:49:09,507 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:49:09,507 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:49:09,507 - root - INFO - Application shutdown.
2024-10-18 12:50:54,833 - root - INFO - Built-in commands registered.
2024-10-18 12:50:54,833 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:50:54,833 - root - INFO - Application shutdown.
2024-10-18 12:50:54,836 - root - INFO - Built-in commands registered.
2024-10-18 12:50:54,836 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:50:54,836 - root - INFO - Application shutdown.
2024-10-18 12:50:54,847 - root - INFO - Built-in commands registered.
2024-10-18 12:50:54,847 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:50:54,847 - root - INFO - Application interrupted by user.
2024-10-18 12:50:54,847 - root - INFO - Application shutdown.
2024-10-18 12:50:54,850 - root - INFO - Built-in commands registered.
2024-10-18 12:50:54,850 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:50:54,850 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:50:54,850 - root - INFO - Application shutdown.
2024-10-18 12:51:04,348 - root - INFO - Built-in commands registered.
2024-10-18 12:51:04,349 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:51:04,349 - root - INFO - Application shutdown.
2024-10-18 12:51:04,351 - root - INFO - Built-in commands registered.
2024-10-18 12:51:04,352 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:51:04,352 - root - INFO - Application shutdown.
2024-10-18 12:51:04,362 - root - INFO - Built-in commands registered.
2024-10-18 12:51:04,363 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:51:04,363 - root - INFO - Application interrupted by user.
2024-10-18 12:51:04,363 - root - INFO - Application shutdown.
2024-10-18 12:51:04,365 - root - INFO - Built-in commands registered.
2024-10-18 12:51:04,366 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:51:04,366 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:51:04,366 - root - INFO - Application shutdown.
2024-10-18 12:53:32,337 - root - INFO - Built-in commands registered.
2024-10-18 12:53:32,338 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:53:32,338 - root - INFO - Application shutdown.
2024-10-18 12:53:32,341 - root - INFO - Built-in commands registered.
2024-10-18 12:53:32,341 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:53:32,341 - root - INFO - Application shutdown.
2024-10-18 12:53:32,351 - root - INFO - Built-in commands registered.
2024-10-18 12:53:32,352 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:53:32,352 - root - INFO - Application interrupted by user.
2024-10-18 12:53:32,352 - root - INFO - Application shutdown.
2024-10-18 12:53:32,354 - root - INFO - Built-in commands registered.
2024-10-18 12:53:32,355 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:53:32,355 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:53:32,355 - root - INFO - Application shutdown.
2024-10-18 12:54:22,023 - root - INFO - Built-in commands registered.
2024-10-18 12:54:22,023 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:54:22,023 - root - INFO - Application shutdown.
2024-10-18 12:54:22,026 - root - INFO - Built-in commands registered.
2024-10-18 12:54:22,026 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:54:22,026 - root - INFO - Application shutdown.
2024-10-18 12:54:22,030 - root - INFO - Built-in commands registered.
2024-10-18 12:54:22,030 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:54:22,031 - root - INFO - Application interrupted by user.
2024-10-18 12:54:22,031 - root - INFO - Application shutdown.
2024-10-18 12:54:22,033 - root - INFO - Built-in commands registered.
2024-10-18 12:54:22,034 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:54:22,034 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:54:22,034 - root - INFO - Application shutdown.
2024-10-18 12:55:39,654 - root - INFO - Built-in commands registered.
2024-10-18 12:55:39,655 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:55:39,655 - root - INFO - Application shutdown.
2024-10-18 12:55:39,659 - root - INFO - Built-in commands registered.
2024-10-18 12:55:39,659 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:55:39,659 - root - INFO - Application shutdown.
2024-10-18 12:55:39,663 - root - INFO - Built-in commands registered.
2024-10-18 12:55:39,664 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:55:39,664 - root - INFO - Application interrupted by user.
2024-10-18 12:55:39,664 - root - INFO - Application shutdown.
2024-10-18 12:55:39,666 - root - INFO - Built-in commands registered.
2024-10-18 12:55:39,666 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 12:55:39,667 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 12:55:39,667 - root - INFO - Application shutdown.
2024-10-18 13:00:20,963 - root - INFO - Built-in commands registered.
2024-10-18 13:00:20,963 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:00:20,963 - root - INFO - Application shutdown.
2024-10-18 13:00:20,965 - root - INFO - Built-in commands registered.
2024-10-18 13:00:20,965 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:00:20,965 - root - INFO - Application shutdown.
2024-10-18 13:00:20,968 - root - INFO - Built-in commands registered.
2024-10-18 13:00:20,968 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:00:20,968 - root - INFO - Application interrupted by user.
2024-10-18 13:00:20,968 - root - INFO - Application shutdown.
2024-10-18 13:00:20,970 - root - INFO - Built-in commands registered.
2024-10-18 13:00:20,970 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:00:20,970 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 13:00:20,970 - root - INFO - Application shutdown.
2024-10-18 13:00:28,196 - root - INFO - Built-in commands registered.
2024-10-18 13:00:28,196 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:00:28,196 - root - INFO - Application shutdown.
2024-10-18 13:00:28,199 - root - INFO - Built-in commands registered.
2024-10-18 13:00:28,199 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:00:28,199 - root - INFO - Application shutdown.
2024-10-18 13:00:28,203 - root - INFO - Built-in commands registered.
2024-10-18 13:00:28,203 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:00:28,203 - root - INFO - Application interrupted by user.
2024-10-18 13:00:28,203 - root - INFO - Application shutdown.
2024-10-18 13:00:28,206 - root - INFO - Built-in commands registered.
2024-10-18 13:00:28,207 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:00:28,207 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 13:00:28,207 - root - INFO - Application shutdown.
2024-10-18 13:28:10,687 - root - INFO - Built-in commands registered.
2024-10-18 13:28:10,688 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:28:10,688 - root - INFO - Application shutdown.
2024-10-18 13:28:10,689 - root - INFO - Built-in commands registered.
2024-10-18 13:28:10,689 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:28:10,689 - root - INFO - Application shutdown.
2024-10-18 13:28:10,693 - root - INFO - Built-in commands registered.
2024-10-18 13:28:10,693 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:28:10,693 - root - INFO - Application interrupted by user.
2024-10-18 13:28:10,693 - root - INFO - Application shutdown.
2024-10-18 13:28:10,695 - root - INFO - Built-in commands registered.
2024-10-18 13:28:10,695 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:28:10,695 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 13:28:10,695 - root - INFO - Application shutdown.
2024-10-18 13:36:07,113 - root - INFO - Built-in commands registered.
2024-10-18 13:36:07,113 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:36:07,113 - root - INFO - GreetCommand executed: Hello, World!
2024-10-18 13:36:07,114 - root - INFO - Application shutdown.
2024-10-18 13:36:20,172 - root - INFO - Built-in commands registered.
2024-10-18 13:36:20,173 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:36:20,173 - root - INFO - Application shutdown.
2024-10-18 13:36:20,175 - root - INFO - Built-in commands registered.
2024-10-18 13:36:20,175 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:36:20,175 - root - INFO - Application shutdown.
2024-10-18 13:36:20,177 - root - INFO - Built-in commands registered.
2024-10-18 13:36:20,178 - root - INFO - Application started. Type 'exit' to exit.
2024-10-18 13:36:20,178 - root - INFO - Application interrupted by user.
2024-10-18 13:36:20,178 - root - INFO - Application shutdown.
2024-10-18 13:48:41,810 - root - INFO - Built-in commands registered.
2024-10-18 13:48:41,815 - root - INFO - Application started. Type 'exit' to exit.

