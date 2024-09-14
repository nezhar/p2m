# p2m: Clipboard to Markdown

This project provides a simple web application that captures HTML content from the clipboard,
converts it to Markdown using the [Turndown](https://github.com/mixmark-io/turndown) library, and displays the Markdown output.

## Usage

1. **Build the Docker Image**:
   ```sh
   docker build -t p2m .
   ```

2. **Run the Docker Container**:
   ```sh
    docker run -d -p 8080:8080 p2m
    ```

3. **Access the Web Application**:
    Open a web browser and navigate to `http://localhost:8080`.
