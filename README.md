# My Scuffed Personal Website

### Start command
```bash
docker run -v /mnt:/app/files --env-file ./.env -p 3000:3000 <name>
```
### .env file
```env
TOKEN=""
USERID=""
AUTH_SECRET=""
AUTH_GOOGLE_ID=""
AUTH_GOOGLE_SECRET=""
NEXTAUTH_URL=""
DATABASE_URL=""
```