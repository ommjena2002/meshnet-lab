# Tests

A collection of test scenarios. Execute `run.py` as user root in the sub folders to run the tests. The tests all expect the routing protocols to be installed. Otherwise modifiy the scripts. Be aware that the general execution time can take from 5 minutes up to some hours.

The tests will create a bunch of `*.csv` files with comma separated values. Use `./plot.sh` to create image graphs. You will need the `gnuplot` program installed for that.

## Benchmark1 Test

The mesh routing programs batman-adv and babel are used to estimate the amount of nodes the host system can simulate.
A good starting point to see to what number of nodes to limit the other tests. Otherwise the system performance will dictate the results.

[Go to Test](benchmark1/)

## Connectivity1 Test

This test does not run no network or any routing protocol. It runs a theoretical setup to create data.

[Go to Test](connectivity1/)

## Convergence1 Test

Test how long it takes for a routing daemon to route after start.

[Go to Test](convergence1/)

## Gateways1 Test

Assume that there is a small count of gateways/sinks in the network that many nodes want to use. Measures the traffic (overhead). 

[Go to Test](convergence1/)

## Mobility1 Test

Ping random nodes while they all move around randomly at fixed speed and form new connections. Data for animations of node movements is also generated.

[Go to Test](mobility1/)

## Mobility2 Test

Similar to Mobility1, but the nodes move around at increasing speeds.

[Go to Test](mobility2/)

## Freifunk Test

Test on topologies from the Freifunk data set with cable and WiFi connections. Measure connectivity and traffic.

[Go to Test](freifunk1/)

## Satellites1 Test

Test connectivity on a simple satellite network.

[Go to Test](satellites1/)

## Satellites2 Test

Test connectivity and traffic on a more complex satellite network.

[Go to Test](satellites2/)

## Satellites3 Test

A more realistic test with packet loss and transmission delay.

[Go to Test](satellites3/)

## Scalability1 Test

Get the traffic per link that a routing protocol generates under minimal load on different network sizes and topologies.

[Go to Test](scalability1/)

## Scalability2 Test

Send a ping from each node towards a single sink and measure traffic.

[Go to Test](scalability2/)

## Scalability3 Test

Send a ping from a single sink node towards each other node and measure traffic.

[Go to Test](scalability3/)
