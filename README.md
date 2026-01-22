# Wiki

A Django-based encyclopedia application where users can view, search, create, and edit markdown entries.

## Features

- View encyclopedia entries
- Search entries by title
- Create new entries
- Edit existing entries
- Browse all available entries

## Installation

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run migrations:
   ```bash
   python manage.py migrate
   ```

3. Start the development server:
   ```bash
   python manage.py runserver
   ```

The application will be available at `http://127.0.0.1:8000/`

## Project Structure

- `encyclopedia/` - Main Django app
- `entries/` - Markdown encyclopedia entries
- `wiki/` - Django project configuration

## Usage

Navigate to the home page to browse or search entries. Use the interface to create or edit entries as needed.
