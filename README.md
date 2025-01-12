# GitHub Repo Code Commenting Tool

This tool scans a public GitHub repository, analyzes the code files, and suggests comments/docstrings using OpenAI's GPT-4. It provides a Gradio-based user interface where you can enter a GitHub repository link and view the suggested comments.

---

## Features

- Validates if the GitHub repository is public.
- Analyzes code files (e.g., `.py`, `.js`, `.java`).
- Suggests comments and docstrings using GPT-4.
- Easy-to-use Gradio interface for input and output.

---
## Supported File Types

- Python (.py)
- JavaScript (.js)
- Java (.java)
  
---

## Limitations

- Only supports public GitHub repositories.
- Processes specific file types (.py, .js, .java).
- API calls to GPT-4 may incur costs based on usage.
- Limited handling of very large repositories or files.

---

## Future Improvements

- Add support for private repositories using GitHub tokens.
- Extend compatibility to more file types (e.g., .cpp, .rb).
- Implement pagination for large outputs.
- Deploy the tool on a cloud platform for easy access (e.g., Hugging Face Spaces).

---

## License

This project is licensed under the MIT License.
