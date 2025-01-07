# Flask Todo Application

A simple Todo application built with Flask.

## Prerequisites

* Python 3.x
* Git

## Installation and Setup

### 1. Clone the Repository

```bash
git clone git@github.com:thinkphp/my_todo_flask.git
cd my_todo_flask
```

### 2. Set Up Virtual Environment

Create and activate a virtual environment:

```bash
# Create virtual environment
python3 -m venv myvenv

# Activate virtual environment
# On Unix or MacOS:
source myvenv/bin/activate

# On Windows:
myvenv\Scripts\activate
```

### 3. Install Dependencies

Install the required packages:

```bash
# If requirements.txt exists:
pip install -r requirements.txt

# Or install Flask directly:
pip install flask
```

### 4. Run the Application

Start the Flask development server:

```bash
flask run
```

The application will be available at `http://localhost:5000`

## Development

To enable debug mode during development:

```bash
export FLASK_ENV=development  # Unix/MacOS
set FLASK_ENV=development    # Windows
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details
