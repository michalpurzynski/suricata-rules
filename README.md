# suricata-rules
Example Suricata rules implementing some of my detection tactics  

backdoors.rules - rules detecting questionable software  
pass.rules - prevent some types of traffic from being inspected. Useful to combat false-positives from sites like Windows Update  
plaintext.rules - detect files that should never be seen on the wire  
suspicious.rules - detect suspicious traffic (like TOR from a data center)
traffic_anomalies.rules - detect non-proto X on port X, detect proto X on non-port X - i.e. what is TLS doing on port 445 and why do I see HTTP (not S) on port 443?
