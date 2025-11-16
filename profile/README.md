![image](https://github.com/user-attachments/assets/77f724d0-00e0-4441-a12e-c666dc2cae0c)

# Your entire stack, defined as code.

We provide all the tools, security, scaling and infrastructure you need to launch faster. Plus, it's all deployed and configured with code while staying type-safe.

Rebxd is a platform for building, connecting, and deploying complete applications. It bundles serverless functions, authentication, databases, storage, and frontend-friendly security into one unified system — and will be fully self-hostable.

Everything is configured and deployed through TypeScript inside your repository. Your infrastructure becomes code: deployments, permissions, database rules, authentication, environments, and how all services connect. Deploy it all with one command:

```sh
$ rxd deploy
```

Rebxd builds, links, and deploys your full stack automatically, similar to Vercel’s workflow but with deeper control, type safety, and full-stack configuration. TypeScript gives you autocomplete, validation, and end-to-end type inference across your services. Non-TypeScript projects are supported through generated code.

You can define how your services interconnect — for example, have your web app automatically receive `AUTH_TOKEN` from your auth deployment — and configure partial redeployments so only changed components update. All infrastructure is version-controlled and easily shareable; committing your `rebxd/` folder lets anyone self-host your stack with one command.

Rebxd merges the automation of Vercel, the flexibility of Terraform, and the type-safety of TypeScript into one platform.

### Are you ready? [Go Rebxd](https://rebxd.com).

> [!Note]
> Well, we aren't yet, but it's going to be available, very very soon.

---

### Why Rebxd?

**Unified**  
All essential backend and deployment services in one place: serverless functions, authentication, storage buckets, databases, and secure frontend-friendly policies.

**Infrastructure as TypeScript**  
Define your architecture inside your repo with full typing, autocomplete, validation, and consistent service-to-service connections.

**Automatic deployments**  
Rebxd handles build, linking, and deployment in one step. Push, run `rxd deploy`, and your entire stack updates.

**Self-hostable**  
Commit your `rebxd/` directory and anyone can bootstrap and self-host your full setup.

**Language-agnostic**  
TypeScript gets first-class inference and tooling; other languages work via generated clients, with expanded support planned.


---

### Roadmap (condensed)

- **Core platform**
  - Infrastructure-as-TypeScript
  - Full-stack linking (auth, DB, storage, serverless)
  - Partial deployments
  - Self-hosting

- **Services**
  - Authentication (oAuth2, organizations, integrations)
  - Serverless compute with autoscaling
  - Storage buckets with row-level security + CDN
  - Rebxd Database (post-launch)
  - Third-party integrations

- **Dashboard**
  - Overview, announcements, project management
  - Analytics, billing, tickets
  - Project listings + hub for community projects

- **AI / Automation**
  - Blitz Agent: zero-effort project bootstrapper  
  - Blitz-One: in-house model (WIP)

