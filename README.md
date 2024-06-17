# WeConnect.Grafana
Grafana Console with VW WeConnect API capture via python

Inspired by https://github.com/tillsteinbach/WeConnect-mqtt which is able to capture via Pyhton the data of your VolksWagen vehicle via the WeConnect API, I captured the Json Topic via TELEGRAF (InfluxDB2) and created this Grafana Dashboard that I make available to you.

You will also find the part of code to insert inside your "telegraf.conf" file for parsing data from MQTT/Json to InfluxDB2

<img width="2027" alt="Screenshot 2024-06-17 at 11 20 44" src="https://github.com/mk4001/WeConnect.Grafana/assets/50479511/e994307f-4da0-47a5-919b-dd0992530a78">
