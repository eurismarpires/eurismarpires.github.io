---
layout: post
title:  "Dicas Ruby on Rails"
date:   2016-02-01 15:16:16 -0200
categories: Desenvolvimento RubyOnRails
---
#Instalar Rails com proxy
gem install rails --http-proxy=http://ip:porta

#Resolver problema de proxy com o comando Bundle install
set HTTP_PROXY=http://ip:porta

#CRUD em Ruby on Rails
* rails new appwebexemplo
* cd appwebexemplo
* bundle install
* rails server
* rails generate scaffold appwebexemp nome:string endereco:string
* rake db:migrate
