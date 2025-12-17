This report documents in-depth testing performed on the Octra public testnet, focusing on the OCS01 benchmark contract under both regular and encrypted sequential execution modes. The objective is to validate execution stability, establish baseline performance metrics, and provide verifiable artifacts suitable for QA review and ecosystem evaluation.

Contributor Information

Octra address: octGTW2A7kvKDharykCzce8fJSktvXavrBhMZKfqtLPJQQ3

Testing Scope

Network: Octra Public Testnet

Contract: OCS01

Execution modes tested:

Regular (sequential)

Encrypted (sequential)

Client/contract modifications: None

Methodology

Benchmarks executed using the official OCS01 tooling.

Transactions were submitted sequentially to observe end-to-end execution behavior.

Metrics collected per run:

Total transactions processed

Total execution duration

SHA-256 checksum of raw log output for integrity verification

Benchmark Results
OCS01 Regular Benchmark

Total transactions: 110

Total duration: 952 seconds

Derived TPS: 0.1155

SHA-256 (log): e04220307b27845334d128a24072547ca87ea4d9735b6258cd60cffca90a6c42

OCS01 Encrypted Sequential Benchmark

Start time: 2025-11-24T11:22:51Z

Total transactions: 20

Total duration: 1303 seconds

Derived TPS: 0.0153

SHA-256 (log): 279ffa3e96a87f0686e5daef8a8dba6ebed28c257546b128880b1fe8c6810da9
