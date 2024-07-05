# NewsApp: News Summarizer 

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-360/)

## Source
- For summarizing the news, I have used [Newspaper3k](https://newspaper.readthedocs.io/en/latest/)
- For scraping the news, I have used Google News RSS API.

## Features
- Trending News
- Favorite Topics
- Search News
- Quantity Control

## Usage
1. Clone my repository:
    ```sh
    git clone https://github.com/Kuntal271/NewsApp ~/NewsApp && cd NewsApp
    ```

2. Open CMD in the working directory and install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. `App.py` is the main Python file of the Streamlit web application. To run the app, write the following command in CMD or use any IDE:
    ```sh
    streamlit run App.py --server.port 80
    ```

## For Linux (using sudo):
1. Switch to superuser:
    ```sh
    sudo su
    ```

2. Install Git, Python3, and Pip:
    ```sh
    yum install git
    yum install python3
    yum install python3-pip
    ```

3. Clone the repository and navigate to the directory:
    ```sh
    git clone https://github.com/Kuntal271/NewsApp ~/NewsApp && cd NewsApp
    ```

4. Install the dependencies:
    ```sh
    pip3 install -r requirements.txt
    ```

5. Run the app:
    ```sh
    streamlit run App.py --server.port 80
    ```

## Additional Information
For more details on using AWS EC2, refer to the [AWS EC2 User Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html).
