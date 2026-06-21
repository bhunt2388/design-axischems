# Axis Chems Logistics — Design Hub

**Live:** https://design.axischemslogistics.com  
**Vercel:** https://design-axischems.vercel.app

## Brand Studios

| Brand | URL | Studio |
|---|---|---|
| Axis Chems | `/axis-chems` | `axis-chems.html` |
| Axiom Labz | `/axiom-labz` | `axiom-labz.html` |
| Emigenex | `/emigenex` | `emigenex.html` |
| Auro | `/auro` | `auro.html` |

## Update workflow

```bash
cd ~/Desktop/design-axischems
# edit any .html file
git add -A && git commit -m "Update [brand] studio" && git push
# Vercel auto-deploys in ~20s
```

## Custom domain

Add CNAME at your DNS registrar:
```
design -> cname.vercel-dns.com
```
Then in Vercel dashboard → project → Domains → add `design.axischemslogistics.com`
