# postgresql_course
Notes and code from [Udemy PostgreSQL course](https://www.udemy.com/course/sql-and-postgresql)


# NOTES

## Section 1
- Challenges this course addresses:
  - Writing efficient queries
  - Schema design
  - Understanding when, and how, to use advanced features
  - Managing the db in prod
- Database design
  - DB design process:
    - What kind of thing are we storing? --> a list of cities
    - What properties does this thing have? --> each city has a {name, country, population, area}
    - What type of data does each of those properties contain? --> {name: str, country: str, population: numeric, area: numeric}  

    |  |  |  |
    |------------------------------------|------------------|--------------------------------|   
    | Kind of _thing_ we're storing --> | List of cities --> | Create table `cities` |
    | Properties this thing has? --> | Each city has {name, country, pop, area} --> | Table should have columns `{name, country, pop, area}` |  
    | _Type_ of data for each property? --> | {name: str, country: str, pop: int, area: float} --> | Each col should indicate correct data type | 
    | | | | 



