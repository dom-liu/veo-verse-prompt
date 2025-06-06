# Contributing to veo-verse-prompt

First off, thank you for considering contributing to veo-verse-prompt! Your help is appreciated.

This document provides guidelines for contributing to the project. Please make sure your contributions are in English.

## How to Contribute

There are several ways you can contribute to this project:

*   **Submitting new video prompts**: Share your creative Veo prompts.
*   **Suggesting improvements**: Help us enhance the project structure, documentation, or prompt quality.

### Submitting New Video Prompts

To add a new video prompt, please follow these steps:

1.  **Create a JSONC file**: Create a new file with the `.jsonc` extension (e.g., `my-awesome-prompt.jsonc`).
2.  **File Location**: Place your new file in the directory corresponding to the Veo version the prompt is for. For example, prompts for Veo version 1 should go into the `veo/` directory.
3.  **Content Format**: The JSONC file should contain the following fields:
    ```jsonc
    {
      "title": "Your Video Title",
      "description": "A brief description of the video or prompt.",
      "prompt": "The exact prompt text used to generate the video.",
      "version": "Veo version (e.g., '1', '2', '3')",
      "uploadDate": "YYYY-MM-DD",
      "author": "Your Name or Pseudonym",
      "videoUrl": "A URL to the video if available (e.g., YouTube, Vimeo)"
      // You can also add comments within the JSONC file using //
    }
    ```
4.  **Pull Request**: Once your file is ready, open a pull request with your changes.

### Suggesting Improvements

If you have ideas on how to improve the project, whether it's the directory structure, the documentation, the prompt format, or anything else, please feel free to:

*   **Open an Issue**: Describe your suggestion in detail.
*   **Submit a Pull Request**: If you've already implemented the improvement, you can submit a pull request with your changes.

## Code of Conduct

While this project does not have a formal Code of Conduct yet, please be respectful and constructive in all your interactions.

Thank you for contributing!
