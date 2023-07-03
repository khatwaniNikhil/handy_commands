### HTTP API Latency Load test - vegeta (https://github.com/tsenart/vegeta)
1. echo "GET http://<application_url>/" | vegeta attack -duration=120s | tee results.bin | vegeta report
