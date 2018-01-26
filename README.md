# claymore
Dockerized claymore miner

# Summary
Dockerizes the claymore miner binary. Run the docker container as if it were the actual binary, simply pass in flags.

# Run
```
$: docker run --rm -t \
--runtime=nvidia \
djenriquez/claymore

????????????????????????????????????????????????????????????????ͻ
?     Claymore's Dual ETH + DCR/SC/LBC/PASC GPU Miner v10.0      ?
????????????????????????????????????????????????????????????????ͼ
.
.
.
$:
```
## Example
```
docker run -d -t \
--name claymore \
--restart always \
--runtime=nvidia \
djenriquez/claymore \
-zpool zcl.suprnova.cc:4042 -zwal t1WsdsfAzbxUXPgVhT63nm62q97divGgp1s -zpsw x -allpools 1
```
# Dependencies
- nvidia GPUs
- CUDA drivers for your machine, see https://developer.nvidia.com/cuda-downloads?target_os=Linux
- [nvidia-docker](https://github.com/NVIDIA/nvidia-docker)

## Donations
- BTC - 33DyXVuy3R5jfLZRRpEQcXXAJ1Xz5rkGxE
- LTC - MUaov1JidbnpfeuQiSR3mtJhN3CN8Wj5g9
- ETH - 0xCBBC579Ac1Bc4868823fbBb2D8dDaFF93D619ceD
- DASH - Xy4cgJVAiHsrbeBB53NeQWk2iXKoWjBvJp
- ZEC - t1gYs8Zn2ZCFZWKZsTmZWd5bgXa9eD8M87K
- BCH - LOL