[![Travis-CI Build Status](https://travis-ci.org/decryptr/captchaSajAudio.svg?branch=master)](https://travis-ci.org/decryptr/captchaSajAudio)

# captchaSajAudio

Quebra captcha do sistema e-SAJ por áudio.

## Instalação

```
if (!require(devtools)) install.packages('devtools')
devtools::install_github('captchaSajAudio')
```

## Exemplo

```
library(captchaSajAudio)
arq <- system.file('exemplo.mpg', package = 'captchaSajAudio')
decifrar(arq)
```

