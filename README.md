Cài đặt database
-Chạy lệnh: php artisan migrate
-chạy lệnh: php artisan db:seed
-import dữ liệu từ thư mục DatabaseSQL
Chạy các tiện ích hỗ trợ
-php artisan queue:work --queue=SenMailSale
-php artisan vietnam-map:download
Cấu hình lại file .env chạy Mailhog
MAIL_MAILER=smtp
MAIL_HOST=127.0.0.1
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS=laravel.admin@gmail.com
MAIL_FROM_NAME="${APP_NAME}"
