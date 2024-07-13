# DCC ShutterSeek

DCC ShutterSeek is a Django web application that allows users to search for images using the Unsplash API. The application displays the images along with the number of likes and the author's name.

## Live Demo

I have hosted it on Google Cloud Platform VM. Simply go to [http://34.171.243.208](http://34.171.243.208) and use the website.

## Features

- Search for images from Unsplash
- Display images with likes and author's name
- Auto-submit search after user stops typing
- Supports submitting search on pressing Enter

## Getting Started

Follow these instructions to set up the project on your local machine.

### Prerequisites

- Python 3.x
- Django 3.x or later
- An Unsplash API access key. You can obtain one by creating a developer account on [Unsplash](https://unsplash.com/developers).

### Installation

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/your-username/DCC-ShutterSeek.git
    ```

2. Navigate to the project directory:
    ```sh
    cd DCC-ShutterSeek
    ```

3. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

5. Set up the Django project:
    ```sh
    python manage.py migrate
    ```

6. Create a `.env` file in the project root and add your Unsplash API access key:
    ```env
    UNSPLASH_ACCESS_KEY=your_unsplash_access_key
    ```

7. Run the development server:
    ```sh
    python manage.py runserver
    ```

8. Open your web browser and navigate to `http://127.0.0.1:8000/`.
