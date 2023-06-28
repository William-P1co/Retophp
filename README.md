# Retophp
reto
willliam Ferney Pico Duran
apolo

BD

mysql -u campus -p
campus2023

CREATE DATABASE CAMPUS;

CREATE TABLE PAIS(
idPais int primary key,
nombrePais int 
);

CREATE TABLE departamento(
idDepartamento int primary key,
nombreDepartamento varchar(50),
idPais int 

);
CREATE TABLE region(
idRegion int primary key,
nombreRegion varchar(50),
idDepartamento int
);

CREATE TABLE campers(
idCamper varchar(50) primary key,
nombreCamper varchar(50),
apellidoCamper varchar(50)
fechaNac: date ,
idRegion int
);
