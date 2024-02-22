# Basic-Authentication-Jwt-Token
This project was created to learn how to authenticate the JWT token.

## How to start
1. Create database in docker following this step [**PostgreSQL in docker**].
2. Create table _user with
```
create table _user (
	id SERIAL not null,
	firstname VARCHAR (255),
	lastname VARCHAR (255),
	email VARCHAR (255),
	password VARCHAR (255),
	role VARCHAR (255),
	primary key (id)
);
```
3. Start this project.
4. Test API with Postman collection.

## Reference
**PostgreSQL in docker:** `https://www.commandprompt.com/education/how-to-create-a-postgresql-database-in-docker/` \
**Secure your API with JWT Token:** `https://www.youtube.com/watch?v=BVdQ3iuovg0&t=4052s` \
**Check value JWT token:** `https://jwt.io/`
