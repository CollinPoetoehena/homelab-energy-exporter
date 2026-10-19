# homelab-energy-exporter
A small Go service that reads an energy meter through a selected provider and exposes normalized readings in Prometheus text format. It is an independent project so provider adapters, container releases and tests can evolve separately from a particular homelab deployment

TODO: for homelab add this; short description: 	TODO: separate repository because it can be versioned independently that way and is open source for that reason, etc.
	TODO: can be piblic repo because it is just the container code, make it in Go (fastest, add with AI reasoning for that more) and state used in my homelab with a reference.
	TODO: design is simple: different meters IpT devices input data (the providers/plugins/whatever the best name is) and the output is a consistent format that is output and exported to the metrics collector for the energy dashboard, etc.
	TODO: that is a lot of fun to make and this way I can learn Go as well (Python I use at work a lot already and the goal here is fast to convert output, etc., and Go is better for that, etc.), etc. :)!

