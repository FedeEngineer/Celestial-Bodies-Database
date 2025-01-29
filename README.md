
# Universe Database Project

## 🚀 Overview

This project involves creating a relational database for a simulated "universe" containing galaxies, stars, planets, moons, and asteroid belts. The database captures the hierarchical relationships between these celestial bodies and stores relevant information such as their names, sizes, and characteristics.

## 📊 Tables in the Database

### Galaxy Table
Stores information about galaxies, such as name, size, distance from Earth, and an optional description.

![image](https://github.com/FedeEngineer/Celestial-Bodies-Database/blob/main/img/galaxy.png)

### Star Table
Stores information about stars within galaxies. Each star belongs to a galaxy.
![image](https://github.com/user-attachments/assets/509b62d8-798c-4c9f-baac-72e56c1f2628)

### Planet Table
Stores information about planets. Each planet is associated with a star.
![image](https://github.com/user-attachments/assets/824ff783-9b73-485e-bfce-f012d389c6a2)

### Moon Table
Stores information about moons orbiting planets. Each moon is associated with a planet.
![image](https://github.com/user-attachments/assets/f1b07f9c-1542-4d15-871b-3d04abc1be42)

### Asteroid Belt Table
Stores information about asteroid belts. Each asteroid belt is associated with a planet.
![image](https://github.com/user-attachments/assets/51047436-7d4e-4c18-a456-6e585fa48da0)

# ⚙️ Features Implemented

* Relational Structure: The database is structured with foreign keys to represent the relationships between galaxies, stars, planets, moons, and asteroid belts.
* Data Types: The database uses various data types such as VARCHAR for text data, NUMERIC for numerical data, BOOLEAN for true/false values, and TEXT for larger textual descriptions (e.g., descriptions of galaxies).

#### Constraints:
* Each table has a primary key.
* Several tables include foreign key constraints to ensure referential integrity between related entities (e.g., stars reference galaxies, planets reference stars, moons reference planets).
* At least one column in each table is required to be unique.
* Some columns do not accept NULL values.
