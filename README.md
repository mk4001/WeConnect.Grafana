# WeConnect.Grafana
Grafana Console with VW WeConnect API capture via python

Inspired by https://github.com/tillsteinbach/WeConnect-mqtt which is able to capture via Pyhton the data of your VolksWagen vehicle via the WeConnect API, I captured the Json Topic via TELEGRAF (InfluxDB2) and created this Dashboard that I make available to you.
You will also find the part of code to insert inside your "telegraf.conf" file for parsing from MQTT/Json to InfluxDB2

https://github.com/mk4001/WeConnect.Grafana/blob/49aa21a79796cd8e53933ae45e868153a0b888b0/Screenshot%202024-06-16%20at%2016.26.59.png

https://github.com/mk4001/WeConnect.Grafana/blob/49aa21a79796cd8e53933ae45e868153a0b888b0/Screenshot%202024-06-16%20at%2016.40.32.png
