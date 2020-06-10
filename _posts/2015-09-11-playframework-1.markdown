---
layout: post
title: "Instalando o Play Framework no Ubuntu"
date: 2015-09-11 12:26:50
categories: tutorial, Play Framework, install, ubuntu
---

Como instalar o Play framework no Ubuntu? Nesse tutorial estou usando o Ubuntu 14.04 e o Play Framework 2.4.3.

Siga os seguintes passos:

1. Faça o download do Play no site: https://www.playframework.com/download
2. Descompacte o arquivo e mova o diretório resultante para o local onde você desejar, como, por exemplo, a sua home. Você pode fazer isso usando os comandos do terminal:
{% highlight Shell %}
cd /home/seunome/Downloads
unzip typesafe-activator-1.3.6-minimal.zip -b /home/seunome
{% endhighlight %}
3. Vá até o seu diretório home e abra o arquivo .bashrc. Você pode fazer isso usando os comandos do terminal:
{% highlight Shell %}
cd /home/seunome
nano .bashrc
{% endhighlight %}
4. Vá até o final do arquivo e acrescente a seguinte linha:
{% highlight Shell %}
export PATH=$PATH:/caminho.ate.o.diretorio.do.play
{% endhighlight %}
Em */caminho.ate.o.diretorio.do.play* substituta pelo local onde você salvou o diretório do play, no nosso exemplo a linha ficaria:
{% highlight Shell %}
export PATH=$PATH:/home/seunome/activator-1.3.6-minimal/
{% endhighlight %}
5. Salve e feche o arquivo.
6. Abra o terminal e execute o comando **activator ui**, se tudo tiver ocorrido bem você poderá começar a construir suas aplicações usando o Play!
