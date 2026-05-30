# robimytech-landing

Static landing prototype for RobimyTech — invite-only circle of tech creators.

## Deploy

Cloudflare Pages, build settings:
- Framework: None
- Build command: (empty)
- Build output: `/`

Custom domain: `robimytech.pl` (DNS at OVH, point CNAME or change nameservers to CF).

Apply form currently uses `mailto:` to `pz@xfaang.com` + `cc=xf@xfaang.com`. Plan: replace with Cloudflare Pages Function once we have Resend / Mailgun key.

## Local

```
python3 -m http.server 8080
open http://localhost:8080
```
