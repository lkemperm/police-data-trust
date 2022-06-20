FROM python:3.9 
WORKDIR /app
ADD backend/scraper/ .
RUN pip install -r requirements.txt
CMD ["python", "scrape_data_sources.py"]