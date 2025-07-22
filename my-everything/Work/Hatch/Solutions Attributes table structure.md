
|           |                                      |              |                                |                            |                            |
| --------- | ------------------------------------ | ------------ | ------------------------------ | -------------------------- | -------------------------- |
| id        | solution-id                          | key          | value                          | created_at                 | updated_at                 |
| 123456789 | b5e97323-ed62-45e0-bb15-1651fdb5e58f | key_features | ["uses PDF", "smart citation"] | 2025-06-16 22:06:06.480917 | 2025-06-16 22:06:06.480917 |
**Clean repo/start from scratch:**

docker system prune -a

npm run clean
npm install
docker-compose up --build



**After reinstall:**

rm -rf ~/Library/Containers/com.docker.docker/Data/vms/0/data/docker/

npm install  
docker compose up --build

docker compose down

docker compose up --build