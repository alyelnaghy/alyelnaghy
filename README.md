# Ali Elnaghy

Senior Backend Engineer at Bab Rizq, working on **Operix**, a multi-tenant ERP / SaaS platform for e-commerce merchants (1,000+ active merchants, 30M+ orders processed).

I care most about correctness under concurrency: payments that can't be double-charged, stock that can't oversell, and messages that can't be sent twice.

### Stack

Node.js · NestJS · Express · TypeScript · MongoDB / Mongoose · Redis · Firestore · Google Cloud (Cloud Run, Cloud Tasks, Cloud Scheduler) · Docker · Jest

### Selected work on Operix

- Cut WhatsApp inbox search on the largest tenant from 4.9 s (scanning 450k messages) to 1 ms with a digit-suffix index.
- Found silent update loss in per-tenant dashboard rollups caused by Cloud Tasks name deduplication, and redesigned the pipeline to remove ~25k per-update Cloud Tasks a day.
- Wrote 229 Jest spec files (~2,800 test cases), including integration tests against an in-memory MongoDB.
- Most of my work is in orders, WhatsApp automation and inventory.

### How I work

Spec-first: requirements become a written spec before implementation, and I use Claude Code and Cursor for AI-assisted development.

Most of my code lives in private company repositories, so the contribution graph below is the best public view of my activity.

### Contact

[LinkedIn](https://www.linkedin.com/in/ali-elnaghy) · dev.alielnaghy@gmail.com
