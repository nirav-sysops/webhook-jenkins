# webhook-jenkins
This is Jenkins Webhook Repo

Hello, My Name is nirav
First Webhook

version : '3' #Version of YML file

services:
    distro:
        image: alpine
        restart : always
        container_name: custom_alpine
    
    database:
        image: postgres:latest
        container_name: postgres_db
        ports:
            - "5432:5432"
