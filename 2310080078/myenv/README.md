# myenv

This project keeps environment configuration out of Git.

## Backend
Create a file:

- `backend/.env`

Required keys (update values locally):
- `MONGODB_URI`
- `PORT`
- `GOOGLE_CLIENT_ID`
- `GOOGLE_CLIENT_SECRET`
- `JWT_SECRET`

## Frontend
If your Vite build needs frontend env vars, create:

- `frontend/.env`

(You can commit it if you want, but do not include secrets.)

## Templates
See:
- `backend.env.example`

## Notes
- Never commit real secrets.
- `.gitignore` is set up to ignore `backend/.env` while still allowing `frontend/.env`.

