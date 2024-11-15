# Конспект по первой практике
## Распределение баллов
1.  Домашние работы (20 баллов).
2.  Летучки, устные ответы (10 баллов).
3.  Контрольные работы (20 баллов).
## Правила приема домашних работ
1.  У каждой работы есть свой дедлайн (срок выполнения).
2.  Если успеваешь выполнить работу в срок, гарантированно можно получить все баллы.
3.  Если не успеть, то есть резервный срок, но если выполнить во время него, то уже таких гарантий не будет.
4.  Если не успеть в резервный срок, то баллы режутся пополам
5.  Срок сдачи всех домашних работ заканчивается за 3 недели до конца семестра. Всё, что не сдали к этому сроку, просто не проверяется.
## Уровни языков программирования
1) Hardware
2) Machine Language
3) Assembly Language
4) High Level Language (C, C#, C++, Python, Java, JavaScript, Ruby)
## Типы языков программирования
1) Структурные
2) Процедурные
3) Функциональные
4) Объектно-ориентированные (ООП)
## Принцип работы .Net
**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUcPoeFvDBav1Ue9Ofk72yKywlLAO7VdQQz8VZPXCbZBa48Kh3gC0aZoX6tiis7wM8v15NecptWgTPKQm_11MUTyI8v2m4yYzkcGI4v4B8QWfmzNOfhvQ9EOT2u-mOB6BPYatKJvnhD4CMPsWcqxIwp6XDSj_fET=s2048?key=ioesny1-am-zBCTxlH-YhQ)**
## Команды для создания решения

    //Создание решения
    dotnet add sln
    
    //Создание консольного проекта
    dotnet new console -o TestConsole (создание нового проекта в папке TestConsole внутри выбранной)
    
    //прикрепить проект к решению
    dotnet sln названиеРешиения.sln add путьПроекта
    
    //Выбор папки проекта
    cd TestConsole
    //Запуск проекта
    dotnet run

## Действия с git
    //регистрация:
    git config --global user.name "Имя пользователя"
    git config --global user.email ПочтаПользователя
	
	//инициализация git: 
	//либо:
	git clone https://github.com/username/repoName.git
	//либо:
	git init
	git remote add https://github.com/username/repoName.git

	//начать отслеживать файл:
	git add fileName
	git add . (отслеживать всё)
	
	//закоммитить (сохранить)
	git commit -m "комментарий к коммиту"

	//залить (в main):
	git push -u origin main

	//обновиться:
	git pull (текущая ветка)
	git fetch (все ветки)
    

