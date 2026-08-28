# Arogya Link — Frontend

Two independent React + Vite applications:

- `apps/patient-kiosk` — touch-first patient/caregiver intake
- `apps/doctor-dashboard` — clinical review and escalation workspace

## Run

```bash
npm install
npm run dev:kiosk
npm run dev:doctor
```

The frontend currently uses a mock API layer so the SIH demo can be developed independently.
Replace service implementations with FastAPI calls phase-by-phase.
