# DBSnapper CLI - (snapper)

`snapper` is the command line DBSnapper client simplifies the process of creating sanitized database snapshots for development. With this client you can create and manage snapshots for your targets as well as generate sanitizations scripts for your data. 

## Features

- Create source and destination target definitions and store them in the cloud
- Asynchronous builds of database snapshots stored in S3
- Pull snapshots and cache them locally to speed up the sanitization script testing cycle
- One-click and automated options for the snapshot -> sanitize -> load cycle  

## Requirements

- Postgres database
- Docker 
- Tested on Mac, Linux and Windows builds also available

## Installation

DBSnapper is currently under heavy development and supports postgres databases (mysql soon to follow)

Install with homebrew

`brew install joescharf/tap/snapper`

## Running

From a command line prompt, execute:

`snapper`

To display a list of commands and help.
