# ProgKiev
Шмыга Алексей

alan.shmyga Skype
alexey.shmyga@gmail.com


21.09.17
В чем разница между абстрактным классом и интерфейсом в java.

Коллекции, принципы ООП.

Selenium design patterns and best practices - книга


26.09.17
//*[@name='btnK'] - xPath для элемента атрибут с именем 'btnK'

// - ищем во всем документе
* - любой элемент с указанными параметрами
@ - атрибут
name, id, class, value - имя атрибута
'btnK' - имя элемента
//a[text()='Карты']
//a[text()='Карты' and @class='q qs']
//li[@class='f-menu-l-i hover']/a[@class='f-menu-l-i-link f-menu-l-i-link-arrow sprite-side novisited']

28.09.17
Создаем Maven проект
С сайта https://mvnrepository.com находим Selenium Java и забираем 
    <dependencies>
        <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>3.6.0</version>
        </dependency>
    </dependencies>
прописываем в проект.

находим junit на сайте https://mvnrepository.com
переносим <dependencies> в проект

Каталог с ChromeDriver прописываем в переменную Path

Д\З
Сценарий логина на сайт

После логина в админ панель убедится что заголовок страницы 
совпадает с названием п.меню.
