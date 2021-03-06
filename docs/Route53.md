# Route53

Route53 is a global service.

## Route53 Routing Policies.

### Simple

The default routing policy when a new record set is created (**Round Robin**).

### Weighted

Configure weighted traffic (20%-80%). It can be the same region but different load balancers. Suited for sending traffic to a new site (**testing puposes**).

### Latency

Allows you to route your traffic based on the lowest network latency for your user (i.e which region will give them the best fastest response).

### Failover

Failover routing policies are used when you want to create an active/passive setup. Route53 will monitor the health of your primary site using a health check.

### Geolocation

Geolocation routing lets you choose where your traffic will be sent based on the geographic location of your users (ie the location where the DNS quyries originated)

## Domain Names Limits

There is **50 Domain Names** soft limit by default. This can be raised by contacting [AWS support](http://aws.amazon.com/route53/faqs/).
