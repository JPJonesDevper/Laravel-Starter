# Laravel Starter
โปรเจคนี้สร้างขึ้นเพื่อผู้ใช้งานที่ต้องการขึ้นโปรเจคในระดับหนึ่ง ซึ่งภายในโปรเจคได้สร้างระบบ Authentication และสามารถจัดการผู้ใช้งานเบื้องต้นได้

# Tools
  - Laravel 5.6 ศึกษาเพิ่มเติม: https://laravel.com/docs/5.6/
  - VueJS 2.5.7 ศึกษาเพิ่มเติม: https://vuejs.org/v2/guide/
  - UIkit ศึกษาเพิ่มเติม: https://getuikit.com/docs/introduction/

# Setup
  1. ทำการติดตั้ง Composer สามารถทำการดาวน์โหลด และศึกษาวิธีติดตั้งได้ที่: https://getcomposer.org/
  2. ทำการติดตั้ง NodeJS สามารถทำการดาวน์โหลด และศึกษาวิธีติดตั้งได้ที่: https://nodejs.org/en/
  3. หลังจกาทำการ Clone โปรเจคลงมายังเครื่อง Local แล้วให้ทำดังต่อไปนี้
      3.1 เปิด Terminal (Mac , Linux , Ubuntu) หรือ Command (Windows)
      3.2 เข้าไปยังโปรเจคที่ได้ทำการ Clone ลงมายังเครื่อง Local
      3.3 ใช้คำสั่ง composer install เพื่อติดตั้ง Package ต่าง ๆ (composer.json)
      3.4 ใช้คำสั่ง npm install เพื่อติดตั้ง Package ต่าง ๆ (package.json)
      3.5 ทำการแก้ไข File .env ในโปรเจค แก้ไขดังต่อไปนี้
          - สังเกตบรรทักที่ 10 - 12
          - DB_DATABASE= ใส่ชื่อ db ที่ต้องการเชื่อมต่อ
          - DB_USERNAME= username ของ db
          - DB_PASSWORD= password ของ db
      3.6 หลังจากทำข้อ 3.5 เสร็จแล้ว ให้ใช้คำสั่งดังต่อไปนี้
          - php artisan migrate ใช้สำหรับสร้าง Table ใน DB
          - php artisan serv & npm run dev หรือ php artisan serv & npm run watch
  4. ทำสอบ localhost:8000
