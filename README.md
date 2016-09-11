# benchmarks


process
```
apt-get install time bzip2 libx11-dev libgl1-mesa-dev libxext-dev perl perl-modules make gcc unzip
wget https://github.com/kdlucas/byte-unixbench/archive/master.zip
unzip master.zip
cd byte-unixbench-master
cd UnixBench
./Run
bash <(wget --no-check-certificate -O - https://raw.github.com/mgutz/vpsbench/master/vpsbench)bash <(wget --no-check-certificate -O - https://raw.github.com/mgutz/vpsbench/master/vpsbench)
wget https://raw.githubusercontent.com/Kaperstone/benchmarks/master/net.sh -O - -o /dev/null|bash
```
