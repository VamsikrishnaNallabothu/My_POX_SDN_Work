SDN Load balancer


For Round Robin:
Run it with --ip=<load_balancer ip> --servers= IP1,IP2,IP3,... [--dpid=<dpid>]
For Weighted Round Robin: Give weights as 1,2,..(weights are seperated from IP by using ':')
Run it with --ip=<load_balancer ip> --servers= IP1:weight,IP2:weight,IP3:weight,... [--dpid=<dpid>]
