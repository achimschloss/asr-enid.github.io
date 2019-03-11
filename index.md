# Developer Documentation
## Claims und Scopes

Each initiation of an SSO process with netID is provided with information about what data is expected from the end-user based on the call. /
The OpenID Connect/OAuth2 mechanisms of the scope and claim definitions serve this purpose.
Every OpenID Connect call must always request the openid scope. In addition, the required master data must be formulated as essential claims.
Once master data has been released by the end user for a service, it no longer has to be released until revoked, and the release is saved.

###netID supports the following claims

- gender | gender of the end user
- given_name | first name(s) of the end user
- family_name | Last name(s) of the end user
- birthdate | Date of birth of the end user
- email | email address of the end user
- email_verified | verification status of the email address of the end user
- postal_code | the postal code of the end user's address.
- locality | city of the address of the end user
- street_address | street and house number of the end user's address
- country | country of the end user's address
- phone_number | phone number of the end user
- phone_number_verified | verification status of the end user's phone number

The availability may vary depending on the account provider of the end user, so that cases where not all requested claims are delivered must be handled by the client.

Claims and scopes that are not requested as essential are ignored.



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/asr-enid/asr-enid.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/asr-enid/asr-enid.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
