# ninja-emr (emr.enhancedops.ninja)

Fork of HospitalRun — the leading open-source TypeScript/React EMR frontend.
Source: https://github.com/HospitalRun/hospitalrun-frontend (★6,890)

## Stack
- React + TypeScript (Create React App)
- Redux for state
- Semantic UI React for components
- PouchDB (local) + CouchDB (remote) for data storage

## Deploy
- Vercel, custom domain: emr.enhancedops.ninja
- Build: npm run build → /build
- All routes rewrite to index.html (SPA)

## Local dev
npm install && npm start

## Working on it
- Customize branding in src/shared/components/
- Patient data model in src/patients/
- Appointments in src/scheduling/
- Lab/imaging in src/labs/ and src/imagings/
- Medications in src/medications/
- To swap in a real backend: replace PouchDB config in src/shared/db/
