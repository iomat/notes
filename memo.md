
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


### ■ 用語
**ICS（Industrial Control System）**

石油、ガス、水道、電気などの生活に欠かせない重要インフラを安定供給させるための産業制御システムのこと。
ICSは工場などで使用されており、リモート制御のためのクラウド移行も検討されることが多くなってきている。
ICSは継続した稼働が求められるため、システムの更新が行われず、古いシステムが未だに現役であることも一般的である。
システムを交換するよりも、システムの停止に伴う損害が重要視される傾向があり、これがICSの特徴である。

<br>

**PLC（Programmable Logic Controller）**

繰り返し動作となるシーケンス制御を専用にしたマイクロコンピュータのこと。
安定的な供給が不可欠な重要インフラでは、システムの反復動作を監視し制御する役割を果たす。

<br>

**DCS（Distributed Contorol System）**

生産設備を構成する機器ごとに設置され、ネットワークを構成することによって管理と制御を行う。

<br>

**HMI（Human Machine Interface）**

グラフィカルに表示し、オペレータが監視したり制御したりできるようにするインターフェース。

<br>

**SCADA（Supervisory Control And Data Acquisition）**

ポンプ、ゲート、バルブなどの設備、水位や水温などの計測データを収集、監視、制御する。


