# Destination Rule

A DestinationRule configures the set of policies to be applied to a request after VirtualService routing has occurred. They are intended to be authored by service owners, describing the circuit breakers, load balancer settings, TLS settings, and other settings.

A DestinationRule also defines addressable subsets, meaning named versions, of the corresponding destination host. These subsets are used in VirtualService route specifications when sending traffic to specific versions of the service.