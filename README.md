# Перечислите алерты, которые настроены в Prometheus alerts.

## containers

/etc/prometheus/alert.rules

jenkins\_down, jenkins\_high\_cpu, jenkins\_high\_memory

## host

/etc/prometheus/alert.rules

high\_cpu\_load, high\_memory\_load, high\_storage\_load

## targets

/etc/prometheus/alert.rules

monitor\_service\_down

# Перечислите количество dashboards в Grafana, для какого ПО они?
4 дашборда

Docker (containers, host), Monitoring (Prometheus), Nginx

# Сделайте скриншот работающего dashboards docker containers grafana, перечислите метрики, которые там есть.

CPU Load, CPU Cores, Memory Load, Used Memory, Storage Load, Used Storage, Running Containers, System Load, I/O Usage, Container CPU Usage, Container Memory Usage, Container Cached Memory Usage, Container Network Input, Container Network Output

