1.Create VPC(10.100.0.0/16)
2.IGW(Attach to VPC )
3.subnets(public(10.100.0.0/24)) change the settings of (enable auto-assign public ipv4 address)
routetables(routes->local,IGW(0.0.0.0/0))
subnet associations ->attach public subnet
we can see the traffic in subnets
=>VPC->IGW->Subnets->RouteTables
  
=========>
plan -> check for the current state of real world objects
apply-> create,modify,or delete real world objects
destroy->delete real world objects