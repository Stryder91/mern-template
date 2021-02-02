# MERN template avec todo list app.
Mongo - Express - Reactjs - Nodejs


## Composants & setup
Composants : bootstrap, nodemon, axios.

npm install in frontend & backend folder.

> mkdir -p /data/db

Install [mongodb](https://docs.mongodb.com/manual/administration/install-community/)

Avec linux ubuntu : 
> wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | sudo apt-key add -
> echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.2.list
> sudo apt-get update
> sudo apt-get install -y mongodb-org

(Si problème ne reconnait pas mongodb-org alors faire mongodb)

> sudo systemctl start mongod

Si 'Failed to start mongod.service: Unit mongod.service not found.'

alors ....

> mongo

Ne pas oublier si besoin est:
> sudo npm install nodemon -g --save

https://medium.com/codingthesmartway-com-blog/the-mern-stack-tutorial-building-a-react-crud-application-from-start-to-finish-part-2-637f337e5d61

