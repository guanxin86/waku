# waku
## Devnet2
### 官方教程
[Guild](https://docs.pipe.network/devnet-2)
### 启动
```
./pop \
  --ram 16 \
  --max-disk 200 \
  --cache-dir /data \
  --pubKey <KEY>
```
### 常用命令
```
# View metrics
./pop --status

# Check points
./pop --points-route

# Generate referral
./pop --gen-referral-route

# Use referral
./pop --signup-by-referral-route <CODE>
```

## OLD
### docker compose guild
[Guild](https://docs.waku.org/guides/nwaku/run-docker-compose)
### 查看日志
```
cd ./nwaku-compose
docker-compose logs -f nwaku
```
### 查看stats
```
http://localhost:3000/d/yns_4vFVk/nwaku-monitoring #
```
