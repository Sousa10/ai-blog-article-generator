# Django YouTube Blog Generator

This Django application uses the OpenAI API to generate blog posts from YouTube videos. It extracts the video transcript, processes it, and generates a coherent blog post.

## Features

•  Extracts transcripts from YouTube videos.

•  Uses OpenAI API to generate blog posts from transcripts.

•  Simple and intuitive web interface.

•  Stores generated blog posts in a database.


## Requirements

•  Python 3.8+

•  Django 3.2+

•  OpenAI API key

•  YouTube Data API key


## Installation

1. [**Clone the repository:**]

```bash
git clone https://github.com/Sousa10/ai-blog-article-generator.git
cd django-youtube-blog-generator
```
1. 
Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

2. 
Install the dependencies:
```bash
pip install -r requirements.txt
```
3. 
Set up environment variables:

Create a .env file in the project root and add your API keys:

OPENAI_API_KEY=your_openai_api_key
YOUTUBE_API_KEY=your_youtube_api_key

4. 
Run database migrations:
```bash
python manage.py migrate
```
5. 
Start the development server:
```bash
python manage.py runserver
```
## Usage
1. 
Access the web interface:

Open your web browser and go to http://127.0.0.1:8000.

2. 
Generate a blog post:

•  Enter the URL of the YouTube video.

•  Click on "Generate Blog Post".

•  The app will extract the transcript, process it using the OpenAI API, and display the generated blog post.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
•  Django

•  OpenAI

•  YouTube Data API
