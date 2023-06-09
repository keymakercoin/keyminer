# Keyminer BTC Collider


Used in brute-forcing Bitcoin private keys. The main purpose of this project is to contribute to the effort of solving the Bitcoin puzzle transaction: A transaction with 32 addresses that become increasingly difficult to crack. This miner is preset to use pool.keymaker.cc for the pool address. 

![](./keyminer.png)

### Rewards

There are two ways to receive mining rewards using this system. 

**1.** For every range assigned to your miner you will receive the current market price of KEY times 2500.

**2.** If a puzzle is solved then each miner will receive double the amount of KEY based on the total balance. 


### Settings

Depending on the type of NVIDIA card you may need to adjust these swiches based on the memory capacity. These settings work well with the RTX 3060TI GPU.  

keyminer-cli.exe --blocks=64 --points=2500 --threads=256


###

Commands
```
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
                                [HELP]

 --user=                  Enter Keymaker worker 
       ex: 39vd38JG9ZCzyAraRrfTQLLqHzWNB2dabh.w
 --points=2500            N blocks")
 --blocks=64              N threads per block
 --threads=256            N points per thread
 --collide=false          Enables or Disabled Collision mining
 --puzzle=65              Set the current puzzle / bit range to look for collisions

 --pool=https://pool.keymaker.cc  Sets the pool server address.

Example:
keyminer-cli --user=39vd38JG9ZCzyAraRrfTQLLqHzWNB2dabh.w1 --collide=true --puzzle=65

■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
```

### Dependencies
 
.NET: Dotnet Core 6.0
For CUDA: CUDA Toolkit 10.1

### Supporting this project
If you find this project useful and would like to support it, consider making a donation. Your support is greatly appreciated!

<b>KEY:</b>  KcKhd2xtLcQ9hwkxa4WCBATjLgSyXfPZDL
