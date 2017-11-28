# Lugano

`/luˈɡaːno/`

[![pipeline status][pipeline]][commit]


```txt

\_|_)
  |            __,  __,   _  _    __
 _|    |   |  /  | /  |  / |/ |  /  \_
(/\___/ \_/|_/\_/|/\_/|_/  |  |_/\__/
                /|
                \|

Lugano; scrolLiris Useful Guide ANd help dOcumentation
```

This documentation project is a guide and help documentation to [Scrolliris](
https://about.scrolliris.com/). Read it on [online](
https://help.scrolliris.com/).


## Repository

https://gitlab.com/scrolliris/lugano


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


## License

```txt
Lugano
Copyright (c) 2017 Lupine Software LLC
```

`GFDL-1.3`

The project is distributed as GNU Free Documentation License. (version 1.3)

```txt
Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "GNU
Free Documentation License".
```

See [LICENSE](LICENSE).


[pipeline]: https://gitlab.com/scrolliris/lugano/badges/master/pipeline.svg
[commit]: https://gitlab.com/scrolliris/lugano/commits/master
