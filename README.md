# Laravel Starter
เพื่อศึกษา Laravel และ VueJS

# Tools
  - Laravel 5.6 ศึกษาเพิ่มเติม: https://laravel.com/docs/5.6/
  - VueJS 2.5.7 ศึกษาเพิ่มเติม: https://vuejs.org/v2/guide/
  - UIkit ศึกษาเพิ่มเติม: https://getuikit.com/docs/introduction/

# Setup
  1. ทำการติดตั้ง Composer สามารถทำการดาวน์โหลด และศึกษาวิธีติดตั้งได้ที่: https://getcomposer.org/
  2. ทำการติดตั้ง NodeJS สามารถทำการดาวน์โหลด และศึกษาวิธีติดตั้งได้ที่: https://nodejs.org/en/
  3. หลังจกาทำการ Clone โปรเจคลงมายังเครื่อง Local แล้วให้ทำดังต่อไปนี้ <br>
      3.1 เปิด Terminal (Mac , Linux , Ubuntu) หรือ Command (Windows) <br>
      
      3.2 เข้าไปยังโปรเจคที่ได้ทำการ Clone ลงมายังเครื่อง Local <br>
      
      3.3 ใช้คำสั่ง composer install เพื่อติดตั้ง Package ต่าง ๆ (composer.json) <br>
      
      3.4 ใช้คำสั่ง npm install เพื่อติดตั้ง Package ต่าง ๆ (package.json) <br>
      
      3.5 ทำการแก้ไข File .env ในโปรเจค แก้ไขดังต่อไปนี้
          - สังเกตบรรทักที่ 10 - 12 <br>
          - DB_DATABASE= ใส่ชื่อ db ที่ต้องการเชื่อมต่อ <br>
          - DB_USERNAME= username ของ db <br>
          - DB_PASSWORD= password ของ db <br>
          
      3.6 หลังจากทำข้อ 3.5 เสร็จแล้ว ให้ใช้คำสั่งดังต่อไปนี้ <br>
          - php artisan migrate ใช้สำหรับสร้าง Table ใน DB <br>
          - php artisan serv & npm run dev หรือ php artisan serv & npm run watch <br>
          
  4. ทดสอบ Run Project: localhost:8000
