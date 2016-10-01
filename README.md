# email-tempaltes

This repository contains email templates for SOFTSKY Site Security project.

## Folder structure
Every email template consist of 3 files
- html.jade (contains HTML formatted email message)
- text.jade (contains PLAIN TEXT formatted email message)
- subject.jade (contains PLAIN TEXT formatted email subject)

Currently we support Jade engine to format our files.


## Editing
To edit the document, navigate to appropriate subfolder, click on document and hit [pen button] at the top right.

## Constraints

Marketing team, please use `marketing` branch to work with your files
Translator team, please use `translator` branch to work with your files

#### Formatting 
`Marketing` and `Translator` teams mostly use simple `#{variable_name}` substitution.
`Designer` team would utilize full power of Jade formatting.

#### Variables
- `#{url}` - website *url* to scan
- `#{name.first}` - customer First Name
- `#{name.last}` - customer Last Name
- `#{email}` - customer Email
