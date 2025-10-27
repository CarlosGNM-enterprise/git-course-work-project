>**Note**: Please **fork** this Udacity repository so you have a **remote** repository in **your** GitHub account. Then you can clone the remote repository to your local machine. Later, as a part of the project, you will push your changes to the remote repository in your GitHub account.


# US Bikeshare Data Exploration

This project analyzes bikeshare data for three major U.S. cities — Chicago, New York City and Washington — using Python.

The program allows users to filter data by city, month, and day of the week, and then calculates useful statistics such as the most popular travel times, stations, trip durations, and user demographics.

## How to use the project

### Installation and Setup
1. Clone your forked repository 
    ```bash
    git clone https://github.com/<your-username>/git-course-work-project
    ```
2. Navigate into the project directory
    ```bash
    cd git-course-work-project
    ```
3. Install the required libraries
    ```bash
    pip install pandas numpy
    ```

### Dataset Description

Each city dataset contains information about individual bike trips, including the following columns:

| Column | Description |
|---------|-------------|
| **Start Time** | Start date and time of the trip |
| **End Time** | End date and time of the trip |
| **Trip Duration** | Duration of the trip in seconds |
| **Start Station** | Station name where the trip started |
| **End Station** | Station name where the trip ended |
| **User Type** | Customer type (Subscriber or Customer) |
| **Gender** | Gender of the user (if available) |
| **Birth Year** | Year of birth of the user (if available) |


### Running the Program
Run the script in your terminal
```bash
python bikeshare.py
```

### Troubleshooting
- Ensure that all `.csv` files are in the same directory as `bikeshare.py`.
- If you select “washington,” note that Gender and Birth Year data are not available.
- Input values (city, month, day) are case-insensitive (e.g., "Chicago" or "chicago" are both accepted).

## Contribution guidelines

Contributions are welcome!
To contribute:

1. Fork the repository
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```

3. Follow Udacity’s Commit Message Style Guide.

    Example:
    ```text
    feat: Add month filter functionality
    ```

4. Push your changes and open a Pull Request.

## Credits

- Dataset Source: Udacity Bikeshare Data
- Libraries Used: pandas, numpy, time
- Inspired by: Udacity’s Programming for Data Science with Python Nanodegree

## Date created

October 27, 2025