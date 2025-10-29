# Kaspa Mining Rigs – Continuous Operation SOP (KS5L & KS5 Pro)

This SOP outlines best practices for maintaining stable, efficient, and resilient 24/7 operation of IceRiver KS5L and Bitmain KS5 Pro Kaspa miners. It includes monitoring routines, environmental checks, and reliability tracking.

---

## 1. Daily Monitoring Checklist

- Check dashboard for:
  - Hash rate stability (±5% of target)
  - Fan RPM within normal range
  - PSU voltage and temperature
  - Pool connectivity and accepted shares
- Review LED indicators:
  - KS5L: L2 blinking = active mining
  - KS5 Pro: dashboard reachable, fans spinning

---

## 2. Environmental Controls

- Maintain ambient temperature below 35°C  
- Ensure airflow is unobstructed (intake and exhaust)  
- Clean filters or intake mesh weekly  
- Use external sensors if available to monitor rack temperature and humidity

---

## 3. Maintenance Rotation

- Schedule visual inspection every 72 hours  
- Rotate rigs for deep cleaning every 2–4 weeks  
- Check PSU connectors for heat discoloration or wear  
- Verify PDU outlet mapping and switch integrity

---

## 4. Reliability Tracking

- Log uptime per rig weekly  
- Record any hash rate dips, reboots, or pool disconnects  
- Update MTTR/MTBF metrics monthly in `reliability-metrics.md`  
- Tag anomalies with timestamp and rig ID

---

## 5. Chip Temperature Monitoring

- Use open-source tools or miner dashboard to manually check chip-level temperatures  
- If supported, query chip temps via API or local interface  
- Log readings periodically to detect thermal drift  
- Recommended threshold: investigate if chip temp exceeds 85°C  
- Alerts are not supported in this setup — rely on manual review or scheduled checks

---

## 6. Firmware & Pool Updates

- Check for firmware releases weekly  
- Apply updates only during scheduled maintenance windows  
- Validate pool performance monthly; switch pools if latency or rejected shares exceed thresholds

---

## 7. Operational Notes

- Avoid frequent power cycling — use pool disable if temporary pause is needed  
- Label all rigs and PDU outlets clearly  
- Maintain backup pool config and wallet addresses offline
