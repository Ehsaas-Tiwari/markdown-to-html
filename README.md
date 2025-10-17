# Markdown Viewer

This project provides a simple, static web page to display Markdown content from an `input.md` file, converting it to HTML and applying syntax highlighting to code blocks. It's built with modern web technologies for a clean and responsive user experience.

## Features

*   **Markdown to HTML Conversion**: Automatically converts `input.md` into beautifully rendered HTML.
*   **Syntax Highlighting**: Code blocks within your Markdown are automatically highlighted using Highlight.js.
*   **Responsive Design**: Built with Tailwind CSS, ensuring a great viewing experience on any device size.
*   **Single File Deployment**: The entire application logic and UI are contained within a single `index.html` file, making deployment extremely simple.

## Technologies Used

*   **HTML5**: The structure of the web page.
*   **Tailwind CSS**: For utility-first styling and responsive design.
*   **Marked.js**: A fast and lightweight Markdown parser and compiler.
*   **Highlight.js**: For beautiful and accurate syntax highlighting of code blocks.

## Setup and Usage

To run this application, you only need a web server capable of serving static files.

1.  **Save the files**: Place `index.html`, `README.md`, and `LICENSE` in your project root directory.
2.  **Provide Markdown content**: Create a file named `input.md` in the same directory as `index.html`. This file will contain the Markdown content you wish to display.
3.  **Serve the directory**: Open `index.html` in your web browser, or serve the directory using a simple HTTP server (e.g., `python -m http.server` from the project root).

    Example `input.md` structure:

    ```markdown
    # Welcome to Markdown Viewer

    This is an example of **Markdown** content being rendered.

    ## Code Example

    ```javascript
    function greet(name) {
      console.log(`Hello, ${name}!`);
    }
    greet('World');
    ```

    - List item 1
    - List item 2

    Visit [GitHub](https://github.com) for more.
    ```

## Contributing

Feel free to fork the repository, open issues, or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
