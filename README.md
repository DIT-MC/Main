# Main DIT-MC Application

## Architecture

* Python webapp which lets you vote between two options
* Redis queue which collects new votes
* Java worker which consumes votes and stores them in…
* Postgres database backed by a Docker volume
* Node.js webapp which shows the results of the voting in real time
