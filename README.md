# Build your Backend using FastAPI

## Pre-requisites
* Python (3.6+)

## Running the Code

1. Clone the project
   * `git clone git@github.com:bhanwar88/MLOps_Project.git`
   * `cd fastapi-backend`
2. Create virtual environment
   * `virtualenv venv`
   * `source venv/bin/activate`
3. Install dependencies 
   * `pip3 install -r requirements.txt`
4. Run the server
   * `python3 src/main.py`
5. Server should be running at `http://127.0.0.1:8000/docs`

## Testing the End points

### Running Unit Tests
1. `pytest`

### Running the performance Tests using Locust

1. `locust -f tests/performance-tests/locust_test.py 
`
2. Tests should appear at `http://127.0.0.1:8089/`
