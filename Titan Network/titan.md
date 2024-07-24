# [Run-node-Titan](https://titannet.gitbook.io/titan-network-en)

[<img width="200" alt="665875" src="https://www.titannet.io/img/home/log-one.gif?t=1721840231036">
](https://docs.sui.io/)

### Installing plugins

```
sudo apt-get update && sudo apt-get upgrade -y
```

### Installing the node:

```
rm -r ~/.titanedge
docker pull nezha123/titan-edge
mkdir ~/.titanedge
docker run --network=host -d -v ~/.titanedge:/root/.titanedge nezha123/titan-edge
```

Now go [here](https://test1.titannet.io/intiveRegister?code=nAANHV) and find your identity code

![image](https://assets.quadro.network/img/e8f9f89b-ffa0-43d1-a376-97a6f666fa16.png)



```
docker run --rm -it -v ~/.titanedge:/root/.titanedge nezha123/titan-edge bind --hash=<CODE> https://api-test1.container1.titannet.io/api/v2/device/binding
```


- [Website](https://www.titannet.io/)





