# mqtt-benchmark

A simple MQTT (broker) benchmarking tool.

## Usage

```shell
cargo install mqtt-benchmark
```

## Help
```text
$ mqtt-benchmark  --help
A simple MQTT (broker) benchmarking tool.

Usage: mqtt-benchmark [OPTIONS]

Options:
  -c, --client-id <CLIENT_ID>    MQTT client id [default: mqtt-benchmark]
  -b, --broker <BROKER>          MQTT broker [default: localhost:1883]
  -t, --topic <TOPIC>            MQTT topic [default: test]
  -u, --username <USERNAME>      MQTT username
  -p, --password <PASSWORD>      MQTT password
  -q, --qos <QOS>                MQTT qos [default: 1]
  -P, --payload <PAYLOAD>        MQTT payload, allowed to be empty
  -s, --size <SIZE>              The number of data entries generated by each client [default: 100]
  -C, --client-num <CLIENT_NUM>  The number of MQTT clients that are created [default: 10]
  -h, --help                     Print help
  -V, --version                  Print version
```