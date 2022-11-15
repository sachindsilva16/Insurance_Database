# Insurance_Database



CREATE DATABASE INSURANCE_DATABASE;
USE INSURANCE_DATABASE;

CREATE TABLE PERSON(
DRIVER_ID VARCHAR(10) PRIMARY KEY,
NAME VARCHAR(20),
ADDRESS VARCHAR(50),
);

SELECT * FROM PERSON;

CREATE TABLE CAR(
REG_NUMBER VARCHAR(10) PRIMARY KEY,
MODEL VARCHAR(20),
MODEL_YEAR INT
);

SELECT * FROM CAR;

CREATE TABLE ACCIDENT(
REPORT_NUMBER INT PRIMARY KEY,
ACCIDENT_DATE DATE,
LOCATION VARCHAR(20)
);

SELECT * FROM ACCIDENT;


CREATE TABLE OWNS(
DRIVER_ID VARCHAR(10),
REG_NUMBER VARCHAR(10)
);
