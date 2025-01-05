# People Management Application

## About the Project

This web application is designed for managing a list of people, developed using the Spring Framework and Thymeleaf. The application allows users to perform CRUD (Create, Read, Update, Delete) operations for records of people, including their name, age, and email address.

## Key Features

- **View List of People**: Display all people stored in the database.
- **Add New Person**: A form for entering data for a new person.
- **Edit Information**: Ability to edit existing records.
- **Delete Record**: Remove records of people from the database.

## Technologies

- **Spring MVC**: For creating the web application and handling HTTP requests.
- **Thymeleaf**: A templating engine for dynamically generating HTML pages.
- **Spring JDBC**: For interacting with the PostgreSQL database.
- **Hibernate Validator**: For validating user-entered data.

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Dyglaz/spring-people-management
   cd spring-people-management
   ```

2. **Set up the database**:
    - Ensure that PostgreSQL is installed.
    - Create a database named `first_db`:
      ```sql
      CREATE DATABASE first_db;
      ```

3. **Configure connection parameters**:
    - Open the `SpringConfig` class and modify the database connection parameters (URL, username, password) in the `dataSource()` method:
      ```java
      dataSource.setUrl("jdbc:postgresql://localhost:5432/first_db");
      dataSource.setUsername("your_username");
      dataSource.setPassword("your_password");
      ```

4. **Run the application**:
    - Use your IDE or command line to run the application.

## Usage

- Navigate to `http://localhost:8080/people` to access the application.
- Use the interface to add, edit, and delete records of people.

--- 

# Приложение для управления людьми

## О проекте

Это веб-приложение предназначено для управления списком людей и разработано с использованием Spring Framework и Thymeleaf. Приложение позволяет пользователям выполнять операции CRUD (создание, чтение, обновление и удаление) для записей о людях, включая их имя, возраст и адрес электронной почты.

## Основные функции

- **Просмотр списка людей**: Отображение всех людей, сохраненных в базе данных.
- **Добавление нового человека**: Форма для ввода данных нового человека.
- **Редактирование информации**: Возможность редактировать существующие записи.
- **Удаление записи**: Удаление записей о людях из базы данных.

## Технологии

- **Spring MVC**: Для создания веб-приложения и обработки HTTP-запросов.
- **Thymeleaf**: Шаблонизатор для динамической генерации HTML-страниц.
- **Spring JDBC**: Для взаимодействия с базой данных PostgreSQL.
- **Hibernate Validator**: Для валидации данных, введенных пользователями.

## Установка и настройка

1. **Клонируйте репозиторий**:
   ```bash
   git clone https://github.com/Dyglaz/spring-people-management
   cd spring-people-management
   ```

2. **Настройте базу данных**:
    - Убедитесь, что у вас установлен PostgreSQL.
    - Создайте базу данных с именем `first_db`:
      ```sql
      CREATE DATABASE first_db;
      ```

3. **Настройте параметры подключения**:
    - Откройте класс `SpringConfig` и измените параметры подключения к базе данных (URL, имя пользователя, пароль) в методе `dataSource()`:
      ```java
      dataSource.setUrl("jdbc:postgresql://localhost:5432/first_db");
      dataSource.setUsername("your_username");
      dataSource.setPassword("your_password");
      ```

4. **Запустите приложение**:
    - Используйте вашу IDE или командную строку для запуска приложения.

## Использование

- Перейдите по адресу `http://localhost:8080/people` для доступа к приложению.
- Используйте интерфейс для добавления, редактирования и удаления записей о людях.
   
