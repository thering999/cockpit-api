"Cockpit API" 
- How to Install

git clone https://github.com/cybernude/cockpit-api.git


cd cockpit-api

npm i
tsc
-------------------------------------------------------------------
nodemon bin/www
tsc -w


## หากไม่สมบูรณ์ต้องติดตั้ง

npm install -g yo
npm install -g yo typescript
npm install -g generator-express-ts
npm i -g typings
npm install -g nodemon
npm install knex --save
npm install mysql --save
npm install cors --save
npm install @types/knex @types/mysql --save-dev
npm install dotenv --save
npm install jsonwebtoken --save
npm install crypto-js --save


#รัน api กรณีใน nb เรา ให้เข้าไปที่ D:\xampp\htdocs\cockpit-api (แนะนำทำในโปรแกรม ConEmu) แล้วพิมพ์
- nodemon bin/www

#จากนั้นรัน cockpit-app เรา ให้เข้าไปที่ D:\xampp\htdocs\cockpit-api (แนะนำทำในโปรแกรม ConEmu) แล้วพิมพ์
npm start

ถ้ารันไม่ขึ้นให้ npm i ทุกครั้ง
ถ้ามีการ update ให้ใช้ git pull เอาเฉพาะที่ทีการ update เพิ่มเติม

## add port 3131

firewall-cmd --permanent --add-port=3131/tcp
firewall-cmd --reload
firewall-cmd --list-ports
