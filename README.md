# https://rubyschool.us/ Lesson 22
#создали пустой репозиторий на гитхабе
#склонировали репозиторий в дирректории lesson/22 командой 'git clone https://github.com/DmitryStrazdin/RubySchool_Lesson_22.git'
#командой start ungit запустили фреймворк git
#сделали коммит (вклад). Тут два варианта: коммит локально и на гитхабе
#git pull - автоматически гит подтягивает изменения с сервером. Already up to date - уже синхронизир.
###
#layout.erb - используется как шаблон. Туда в определенные места вставляются наши views
#В какое именно место определяет ключевое слово yield (<%= yield %>)
# erb: welcome будет автоматически вставлен в тоже самое место в layout.erb где
#расположена команда yield
###
#<form action="/visit">  атрибут action говорит куда будем отправлять форму (на страницу визит)
#method="POST" - способ, метод с помощью которого мы будем отправлять
#<input name="username"... атрибут name используется в теге input для передачи запроса на сервер 
#т.е name - имя параметра, под которым наши данные будут отправленны на сервер
