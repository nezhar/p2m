# p2m: Clipboard to Markdown

This project provides a simple web application that captures HTML content from the clipboard,
converts it to Markdown using the [Turndown](https://github.com/mixmark-io/turndown) library, and displays the Markdown output.

## Usage

You can access the web application at [https://nezhar.github.io/p2m/](https://nezhar.github.io/p2m/).

Alternatively, you can run the application locally using a http server. For example, you can use the Python http server:

```sh
python3 -m http.server 8080
```

Then, open a web browser and navigate to `http://localhost:8080`.

### Usage with docker

1. **Build the Docker Image**:
   ```sh
   docker build -t p2m .
   ```

2. **Run the Docker Container**:
   ```sh
    docker run -p 8080:80 p2m
    ```

3. **Access the Web Application**:
    Open a web browser and navigate to `http://localhost:8080`.
