# Resources for self-education

As a self-taught developer, I often ask people: "How can I learn *this thing*?
Where should I go? What should I read?"    
An experienced colleague can quickly come up with a few good advice: a person
who's read dozens of books and tutorials can easily tell you, which of them are
worth your time.

In order to save you hours of googling, here we collect links to some amazing
resources.

## Contribute

Feel free to update the list with any project that, in your opinion, will help
other people become harder, better, faster, stronger.

Want to add a link to main page?    
File that you need to edit is `index.md`.    

Want to supplement a topic page?    
Look for `index.md` in appropriate directory.    
For example, Python's page is `python/index.md`.

Once you find a target file, simply add a link to a suitable group.    
Short and helpful descriptions are very welcome:
```
- [Link name](http://path-to-link.com) — Description
```

If you feel that some links should be moved to a new group (or page), don't
hesitate to do so.

To add a page, just create a new folder in root directory and add `index.md` in
it.    
You can copy one of existing pages as an example and then edit it.

It will be amazing if you wrap strings longer then 80 characters and add
following header to all new pages:
```
---
layout: default
---
<!-- vim: set textwidth=80 colorcolumn=80: -->
```

## Preview changes

You can preview your changes before pushing to remote branch.    
All you need is [Jekyll](http://jekyllrb.com/):
```
$ gem install jekyll
```

Once you have Jekyll installed, start server in the project's directory:
```
$ jekyll serve --config _config.dev.yml -w
```

Now you can open `http://localhost:4000` in your browser and enjoy.

## Be awesome

Have any questions? [Give me a sign!](mailto:tonyganch+educate@gmail.com)

![Free pandas for everyone!](http://i.imgur.com/9dT7z.gif)
