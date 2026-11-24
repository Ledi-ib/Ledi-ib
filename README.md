### Ledian Ibishi

Software engineer in North Macedonia. I design and build complex systems for hard problems: scheduling, concurrency, authentication, money, and the APIs that web and mobile apps run on. I'm building a software agency for SaaS products and take on custom software projects.

**Appointo** is my own product: online booking for salons, barbershops and studios, live on the [web](https://appointo.org), the [App Store](https://apps.apple.com/app/id6762561374) and [Google Play](https://play.google.com/store/apps/details?id=com.appointo.app). I built it alone: a Fastify and PostgreSQL API, a React web app and an Expo app, sharing one TypeScript package. The code is private; how the hard parts work is public:

- [No double bookings](https://ledianibishi.com/work/appointo#double-bookings): a PostgreSQL exclusion constraint lets exactly one of two simultaneous bookings through.
- [Planning a multi-service visit](https://ledianibishi.com/work/appointo#visit-planner): a budgeted search across staff, checked by an independently written validator on 5,000 random days.
- [Sessions and two-factor](https://ledianibishi.com/work/appointo#sessions): revocable device sessions replacing seven-day JWTs, without signing anyone out.
- [Changing the schema under a live app](https://ledianibishi.com/work/appointo#schema-migration): expand-only migrations and a v2 API beside v1.

Since 2024 I've also built backend features in C#, ASP.NET Core and SQL Server for a commercial point-of-sale product: fiscal reporting, a QR menu service, and a landed-cost engine that always sums to the cent.

**Stack I use most:** TypeScript · Node.js · Fastify · PostgreSQL · Prisma · React · React Native (Expo) · C# · ASP.NET Core · SQL Server · Vitest · GitHub Actions

[Start a project](https://ledianibishi.com/#contact) · [ledianibishi.com](https://ledianibishi.com) · [LinkedIn](https://www.linkedin.com/in/ledian-ibishi/)
