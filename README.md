# markdown2confluence
Push markdown files to Confluence Cloud

## Installation

    sudo curl -L https://github.com/justmiles/go-markdown2confluence/releases/download/v1.0.0/markdown2confluence.linux-amd64 -o /usr/local/bin/markdown2confluence
    sudo chmod +x /usr/local/bin/markdown2confluence

## Usage

  - CONFLUENCE_USERNAME - username for Confluence Cloud
  - CONFLUENCE_PASSWORD - password for Confluence Cloud
  - CONFLUENCE_ENDPOINT - endpoint for Confluence Cloud, eg `https://mycompanyname.atlassian.net/wiki`

Usage of markdown2confluence:

    -debug
        enable debug logging
    -file string
        markdown file to sync with Confluence
    -space string
        space in which page should be created. Defaults to user's personal space
    -title string
        title for page. Defaults to file name without .md extension