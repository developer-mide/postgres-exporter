# Postgres-Exporter with Prometheus and Grafana #
A Postgres Exporter, with Prometheus and Grafana for monitoring. 

## Table of Content ##
1. How to install
2. Configure Grafana
3. License

## How to Install ##

Run
    cd postgres && docker-compose up -d
The command above changes directory to postgres and fire up docker-container `(Make sure docker and docker-compose is installed)` 

Go to [http://localhost:3000](http://localhost:3000)
Prometheus will be available [http://localhost:9090](here)


## Configure Grafana ##

![alt text](./adding-prometheus.png)

Hover on **+** icon, click Import to add Grafana dashboard 


## License ##MIT License

Copyright (c) 2021 Ogunmola Samuel (Developer_mide)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE


