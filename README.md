# etherpad-lite_dockercompose

```
mkdir -p etherpad_data/node_modules redis_data/
ln -s ../src etherpad_data/node_modules/ep_etherpad-lite

cat << EOF > .env
DB_PASSWORD=replace
ETHERPAD_API_KEY=replace
ETHERPAD_ADMIN_PASSWORD=replace
EOF
```
