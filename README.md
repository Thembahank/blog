# Themba's Profile and Blog

## Install

See: https://jekyllrb.com/docs/quickstart/

```bash
brew/apt-get install rbenv ruby-build
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
source ~/.bash_profile
rbenv install 2.5.1
rbenv global 2.5.1
ruby -v

# open new terminal
gem install jekyll bundler
bundle install
```


## Run the server

```bash
make server
```
