# rbenv

## rbenv

```
% git clone https://github.com/rbenv/rbenv.git ~/.rbenv

% cd ~/.rbenv && src/configure && make -C src

% echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
% source ~/.bashrc
```

## ruby-build

```
% mkdir -p "$(rbenv root)"/plugins
% git clone https://github.com/rbenv/ruby-build.git "$(rbenv root)"/plugins/ruby-build
```

## check

```
% curl -fsSL https://github.com/rbenv/rbenv-installer/raw/master/bin/rbenv-doctor | bash
```


# Install Ruby

```
% rbenv install --list
% rbenv install 2.6.2
% rbenv global 2.6.2
% rbenv versions
% rbenv rehash
```


# Install Rails

```
% gem install rails bundler
```
