# SF Lindy Society Website

The source for the official website of the SF Lindy Society.

# Local dev
## Setup

Install `ruby` and `bundle` e.g.
> sudo apt install ruby ruby-bundle

Set a local directory for installing gems to not interfere with your system wide gems (optinal):
> bundle config set --local path vendor
The "vendor" directory is ignored in .gitignore

Run `bundle install`

If you get errors building "gem native extensions" you may need e.g.:
> sudo apt install ruby-dev

If you get errors with the openssl gem on linux you may need e.g.:
> sudo apt install libssl-dev

## Running the website locally

run ```bundle exec jekyll serve``` 
