# Lugano

`/luˈɡaːno/`


## Setup

```zsh
% python -m venv venv
% source venv/bin/activate

(venv) % pip install --upgrade pip setuptools
(venv) % pip install nodeenv

(venv) % nodeenv -p --node=7.10.1

(venv) % npm install --upgrade -g npm
(venv) % npm install -g gitbook-cli
(venv) % gitbook fetch 3.2.3
(venv) % gitbook install
```

## Development

```zsh
(venv) % gitbook serve
```
