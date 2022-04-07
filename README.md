# QoSI
Qualidade de Serviço em Redes IP / Internet

Avaliação intermedia: 28 de Abril
Avaliação final: 19 de Maio

Results to be exported per measurement:
  - latency (https://pypi.org/project/icmplib/)
  - jitter (https://pypi.org/project/icmplib/) 
  - packet loss (https://pypi.org/project/icmplib/)
  - download (https://iperf3-python.readthedocs.io/en/latest/examples.html#client)
  - upload (https://iperf3-python.readthedocs.io/en/latest/examples.html#client)
  - target (azure/aws/ibm/gogle)
  - isp (as-number?) 
  - device type of connection (mobile data/wifi/ethernet)
  - type of device (computer/smartphone)
  - device operating system (linux,windows,macos,android,iphone)
  - date
  - hour

Cloud Virtual Machines (UK/London region):
  - Amazon AWS: 13.40.241.112
  - Alibaba Cloud: 8.208.103.146
  - Azure:
  - Google:
  - IBM:

# Instructions to create virtual machine in cloud:

Install iperf3 on vm:
```sudo yum install iperf3 git```

Clone this git repository:
```git clone https://github.com/pg45517/QoSI.git```

Copy the file:
```sudo cp /etc/systemd/system/```

Reload and start service:
```sudo systemctl daemon-reload```
```sudo systemctl enable iperf```
```sudo systemctl start iperf```
