# Serverless (serverless)
An index and topic collection covering serverless compute, function-as-a-service (FaaS) runtimes, and edge function platforms. Serverless platforms abstract away server management, scale on demand, and bill per invocation, letting developers ship event-driven functions, scheduled jobs, durable workflows, and HTTP endpoints without provisioning infrastructure. This collection includes hyperscaler functions like AWS Lambda, Azure Functions, and Google Cloud Functions; edge runtimes like Cloudflare Workers, Vercel Edge Functions, Fastly Compute@Edge, and Deno Deploy; container-based serverless like Google Cloud Run and AWS App Runner; WebAssembly-first platforms like Fermyon Spin and wasmCloud; durable workflow services like AWS Step Functions, Inngest, and Trigger.dev; and BaaS function runtimes like Supabase Functions, Firebase Functions, and Convex.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Serverless, Functions as a Service, Edge Functions, Cold Start, WebAssembly, FaaS, Durable Workflows

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Function Schema](https://raw.githubusercontent.com/api-evangelist/serverless/refs/heads/main/json-schema/serverless-function-schema.json)
- [JSONSchema - Invocation Schema](https://raw.githubusercontent.com/api-evangelist/serverless/refs/heads/main/json-schema/serverless-invocation-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/serverless/refs/heads/main/json-ld/serverless-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/serverless/refs/heads/main/vocabulary/serverless-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Function-as-a-Service Runtimes | Serverless platforms execute short-lived, stateless functions in managed runtimes that automatically scale from zero to many instances based on incoming requests or events. |
| Event-Driven Invocation | Functions are triggered by HTTP requests, queue messages, object storage events, scheduled cron jobs, database changes, and pub/sub topics without dedicated listeners. |
| Edge Function Distribution | Edge runtimes like Cloudflare Workers, Vercel Edge Functions, and Fastly Compute@Edge execute code in points of presence physically close to end users, reducing latency. |
| Cold Start and Snapshot Optimization | Platforms reduce cold start latency through V8 isolates, Firecracker microVMs, AWS Lambda SnapStart, and WebAssembly-based instant startup runtimes. |
| Durable Workflows and Orchestration | Services like AWS Step Functions, Inngest, and Trigger.dev provide durable execution, retries, sleeps, and long-running workflows on top of serverless functions. |
| Pay-per-Invocation Billing | Costs scale linearly with usage, billed per invocation and gigabyte-second of compute time, with generous free tiers that absorb most low-traffic workloads. |
| WebAssembly Serverless | Platforms like Fermyon Spin, wasmCloud, and Fastly Compute@Edge run WebAssembly modules with sub-millisecond startup, strong sandboxing, and polyglot language support. |
| Function URLs and HTTP Endpoints | Direct HTTPS endpoints for functions (Lambda Function URLs, Cloud Run, Workers routes) eliminate the need for a separate API gateway for simple HTTP services. |

## Use Cases

| Name | Description |
|------|-------------|
| API Backends and Microservices | Serverless functions back HTTP APIs and microservices, scaling to zero during idle periods and absorbing traffic spikes without capacity planning. |
| Webhook Receivers and Integrations | Functions process incoming webhooks from SaaS platforms, validate signatures, transform payloads, and fan out to downstream systems. |
| Scheduled and Cron Jobs | Platforms like Vercel Cron, Cloudflare Cron Triggers, and EventBridge schedule functions to run on a cadence for batch jobs, cleanups, and periodic syncs. |
| Image and Media Processing | Functions resize, transcode, or watermark uploaded media in response to object storage events, often paired with edge caching for delivery. |
| Real-Time Edge Personalization | Edge functions rewrite responses, inject A/B test variants, geolocate visitors, and personalize HTML at the CDN edge with single-digit-millisecond overhead. |
| AI Inference and Agent Tools | Serverless GPU platforms like Modal and Cloud Run run AI model inference on demand; functions also serve as tool endpoints for LLM agents. |
| Durable Long-Running Workflows | Step Functions, Inngest, and Trigger.dev orchestrate multi-step business processes with retries, human-in-the-loop steps, and durable timers across hours or days. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | The original FaaS platform with first-class integrations into 200+ AWS services, Function URLs, SnapStart, and container image support. |
| Cloudflare Workers | V8-isolate edge runtime executing JavaScript and WebAssembly in 300+ points of presence with sub-millisecond cold starts. |
| Google Cloud Run | Container-based serverless platform that scales any HTTP container from zero, with both fully managed and Kubernetes-backed deployment modes. |
| Vercel Functions | Edge and Node.js serverless functions tightly integrated with the Vercel frontend platform, Next.js, and ISR. |
| Modal | Python-first serverless platform for AI inference, batch jobs, and long-running GPU workloads with code-defined infrastructure. |
| Inngest | Durable execution and event-driven workflow platform built on top of serverless functions across cloud providers. |
| Fermyon Spin | WebAssembly-native serverless runtime supporting polyglot Spin apps deployed to Fermyon Cloud or self-hosted clusters. |
| Supabase Functions | Deno-based edge functions colocated with Supabase Postgres, Auth, and Storage for backend-as-a-service workloads. |

## Artifacts

Machine-readable specifications for serverless functions, invocations, and runtime artifacts.

### JSON Schema

- [Function Schema](json-schema/serverless-function-schema.json)
- [Invocation Schema](json-schema/serverless-invocation-schema.json)

### JSON Structure

- [Function Structure](json-structure/serverless-function-structure.json)
- [Invocation Structure](json-structure/serverless-invocation-structure.json)

### JSON-LD

- [Serverless Context](json-ld/serverless-context.jsonld)

## Vocabulary

- [Serverless Vocabulary](vocabulary/serverless-vocabulary.yaml) — Unified taxonomy mapping serverless resources, actions, workflows, and personas across FaaS, edge runtimes, and durable workflow platforms

## Network

This index references the following serverless and edge function platform repositories:

- [Apache OpenWhisk](https://github.com/api-evangelist/apache-openwhisk)
- [Auth0](https://github.com/api-evangelist/auth0)
- [AWS App Runner](https://github.com/api-evangelist/aws-app-runner)
- [AWS Lambda](https://github.com/api-evangelist/aws-lambda)
- [AWS Step Functions](https://github.com/api-evangelist/aws-step-functions)
- [Azure Functions](https://github.com/api-evangelist/azure-functions)
- [Cloudflare](https://github.com/api-evangelist/cloudflare)
- [Convex](https://github.com/api-evangelist/convex)
- [Defer](https://github.com/api-evangelist/defer)
- [Deno](https://github.com/api-evangelist/deno)
- [Fastly](https://github.com/api-evangelist/fastly)
- [Fermyon](https://github.com/api-evangelist/fermyon)
- [Google Cloud Functions](https://github.com/api-evangelist/google-cloud-functions)
- [Google Cloud Run](https://github.com/api-evangelist/google-cloud-run)
- [Google Firebase](https://github.com/api-evangelist/google-firebase)
- [Inngest](https://github.com/api-evangelist/inngest)
- [Knative](https://github.com/api-evangelist/knative)
- [Koyeb](https://github.com/api-evangelist/koyeb)
- [Microsoft Azure Functions](https://github.com/api-evangelist/microsoft-azure-functions)
- [Modal](https://github.com/api-evangelist/modal)
- [Netlify](https://github.com/api-evangelist/netlify)
- [Quirrel](https://github.com/api-evangelist/quirrel)
- [Scaleway](https://github.com/api-evangelist/scaleway)
- [Serverless Patterns](https://github.com/api-evangelist/serverless-patterns)
- [Serverless Workflow](https://github.com/api-evangelist/serverless-workflow)
- [Spin](https://github.com/api-evangelist/spin)
- [Supabase](https://github.com/api-evangelist/supabase)
- [Trigger.dev](https://github.com/api-evangelist/trigger-dev)
- [Twilio](https://github.com/api-evangelist/twilio)
- [Vercel](https://github.com/api-evangelist/vercel)
- [wasmCloud](https://github.com/api-evangelist/wasmcloud)
- [WasmEdge](https://github.com/api-evangelist/wasmedge)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
