1. Создать внешний репозиторий c названием “XML”

        New → Create repository
2. Клонировать репозиторий “XML” на локальный компьютер

        git clone https://github.com/kolikplatis/XML.git
3. Внутри локального “XML” создать файл “new.xml”

        touch new.xml
4. Добавить файл под гит

        git add .
5. Закоммитить файл

        git commit -m “new.xml”
6. Отправить файл на внешний GitHub репозиторий

        git push
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата).Всё написать в формате XML
        
        cat >> new.xml
        <candidate>
            <FIO>J J Simmons</FIO>
            <Age>60</Age>
            <Pets>2</Pets>
            <Expected_salary>100000</Expected_salary>
        </candidate>

8. Отправить изменения на внешний репозиторий

        git add .
9. Создать файл “preferences.xml”

        > preferences.xml
10. В файл preferences.xml добавить информацию о своих предпочтениях (любимый фильм, любимый сериал, любимая еда, любимое время года, страна, которую хотели бы посетить) в формате XML

        cat >> preferences.xml
        <preferences>
            <favorite_film>Departed</favorite_film>
	        <favorite_series>Method</favorite_series>
            <favorite_food>pizza</favorite_food>
            <favorite_season>summer</favorite_season>
            <desired_country>Serbia</desired_country>
        </preferences>
11. Создать файл “sklls.xml”, добавить информацию о скиллах, которые будут изучены на курсе в формате XML

        cat > skills.xml
12. Сделать коммит в одну строку

        git commit -am “2 files”
13. Отправить сразу 2 файла на внешний репозиторий

        git push
14. На веб-интерфейсе создать файл “bug_report.xml”

        - кнопка [Add file]
        - кнопка [Create new file]
15. Сделать Commit changes (сохранить) изменения на веб-интерфейсе

        кнопка [Commit changes]
16. На веб-интерфейсе модифицировать файл “bug_report.xml”, добавить багрепорт в формате XML

        кнопка [Edit this file]
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе

        кнопка [Commit changes]
18. Синхронизировать внешний и локальный репозиторий XML

        git pull

