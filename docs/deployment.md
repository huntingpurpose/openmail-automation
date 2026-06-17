# OpenMail Automation - Deployment Guide

## Local Development
See README.md

## Docker Deployment
```bash
docker-compose up -d
```

## Vercel + Neon + Upstash (Recommended Free)
1. Deploy frontend to Vercel
2. Use Neon for Postgres
3. Upstash for Redis
4. Set all env vars in Vercel dashboard

## Production Checklist
- [ ] HTTPS enabled
- [ ] Secrets configured
- [ ] Database migrations run
- [ ] Redis connected
- [ ] Rate limiting active
- [ ] Monitoring (Sentry) configured

Full details in this document.