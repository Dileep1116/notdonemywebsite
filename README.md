# Not Done My Website

## Rewrite Goals

- [x] Move frontend to entirely HTML5 w/o framework or PHP
- [ ] Create more templates
- [ ] Work out system for easier template additions

## What is this?

Not Done My Website is a little utility for generating index page placeholders based on required criteria, whether it's because you're working on your website or just need a placeholder page!

## Running

Clone the repository to your webserver.

```
git clone git@github.com:gmemstr/notdonemywebsite.git
```

Then go to localhost/notdonemywebsite (or however you have your server set up) and generate away.

## Adding Templates

Custom templates belong in the `templates/` folder and should be entirely self contained, and preferably minimized as well. Feel free to make a pull request so we can add your template to the repository! These should be .html files.

### Keywords for template

| Keyword | Replaced by |
|---|---|
| rep_SURL | URL of the website |
| rep_SNAME | Name of the website |
| rep_DEVNAME | Name of the developer/designer |