# arjunkanojia.com

Source for [arjunkanojia.com](https://arjunkanojia.com): the portfolio and weekly engineering blog of **Arjun Kanojia**, DevOps / Platform / SRE engineer (AWS · EKS/Kubernetes · Terraform · GitOps). AWS Certified Solutions Architect – Professional · CKA.

## What's here

| Path | What it is |
|---|---|
| `index.html` | Portfolio home page: experience, projects, skills, contact |
| `blog/` | Weekly posts on platform engineering, EKS operations, Terraform and SRE |
| `blog/feed.xml` | RSS feed |
| `sitemap.xml`, `robots.txt` | SEO |
| `resume.pdf` | Public resume (no phone number) |
| `vercel.json` | Redirects `*.vercel.app` to the custom domain |

## Blog posts

| Date | Post |
|---|---|
| 16 Nov 2026 | [EKS 1.34 end of standard support: a zero-downtime upgrade playbook](https://arjunkanojia.com/blog/eks-1-34-end-of-support-upgrade-playbook/) |
| 9 Nov 2026 | [MCP servers are supply chain: securing the agent tool layer on EKS](https://arjunkanojia.com/blog/mcp-server-security-supply-chain-eks/) |
| 2 Nov 2026 | [Serving LLMs on EKS after Kubernetes 1.37](https://arjunkanojia.com/blog/llm-inference-eks-kubernetes-1-37/) |
| 26 Oct 2026 | [From IDP to agentic developer platform](https://arjunkanojia.com/blog/agentic-developer-platform-golden-paths/) |
| 19 Oct 2026 | [AI SRE agents on call: an autonomy ladder for incident response](https://arjunkanojia.com/blog/ai-sre-agents-incident-response/) |
| 12 Oct 2026 | [Guardrails for AI agents writing Terraform](https://arjunkanojia.com/blog/ai-agents-terraform-guardrails/) |
| 8 Oct 2026 | [Surviving peak traffic on EKS](https://arjunkanojia.com/blog/peak-traffic-lessons-fifa-world-cup-2026/) |

## How it's built and deployed

- Plain static HTML and CSS: no framework, no build step, fast to load.
- Hosted on Vercel. Every push to `main` deploys to production; pull requests get preview URLs.
- Each new post = `blog/<slug>/index.html` + an entry in `blog/index.html`, `blog/feed.xml` and `sitemap.xml`.

## Contact

arjun.kanojia.in@gmail.com · [LinkedIn](https://www.linkedin.com/in/arjunkanojia) · Open to relocate: Singapore · Dubai · Netherlands
