# bandNameGenerator_expressJs_eJs

# Express Server with EJS Template Rendering

This project sets up an Express server with EJS template rendering. It includes routes for rendering an index page and processing a form submission. Random adjectives and nouns are dynamically inserted into the index page upon form submission.

## Prerequisites

Ensure you have Node.js and npm installed on your machine.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/yourproject.git

   ```

2. Navigate to the project directory:

`cd yourproject`

3 Install dependencies:

`npm install`

## Usage

To start the server, run the following command:

`node index.js`
The server will start listening on port 3000 by default.

## Routes

`GET /: Renders the index.ejs template.`

`POST /submit: Processes a form submission and renders the index.ejs template with random adjectives and nouns`

## Dependencies

Express: Fast, unopinionated, minimalist web framework for Node.js.
body-parser: Node.js body parsing middleware.

## Files

`index.js`: Main entry point of the application, containing server setup and route definitions.

`public/:` Directory containing static assets such as HTML, CSS, and client-side JavaScript files.

`views/index.ejs:` EJS template file for the index page.
Configuration

`Static File Serving:` Static files such as HTML, CSS, and client-side JavaScript are served from the public directory using express.static middleware.

`Form Submission Handling:` The server utilizes body-parser middleware to parse form submissions sent with POST requests.
Rendering: EJS templates are rendered using res.render() method to dynamically generate HTML content.
