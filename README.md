# CSC3916 HW2

## Description:
A standard REST server (POST,GET,PUT,DELETE) using NodeJS/Express. Original code is under '/movies' implementation.

## How-to:
app.js can be run locally with 'node -r dotenv/config app.js' in order for the server to get keys from .env file.

## POSTMAN:
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/a78ee62e952a2e8ed521?action=collection%2Fimport#?env%5BHomework2_gryzick%5D=W3sia2V5Ijoiand0X3Rva2VuIiwidmFsdWUiOiJ0b2tlbiBoZXJlIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InRleHQiLCJzZXNzaW9uVmFsdWUiOiJKV1QuLi4iLCJzZXNzaW9uSW5kZXgiOjB9XQ==)
Check that the environment 'Homework2_gryzick' is enabled in Postman. Postman needs to store 'jwt_token' from the '/signin' POST in an environment variable in order for jwt authentication to succeed.
