# ChoirEdge — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Facility operator

- As a facility operator, I want on-prem action alerts (e.g., after-hours intrusion gestures) without video leaving the building, so that privacy review can approve the system.
- As a facility operator, I want a clear degraded-mode banner when too few devices are online, so that I know coverage is reduced.
- As a facility operator, I want alert clips stored locally with retention limits, so that investigations remain possible without permanent recording.

### Edge ML engineer

- As an ML engineer, I want to publish a model profile with partition hints, so that ChoirEdge can shard layers across heterogeneous Pis.
- As an ML engineer, I want runtime metrics per partition (latency, queue), so that I can find straggler layers.
- As an ML engineer, I want A/B comparison against a single TX2 baseline profile, so that sales engineering can quote performance honestly.

### Installer

- As an installer, I want to enroll cameras and collaborator nodes with QR/claim codes, so that setup does not require compiling DNN graphs by hand.
- As an installer, I want automatic rebalance after adding a node, so that capacity upgrades are plug-in.

### Privacy officer

- As a privacy officer, I want cryptographic membership attestation for choir nodes, so that a compromised laptop cannot join inference.
- As a privacy officer, I want a guarantee and test that raw frames are not egressing, so that we can sign off deployment.

### Platform administrator

- As a platform admin, I want fleet policy that pins model versions per site, so that a bad push can be frozen.
- As a platform admin, I want energy and FPS dashboards for procurement renewals, so that we can defend on-prem spend vs cloud vision.
