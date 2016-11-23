# Materials Service
## Setup

1. Clone the repo
2. Run `source venv/bin/activate`
3. Run `pip install -r requirements.txt`

## Running
### Development

Run `python run.py`

### Production

Run `gunicorn run:app -w 5 -b 127.0.0.1:5000`

Creates a web server with 5 worker processes.
