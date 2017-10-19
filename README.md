# What is ZM?

ZM is the console miner provided by [dstm](https://bitcointalk.org/index.php?topic=2021765.0).

ZM supports Zcash (ZEC).

# How to use this image [NVIDIA version]

Run in background:

```console
$ docker run -d --device /dev/nvidia0 --device /dev/nvidiactl --device /dev/nvidia-uvm --name YOUR_CONTAINER_NAME calvintam236/zm:nvidia --server YOUR_POOL_ADDRESS --port YOUR_POOL_PORT --user YOUR_USERNAME.YOUR_WORKER_NAME --pass YOUR_WORKER_PASSWORD
```

Get `zm` options with:

```console
$ docker run --rm calvintam236/zm:nvidia
```

Fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```
