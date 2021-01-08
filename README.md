# spring_mvc_aop_hibernate

Реализация Spring MVC приложения, использовался Maven, Hibernate, Tomcat.
Логика вынесена через DAO и Service.

Проект представляет собой MVC приложение, стартующее по адресу http://localhost:8080/spring_cource_mvc_hibernate_aop_war_exploded/
Главная страница реализует список сотрудников из БД postgreSQL. Настройка БД описана в applicationContext.xml

Добавление, изменение и удаление сотрудника реализовано с помощью Hibernate.

Каждое действие логировано посредством @Around
