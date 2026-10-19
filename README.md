# homelab-energy-exporter
A small Go service that reads an energy meter through a selected provider and exposes normalized readings in Prometheus text format. It is an independent project so provider adapters, container releases and tests can evolve separately from a particular homelab deployment
