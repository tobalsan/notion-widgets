# Notion Widgets Repository

This repository contains simple HTML, CSS, and JavaScript files to create custom widgets that can be embedded in Notion.

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/notion-widgets.git
   ```

2. Navigate to the project directory:
   ```bash
   cd notion-widgets
   ```

3. Create a new HTML page for each new widget you want to create.

4. Preview your changes locally:
   - **Option 1**: Use Python's built-in HTTP server:
     ```bash
     python -m http.server
     ```
     Open `http://localhost:8000` in your browser.
   - **Option 2**: Use Visual Studio Code with the Live Server extension. Right-click on `index.html` and select "Open with Live Server."

5. Once satisfied, push changes to GitHub:
   ```bash
   git add .
   git commit -m "Update widget"
   git push
   ```

## Embedding in Notion
- Use GitHub Pages to host your widgets:
  1. Go to your repository settings on GitHub.
  2. Under the **Pages** section, set the source to the `main` branch.
  3. Copy the provided GitHub Pages URL.
- Embed the widget in Notion using an `iframe` block or a third-party embed service.

## License
This project is open source and available under the MIT License. Feel free to use and modify it as needed.

