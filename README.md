# Inverted
Inverted is a minimal dark theme for Hugo.

## Getting started
1. Create a new site from default template:  
`hugo new site yourAwesomeSite`
2. Change the directory:  
`cd yourAwesomeSite`
3. Create a new empty git repository:  
`git init`
4. Install the theme:  
`git submodule add https://github.com/trubitsyn/inverted themes/inverted`

## Site configuration
Example `config.toml`:

```
baseURL = "https://example.org/"
languageCode = "en-us"
title = "My New Hugo Site"
theme = "inverted"
```

## Build
1. Start the server on localhost:1313 
with `hugo server`
2. Ensure everything is working well  
3. Build the site with `hugo build`

## License
Apache License, Version 2.0
