# Simple Java Docker Example

A straightforward repository to help you revise and understand basic Docker concepts with a simple Java application.

## Prerequisites

Before you begin, ensure you have Docker installed on your system. You can download and install it from the [official Docker website](https://www.docker.com/get-started).

## Getting Started

Follow these steps to get the Java application running in a Docker container:

1.  **Clone this repository:**

    Open your terminal or command prompt and run the following command to clone the repository to your local machine:

    ```bash
    git clone https://github.com/nijal2003/Docker-Java-Sample.git
    ```

2.  **Navigate to the directory:**

    Change your current directory to the cloned repository:

    ```bash
    cd Docker-Java-Sample
    ```
    
3.  **Build the Docker image:**

    Use the following command to build the Docker image. This command looks for the `Dockerfile` in the current directory and creates an image tagged as `java-app`.

    ```bash
    docker build -t java-app .
    ```

4.  **Run the Docker container:**

    Once the image is successfully built, you can run it as a container using this command:

    ```bash
    docker run java-app
    ```

And there you have it! Your simple Java application should now be running inside a Docker container.

---

Happy Dockering!
