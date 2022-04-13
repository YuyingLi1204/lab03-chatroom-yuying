# lab03-chatroom-yuying

#  work have done

deployed to the local environment with no bug
deployed to the heroku with a bug that "POST and GET 4000" which caused that chatter can not send message in the message box.However except the bug,the other function like login and out of the room successfully run in the heroku.

#  work to do

find the solution to solve the "POST and GET 400" bug.

# debug have tried:

(1)install lower version of gunicorn==18.0.0
(2)update Procfile as "web:gunicorn --worker-class eventlet -w 1 app:app"
(3)install another version like eventlet.
