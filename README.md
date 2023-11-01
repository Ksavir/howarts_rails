# Howarts_rails

Pagina creada en RoR para poder mostrar información de una base de datos y ser desplegada a la plataforma heroku

## Descripción

la pagina mostrara los datos de una base de datos, estos datos fueron creados usando la gema faker


## Puedes echarle un vistazo

https://howarts-ruby-on-rails-98954b9eabd9.herokuapp.com/

## Empezando 🚀

Estas instrucciones te guiarán para obtener una copia de este proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

### Prerrequisitos 📋

Lista de software y herramientas, incluyendo versiones, que necesitas para instalar y ejecutar este proyecto:

- Sistema Operativo windows, ubuntu o mac
- Lenguaje de programación Ruby 3.2.2
- Framework Rails 7.0.6
- Postgrestql 14.8

### Instalación 🔧

Clona el repositorio con el siguiente comando

```bash
git clone https://github.com/ksavir/howarts_rails.git
```

En la terminal accede a la carpeta donde esta el repositorio y ejecuta
(recuerda que para que esto funcione debes tener instalado ruby y la gema bundle)

```bash
bundle install
```

Inicia la base de datos con el siguiente comando

```bash
rails db:create db:migrate

rails db:seed
```

Finalmente ejecuta el proyecto con el siguiente comando y ve a la ip que saldra en la consola

```bash
rails s
```

## Construido Con 🛠️

Explica qué tecnologías usaste para construir este proyecto. Aquí algunos ejemplos:

- [Ruby](https://www.ruby-lang.org/es/) - El lenguaje utilizado
- [Ruby on Rails](https://rubyonrails.org) - El framework web utilizado
- [Ruby gems](https://rubygems.org) - Gestión de dependencias

## Autores ✒️

- **Kevin Rivas** - [Kevin Rivas](https://github.com/ksavir)
