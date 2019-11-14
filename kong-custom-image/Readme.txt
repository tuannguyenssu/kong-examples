Rebuild lại kong image
docker-compose build kong
Chạy với image mới vừa build
docker-compose up -d

Kiểm tra kết quả
http://localhost:8000/api/users

Đẩy lên Docker Hub
docker push tuannguyenssu/kong:latest