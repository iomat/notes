
### ■ リソースを確認する

**物理CPUの数**

```
$ grep physical.id /proc/cpuinfo | sort -u | wc -l
```

**CPUあたりのコア数**

```
$ grep cpu.cores /proc/cpuinfo | sort -u
```

**コメント**

物理CPUの数が2でCPUあたりのコア数が4であれば、コアの総数は8である。

**参考**

・https://access.redhat.com/ja/solutions/2159401
