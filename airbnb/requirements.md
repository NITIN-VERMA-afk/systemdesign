# functional requirements
 
1 . add or update there property

2 . view the bookings

3 . search properties

4 . book property

5 . view bookings


# non-functional requirements

1 . availability

2 . Scalability

3 . Moderate Latency

# capacity Estimation 

1 . DAU - 50 M


2 . MAU-100M

# throughputs

1 . write requests - 28,571 create request per day

2 . read requests - 326,667 booking request per day

# storage 

1 . 500kb*28571 r/d= 14.29 GB/day * 365* 10 years = 52.15T

2 . bookings -14.61 GB/day

# Memory 

1 . 0.73

# Network 

1 . INGRESS - 169.1 KB /second

2 . EGRESS - 14.7 tb/dat
