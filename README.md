# ruby-dojo-toolkit
A set of tools for Randori code dojo.

## Setup
1. Clone the repo: `https://github.com/gracjan-grala/ruby-dojo-toolkit.git`
2. Run `bundle install`
3. (optional) Install [direnv](http://direnv.net/) if you don't have it
4. (optional) Run `direnv allow`
5. (optional) Delete the git history of this repo: `rm -Rf .git`

## Usage
Specs go into `spec/`.

Code goes into `app/`.

1. Run `guard`.
2. Write some tests.
3. Write some code.
4. When you're green, run `dojo`. It will commit.

This way, you can `git reset --hard` easily when you want to get back to your most recent green.
