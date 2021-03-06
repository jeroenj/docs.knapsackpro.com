# docs.knapsackpro.com

Documentation for KnapsackPro.com

http://docs.knapsackpro.com

# How can I report a bug or improvement

If you found a bug in our API or you have just an idea how to improve it then please create issue here:

https://github.com/KnapsackPro/docs.knapsackpro.com/issues

# Development

    $ bundle install
    $ bundle exec jekyll serve --watch

## Dependencies

* https://nodejs.org

Run to install dependencies:

    $ npm install

We are using Raml, you can learn more here:

* http://raml.org/
* https://github.com/kevinrenskers/raml2html

## Generate API docs

Raml files with docs are in `_api` directory.

Run to compile them:

    $ bundle exec rake api:generate_docs

Compiled files are in `api` directory. Please commit them into repository.

## Guard

You can run guard to recompile raml files whenever they change.

    $ guard
