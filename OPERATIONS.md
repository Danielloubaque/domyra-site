# DOMYRA / operation and recovery

Live: https://domyra.net.br/ (GitHub Pages com domínio personalizado via CNAME)

Static HTML on GitHub Pages. Source is index.html; no build dependencies. Preserve Pages configuration, CNAME (`domyra.net.br`), main branch and the existing phone +55 15 99189-7820 (different from Vyntriva). Services: residential electrical work and residential/industrial automation in Sorocaba/Votorantim.

Quote flow prepares a preview and opens WhatsApp for visitor confirmation; no backend delivery is configured. SEO metadata, sitemap and robots are tracked. Test on mobile before changing source. Rollback: restore the last tested commit; verify the Pages deployment rather than assuming a commit is published. Do not expose customer data or credentials.

2026-11-14: added a read-only public health monitor for the owner's five related public projects, every six hours, plus manual dispatch. Standard ubuntu-latest runner in this existing public repository; no secrets, paid runners, artifacts or catalog mutations. It checks HTTP status and public blog freshness >30h. Access denials and network failures are unverified, not proof of outage. Read logs and job summaries. The first run must be verified; configured schedules are not delivery proof.

Integrations: GitHub Pages, WhatsApp click-to-chat, Instagram external link. This repository does not run Shopee imports, Whapi sends or Blogger publishing. Git is the source backup. Native hosting/DNS access is needed for domain changes.
