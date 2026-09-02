# Data Leakage Investigation

## Scenario

Analyze a controlled NIST CFReDS insider-threat dataset to determine how information moved across a workstation, removable media, and online services.

## Methodology

1. Recorded evidence identifiers and verified image integrity with cryptographic hashes.
2. Examined filesystem and operating-system artifacts associated with user activity.
3. Reviewed removable-media, email, browser, and cloud-service indicators.
4. Recovered deleted content where supported by the available evidence.
5. Correlated timestamps and artifacts into an evidence-backed sequence of events.

Conclusions were tied to specific artifacts and separated from assumptions. Conflicting timestamps and incomplete evidence were documented as limitations.

## Skills demonstrated

- Chain-of-custody awareness and hash verification
- Windows artifact and removable-media analysis
- Deleted-file recovery and timeline reconstruction
- Clear reporting of evidence, inference, and limitations
