## Documentation
The CharleyApp API is the primary way for apps to read and write to the CharleyApp Backend Service. We cover the basics of CharleyApp API terminology and structure in the CharleyApp API overview. This document goes into more detail about the various operations you can perform with the CharleyApp API.

## HTTP/1.1
All data transfers conform to HTTP/1.1, and all endpoints require HTTP/HTTPS. We have also enabled the includeSubdomains HSTS directive on charleyapp.com, but this should not adversely affect your CharleyAPP API calls.

## Host URL
Almost all requests are passed to the **troubleshooting.charleyapp.com/api** host URL.

## Access Tokens
Access tokens allow your app to access the CharleyApp API. They typically perform two functions:

1. they allow your app to access a User's information without requiring the User's password, and
2. they allow us to identify your app, the User who is using your app, and the type of data the User has permitted your app to access.
All CharleyApp API endpoints require an access token of some kind, so each time you access an endpoint, your request must include one.
The app and User IDs are both encoded in the token itself (among other things), and we use those IDs to keep track of which data the User has permitted the app to access.

## Login
You can use the /authentication to fetch all users data specified in the API request





You can use the [editor on GitHub](https://github.com/interwap/charleyapp/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/interwap/charleyapp/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
