# ServiceNow Banking Portfolio

**Instance:** AU PDI | **Release:** Washington DC  
**Certs:** CSA · CIS-ITSM

---

## Project 1 — Banking Incident Management

**Scenario:** APAC Retail Bank managing IT incidents under APRA CPS 234 
regulatory obligations. P1 incidents affecting banking channels must be 
acknowledged within 15 minutes and escalated to the Major Incident team.

**Scoped app:** x_bank_incident  
**Table:** Banking Incident (extends Task) | Auto-number prefix: BAN

### Deliverables
- [x] Custom table extending Task with auto-numbering (BAN prefix)
- [x] Banking-specific fields: Regulatory Flag, Impacted Channel, Breach Type
- [x] Assignment rule: P1 → Major Incident team
- [x] SLA: 15-min response for P1 regulatory incidents
- [x] Executive dashboard

### Screenshots
<img width="1888" height="575" alt="image" src="https://github.com/user-attachments/assets/66e924f3-78e9-41a7-a9c0-be8527288b60" />
<img width="1902" height="447" alt="image" src="https://github.com/user-attachments/assets/2dbea3fe-bbc1-4d6d-8649-1b2951cfdded" />

<img width="1887" height="418" alt="image" src="https://github.com/user-attachments/assets/308d0182-efde-4b91-a530-318f9f098327" />
<img width="1902" height="900" alt="image" src="https://github.com/user-attachments/assets/f1d165b4-55b4-41cc-b6b7-aaf1d4dfff24" />



## Project 2 — Banking Complaint Management

**Scenario:** Three-tier customer complaint process based on real banking 
operations. Service complaints resolved same day, escalated complaints 
within 30-day IDR window, executive complaints with parallel HR workflow.

**Scoped app:** x_bank_complaint

### Deliverables
- [ ] Service Complaint table
- [ ] Escalated Complaint table  
- [ ] Executive Complaint table (with parallel HR task flow)
- [ ] Assignment rules (3 teams)
- [ ] 30-day IDR SLA
- [ ] Executive complaint dashboard




