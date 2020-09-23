# Normal Installation

- Install python3.7
- Install the dependencies listed in requirements.text
- The working directory is the root folder
- run the command: python3 app.py

# Endpoints

- /get_videos : This gets the videos in the reverse chronological order publishedAfter - "2002-05-01T00:00:00Z" and for the keyword: "cricket". The API page size is 10 (API_PAGE_SIZE). The parameter(s) used: "page" (/get_videos?page=2)
- /search_videos : A basic search API to search the stored videos using their title and description. Parameters used: query and page (/search_videos?query=RCB&page=2)

We store 50 results from youtube at a point of time.

# Docker Installation

- docker build .
- docker run imagename
