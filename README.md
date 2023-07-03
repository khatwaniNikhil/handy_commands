### HTTP API Latency  - Load Test using vegeta (https://github.com/tsenart/vegeta)
echo "GET http://<application_url>/" | vegeta attack -duration=120s | tee results.bin | vegeta report
