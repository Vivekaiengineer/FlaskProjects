Flask Assignment Question -01

1. Create a Flask app that displays "Hello, World!" on the homepage.

Required Code using Visula Studio Environment


from flask import Flask

# Create a Flask app instance
app = Flask(__name__)

# Define a route for the homepage
@app.route('/')
def home():
    return "Hello, World!"

# Run the app
if __name__ == '__main__':
    app.run(debug=True)  # Enable debug mode for easier troubleshooting
