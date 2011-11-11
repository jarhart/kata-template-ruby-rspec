# Ruby/RSpec Kata Template

Project template for starting TDD Kata using Ruby and RSpec

## Usage

Clone the repository.

    $ git clone git://github.com/jarhart/kata-template-ruby-rspec.git my_awesome_kata

Create a "kata" gemset and `cd` into your kata directory.

    $ rvm gemset create kata
    $ cd my_awesome_kata

Install bundler if necessary

    $ gem install bundler --no-ri --no-rdoc

Edit `Gemfile` to use the correct gems for your platform (optional).

Use bundler to install the gems.

    $ bundle

Rename `my_kata.rb` and `my_kata_spec.rb` and edit `my_kata_spec.rb` to require
the correct file for your kata, i.e. whatever you renamed `my_kata.rb` to.

Start guard to run your tests automatically.
    
    $ guard

Do your kata! Guard will monitor your files and run your tests automatically
whenever you make a change.
