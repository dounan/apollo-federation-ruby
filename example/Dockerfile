FROM envoyproxy/envoy:v1.12.2
COPY envoy.yaml /etc/envoy/envoy.yaml
COPY gen/proto.pb /tmp/envoy/proto.pb

# docker build -t apollo-federation-ruby-envoy:latest .
# docker run -p 50011:50011 -p 9901:9901 apollo-federation-ruby-envoy