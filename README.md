# ΦίΛιΠs — Ψηφιακό Μενού

Αυτόνομη ιστοσελίδα (single-file). Το `index.html` περιέχει ενσωματωμένα όλα τα assets (εικόνες, γραμματοσειρές), οπότε δουλεύει και offline — δεν χρειάζεται build.

## Περιεχόμενα
- `index.html` — η ιστοσελίδα του μενού (splash + κατάλογος, GR/EN).
- `netlify.toml` — ρυθμίσεις για Netlify.
- `.gitignore`

## Ανέβασμα στο GitHub
```bash
cd filips-deploy
git init
git add .
git commit -m "ΦίΛιΠs digital menu"
git branch -M main
git remote add origin https://github.com/<χρήστης>/<repo>.git
git push -u origin main
```

## Deploy στο Netlify
**Επιλογή Α — από GitHub:** Netlify → *Add new site* → *Import an existing project* → διάλεξε το repo. Publish directory: `.` (root). Build command: κενό.

**Επιλογή Β — drag & drop:** Σύρε τον φάκελο `filips-deploy` στο [app.netlify.com/drop](https://app.netlify.com/drop).

Η σελίδα είναι έτοιμη στο `/`.
