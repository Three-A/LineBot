# LineBot

How to build it

1. Make Account in Developer.line.me
2. login
3. create provider
4. go to messaging API(Setting: Generate Tokens, Make Webhooks to be enable, if you want bot to join a group you can enabled it)
5. open line@ -> Make Account if you not have it
6. configure Apps in developer line
7. insert App name and in pipeline you can ignore it
8. build a new folder in your directory and open cmd with path in your directory -> you can type 'heroku login' to login heroku
9. in cmd you can type 'composer init' 
   -package name you can safe with forman vendor/name, example: Yudha/line-bot-app
   -Author = skip if you wan't to fill it
   -minimum stability =  (alpha/beta) but you can skip it 
   -Package Type = Project ( you can fill it anything)
   -Would you like to define your dependecies? Yes
   -Search for a package: php
   -Search for a package: slim/slim
   -Search for a package: linecorp/line-bot-sdk
   -after that you can just enter it until closed
   -after closed in that menu, you can type 'composer install'
 (if you confused with step 9, you can see in the picture)
 
![alt text](https://scontent.fcgk6-1.fna.fbcdn.net/v/t1.0-9/29314674_10209171853013343_8067122742437549543_n.jpg?oh=3323bcc266b006385abc0b0ff529d0d9&oe=5B477712)
![alt text](https://scontent.fcgk6-1.fna.fbcdn.net/v/t1.0-9/29262053_10209171854733386_1401831843793893175_n.jpg?oh=1be9ad4c16f4865b0a3e7e0d5a3f451a&oe=5B2A339A)

10. Create file index.php in directory file
![alt text](https://scontent.fcgk6-1.fna.fbcdn.net/v/t1.0-9/29244147_10209171864333626_369135823610258485_n.jpg?_nc_cat=0&oh=36e2add66b3a79c5668c6e67c447a7ef&oe=5B3F2190)

(you can see in project what you must fill in index.php and dont forget to fill token with your token from developer.line.me)

11. Create Procfile and you can type 'web: $(composer config bin-dir)/heroku-php-apache2' and Save
12. deploy your project
    1. in cmd you can type 'heroku create yourProjectName'
    2. git init
    3. heroku git: remote -a yourProjectName
    4. git add . 
    5. git commit -m "initial commit"
    6. git push heroku


<B> IF YOU HAVE ANY QUESTION, YOU CAN ADD MY LINE@ with ID: @wjq3537y Thanks You </B>
