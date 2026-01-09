# Cheatsheet
## Power on
sudo docker compose up -d
## Power off
sudo socker compose stop

## JudgeHost Log
sudo docker compose logs -f judgehost

## Change admin Password
sudo docker compose exec domserver /opt/domjudge/domserver/webapp/bin/console domjudge:reset-user-password admin admin

## Get admin Password
sudo docker compose logs domserver | grep "Initial admin password"

sudo docker compose ps

hostname -I
