## Tracing with Envoy & Jaeger

Standalone example copied from envoy jaeger-tracing:
https://github.com/envoyproxy/envoy/tree/main/examples/jaeger-tracing

### Run:
1. `docker-compose build`
2. `docker-compose up -d`
3. Hit http://localhost:8000/trace/1 to generate some tracing data 
4. Visit http://localhost:16686 in your browser
