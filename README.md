application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_mysql_user
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

spring.data.redis.host=localhost
spring.data.redis.port=6379


# Number Guessing Game 🎯

A fun and interactive Number Guessing Game built with JavaFX.

## Features
- Three difficulty levels: Easy, Medium, Hard
- Score tracking based on remaining attempts
- Hint system (higher/lower)
- Progress bar for attempts
- Guess history display
- Restart option

## How to Play
1. Select a difficulty level.
2. Enter a number between 1-100 and submit your guess.
3. Follow the hints to find the correct number.
4. Try to guess within the allowed attempts! 

