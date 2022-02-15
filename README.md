# remove_pdf_password

Command-line (CLI) utlity to remove a PDF's password

## Installation & usage

Install ruby

```
brew install ruby
```

Install Ghostscript

```
brew install gs
```

Clone the repo and cd into it

```
git clone git@github.com:nisanth074/remove_pdf_password.git
cd remove_pdf_password/
```

Install gems

```
gem install bundler
bundle install
```

Remove your PDF's password

```
bundle exec remove_pdf_password /Users/nisanth/Downloads/Aadhaar\ Card.pdf
```

The `remove_pdf_password` utility will create a file named `Aadhaar Card Unlocked.pdf` in the same directory

## Todos

- Create a website so its easy for folks to utilize this utility
