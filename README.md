# Online-Bank-API
API for an Online Banking System

## Access Database with:
CREATE USER 'bank'@'localhost' IDENTIFIED BY 'api';
CREATE SCHEMA bankapi;
GRANT ALL PRIVILEGES ON bankapi.* TO 'bank'@'localhost';
