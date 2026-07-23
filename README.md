<img src="https://capsule-render.vercel.app/api?type=blur&color=0:0d1117,100:161b22&height=180&section=header&text=darshtank.in&fontSize=42&fontColor=39d353&fontAlignY=45&desc=full-stack%20%2B%20cloud%20systems%20developer&descAlignY=65&descSize=16&descColor=8b949e&animation=fadeIn" width="100%"/>

<br>

```bash
$ whoami
```

```ini
name        = "Darsh Tank"
role        = "Full-Stack & Cloud Systems Developer"
status      = "4th year, Computer Science @ Nirma University"
domain      = "darshtank.in"
focus       = ["distributed systems", "cloud infra", "developer tools"]
philosophy  = "ship it, then make it not break"
```

<br>

```bash
$ terraform plan
```

> Provisioning 3 resources. No resources destroyed.

```hcl
resource "project" "veil" {
  alias        = "Veil"
  description  = "Anonymous messaging platform - auth, per-user inboxes, and email delivery on top of a clean Next.js frontend."
  stack        = ["Next.js", "TypeScript", "MongoDB", "Resend API"]

  source       = "https://github.com/DarshTank/Veil-Message"
  live         = ""   # <- add live link
}

resource "project" "writeverse" {
  alias        = "WriteVerse"
  description  = "A Django blogging platform - content management, templating, and deployment handled end to end."
  stack        = ["Django", "Python", "SQLite"]

  source       = "https://github.com/DarshTank/django-blog"
  live         = ""   # <- add live link
}

resource "project" "draftai" {
  alias        = "DraftAI"
  description  = "AI-assisted email writer shipped as a browser extension, backed by a Spring Boot service and React UI."
  stack        = ["Spring Boot", "React", "Chrome Extension"]

  source       = "https://github.com/DarshTank/draft-ai"
  live         = ""   # <- add live link
}
```

```bash
Apply complete! Resources: 3 added, 0 changed, 0 destroyed.
```

<br>

```bash
$ cat ~/.stack
```

```yaml
languages:      [Python, TypeScript, JavaScript]
frontend:       [React, Next.js, TanStack Start, Tailwind CSS, Alpine.js]
backend:        [Node.js, Django, Spring Boot, Frappe/ERPNext]
cloud:          [GCP, AWS, DigitalOcean, CloudStack, Virtuozzo]
databases:      [MongoDB, PostgreSQL, SQLite]
```

<br>

```bash
$ curl -I darshtank.in
```

```
HTTP/1.1 200 OK
status: online
domain: darshtank.in
```

<div align="center">

**[darshtank.in](https://darshtank.in)**

</div>

<img src="https://capsule-render.vercel.app/api?type=blur&color=0:161b22,100:0d1117&height=100&section=footer" width="100%"/>
