# bench-sh

A VPS benchmarking script with various features.

Demo Results: https://pastebin.com/rV1DayRp

## Direct Run

```sh
wget -qO- https://raw.githubusercontent.com/Sn1F3rt/bench-sh/main/bench.sh | bash
```
OR
```sh
curl -Lso- https://raw.githubusercontent.com/Sn1F3rt/bench-sh/main/bench.sh | bash
```

## Parameters

Help Page:
`./bench.sh -h`

System Info + Speedtest IPv4 + Drive Speed:
`./bench.sh`
Classic mode. This will use 1.5 GB bandwidth!

System Info + Speedtest IPv6 + Drive Speed:
`./bench.sh -6`
IPv6 only speed test. This will use 1 GB bandwidth!

System Info + Speedtest IPv4 & IPv6 + Drive Speed:
`./bench.sh -46` or `./bench.sh -64`
Dual stack speed test. This will use 2.5 GB bandwidth!

System Info:
`./bench.sh -sys`
System information only.

Drive Speed:
`./bench.sh -io`
Drive speed test via DD only.

System Info + Speedtest IPv4 + Drive Speed + System Benchmark:
`./bench.sh -b`
Classic mode with system benchmark. This will use 1.5 GB bandwidth!

System Info + Speedtest IPv6 + Drive Speed + System Benchmark:
`./bench.sh -b6`
IPv6 only speed test with system benchmark. This will use 1 GB bandwidth!

System Info + Speedtest IPv4 & IPv6 + Drive Speed + System Benchmark:
`./bench.sh -b46` or `./bench.sh -b64`
Dual stack speed test with system benchmark. This will use 2.5 GB bandwidth.

## Issues/Suggestions

If you would like to report any issue with the script, any of the speedtest servers or suggest an improvement in general, please create an issue on this GitHub repository. 

## License

Copyright (c) 2019-2025 Sayan "sn1f3rt" Bhattacharyya  
Copyright (C) 2015 - 2017 by Hidden Refuge (Various bug fixes and performance improvements)  
Copyright (C) 2011 by dmmcintyre3 (Speed Test Modification)  
Copyright (C) 2011 by akamaras/camarg (Original Script)  
