# Codewars Leaderboard Ranks Tracker

This Python script automates the process of retrieving and storing your Codewars rankings, providing a convenient way to display your achievements and track your progress for portfolios, resumes, or personal websites.

## Key Features

*   **Dynamic Data Retrieval:** Fetches leaderboard data from Codewars using requests library, ensuring your ranks are up-to-date.
*   **Flexible Configuration:**
    *   Specify your Codewars username.
    *   Define categories to track (or track all categories).
    *   Choose to hide empty ranks in the output.
*   **JSON Storage:** Saves your ranks in a structured JSON file (`ranks.json`) for easy access and future use.

## Why Use This Script?

This script offers a practical solution for Codewars users who want to:

*   Effortlessly track their Codewars ranking progress across various categories.
*   Gain experience with essential Python libraries like `requests`, `json`, and web scraping techniques.
*   Develop a reusable script for leaderboard data retrieval and storage.

## Getting Started

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/BreadyBred/codewars_rank_fetcher
    ```

2.  **Configure the Script (Optional):**

    *   The script uses a separate `data/categories.json` file to define all the categories from the Codewars library.

3.  **Run the Script:**

    1.  Open your terminal, command prompt or preferred IDE.
    2.  Navigate to the directory where you saved the `rank_fetcher.py` file.
    3.  Execute the script using the Python command-line interpreter:

        ```bash
        python rank_fetcher.py
        py rank_fetcher.py
        ```

This will fetch your latest ranks for the specified categories and store them in the `ranks.json` file.

## Further Enhancements

*   **Command-line arguments:** We consider adding command-line arguments for configuration options like specifying a custom categories file.
*   **Codewars API:** The addition of modules to gather information from the official Codewars API for potentially more reliable and efficient data retrieval. This might require additional code to interact with the API.