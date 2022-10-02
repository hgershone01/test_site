# Test Site

## Serving the webpage locally

To view the website before publishing, and also see our changes, we can set up a "development server"
that renders the page as we make changes.

- open the Terminal
- use `cd` to change directories to the repository
  - eg. `cd git/test_site`
- start the development server
  - `bundle exec jekyll serve`
  - Optionally, you can add additional arguments to change the way the server works, to see those
    type `bundle exec jekyll serve --help`
  - For example, to get the page to automatically reload once you make changes, you can use
    `bundle exec jekyll serve --livereload`
- Open the site directory in your text editor! Either by 
  - opening Sublime Text and using the `File > Open` menu, or
  - typing `subl .` from the site directory in the Terminal
- Now when you edit files in the site, you should see that reflected on the page served by the development server!
  - Usually served at [http://127.0.0.1:4000/test_site/](http://127.0.0.1:4000/test_site/)
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
