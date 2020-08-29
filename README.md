[![Meu Telegram](https://img.shields.io/badge/Meu-Telegram-red)](https://t.me/k4k4rot0)
![GitHub repo size](https://img.shields.io/github/repo-size/k4k4rot0/Dark_Orange?label=Tamanho)
![GitHub contributors](https://img.shields.io/github/contributors/k4k4rot0/Dark_Orange)
![GitHub](https://img.shields.io/github/license/k4k4rot0/Dark_Orange?label=Licen%C3%A7a)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# Instalação e configuração! 

```
git clone https://github.com/k4k4rot0/Dark_Orange.git
```

**Veja se tem o diretório themas** 

```
ls /usr/share/grub/themes
```

**Caso não tenha crie**

```
sudo mkdir /usr/share/grub/themes
```

**Vamos copicar o tema**

```
sudo cp -r dark_squares/ /usr/share/grub/themes
```

**Abra o arquivo:** 

```
sudo nano /etc/default/grub 
```

**e adicione:** 

```
GRUB_THEME="/usr/share/grub/themes/dark_orange/theme.txt"
```

**Atualize o GRUB:** 

```
sudo update-grub
```

**Ou:** 

```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

### Fundo 

Abra a pasta do tema e substitua o arquivo “background.png” para o que você gosta (ele precisa ser o arquivo .png / .jpg) 


### Screenshot 

![screenshot](/imagens/logo-01.jpg)

![screenshot](/imagens/logo-02.jpg)

![screenshot](/imagens/logo-03.jpg)

_Sinta-se livre para copiar o tema e fazer sua própria alteração!;-)_

