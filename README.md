# Database Server
This is a simple Sinatra server with 3 basic routes to access the server, save a simple key-value pair and retrieve it.

## Installation via command line
- `git clone git@github.com:MaxProvin/database_server.git`
- `bundle`

## Tests
- `rspec` to run tests

## Gem Dependencies
- rspec
- rspec-sinatra
- capybara
- sinatra
- json

## Usage
- `ruby app.rb`
- requests are made via the url bar in your browser
- server is accessible at `http://localhost:4000/`
- set key value pair like so `http://localhost:4000/set?<yourkey>=<yourvalue>`
- retrieve value like so `http://localhost:4000/get?key=<yourkey>`
