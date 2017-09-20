Base painel admin
========

Base para sistema administrativo, utilizando Rails 4.2.3, banco de dados PostgreSQL e tema AdminLTE. I18n padronizado para pt-BR.

### Recursos instalados

* Devise / Devise Invitable
* CanCanCan
* Inherited Resources
* Paperclip
* Sidekiq
* Simple Form
* Slim
* Squeel
* AdminLTE
* Bootstrap
* FontAwesome
* Simple Navigation
* Toastr
* Notify.js
* jQuery Mask
* SweetAlert
* LazyLoad (imagens)


### Uso  

Após clonar o projeto, deve-se ajustar:  

**CanCanCan:** Classe Ability conforme necessidade, até o momento foi implementado para o model User  
**Devise:** Model User conforme necessidade, db configurado com devise para: `recoverable`, `trackable`, `lockable`, `invitable`  
**Tema:** Alterar o arquivo `app/views/layouts/admin.html.erb`, substituindo a cor por `blue`, `yellow`, `green`, `purple`, `red`, `black`, com variações `-light` após as cores, ex: `blue-light`


### TODO

**Devise:** Padronização nos e-mails com templates e informações sensíveis  
**Searchkick:** Implementar elasticsearch
