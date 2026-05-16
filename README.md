<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║    $ git log --author="Himanshu Singh" --oneline --graph --all       ║
║                                                                      ║
║    * 🟢  himanshu@dev  ~  Software Developer                         ║
║    * 📍  Noida, India                                                ║
║    * ⚡  Backend systems that scale to 10,000,000 users              ║
║    * ☕  Coffee: CRITICAL_DEPENDENCY (do not remove)                 ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=14&pause=1200&color=00f5d4&center=true&vCenter=true&width=750&height=36&lines=%24+git+commit+-m+%22feat%3A+system+that+survives+10M+concurrent+users%22;%24+kubectl+rollout+status+deploy%2Fprod+--watch+%E2%9C%93+success;%24+redis-cli+info+stats+%7C+grep+keyspace_hits+%23+ratio%3A+99.8%25;%24+kafka-consumer-groups+--describe+%7C+grep+LAG+%230;%24+docker+stats+--no-stream+%7C+awk+%27NR%3E1%7Bprint+%241%2C+%243%7D%27;%24+EXPLAIN+ANALYZE+SELECT+...+%23+Index+Scan+0.08ms+%E2%9C%93" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-singh-4339b02a5/)
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Himanshu48415)
[![LeetCode](https://img.shields.io/badge/LeetCode-ffa116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/himanshu152002/)
[![Gmail](https://img.shields.io/badge/Gmail-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:himanshusingh48415@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=Himanshu48415&color=00f5d4&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Himanshu48415)

</div>

---

## `$ gh api /users/Himanshu48415 | jq .`

```json
{
  "name"        : "Himanshu Singh",
  "title"       : "Software Developer — I don't ship features. I ship systems.",
  "location"    : "Noida, India 🇮🇳",
  "hireable"    : true,
  "stack"       : ["Node.js", "NestJS", "Go", "Kafka", "Redis", "PostgreSQL", "K8s"],
  "obsession"   : "What breaks when 10,000,000 users hit this at once?",
  "philosophy"  : "p99 latency > average latency. Every. Single. Time.",
  "status"      : "🟢 Open to Opportunities — response time < 1ms"
}
```

---

## `$ git log --oneline --graph --decorate --all`

```
*   a4f91c2  (HEAD → main, origin/main, origin/HEAD)
|\           feat: zero-downtime deploy — K8s rolling update + readiness probes
| * e83bc71  (origin/perf/latency-tuning)
|/           perf: p99 latency ↓40% — Redis pipeline batching + connection pool tuning
*   9d2a44f  feat: idempotent Kafka consumer — exactly-once semantics, offset post-commit
*   c71f830  fix: RabbitMQ backpressure — prefetch=1, manual ack, DLX wired correctly
|\
| * 3b9e120  (origin/refactor/grpc-migration)
|/           refactor: REST → gRPC internal services — 30% latency drop, protobuf typed
| * 77a1d09  (origin/feature/rate-limiter)
|/           feat: distributed rate limiter — Redis sliding window, atomic EVAL script
*   f44c201  feat: JWT rotation — refresh token reuse detection + silent revocation
*   2e9b881  feat: WebSocket @ scale — Redis pub/sub adapter, dropped sticky sessions
*   d10aa93  perf: DB query ↓60% — covering indexes + EXPLAIN ANALYZE driven
*   88f2c4d  chore: Docker multi-stage build — image 1.2GB → 180MB (85% smaller)
*   3c22b10  feat: event sourcing — append-only log, CQRS projections rebuilt on replay
|\
| * b77f120  (tag: v1.0.0)
|/           🚀 initial commit — backend architecture laid, let's scale this thing
```

---

## `$ git diff average-dev..himanshu -- mindset.md`

```diff
@@ -0,0 +1,16 @@

-  average dev: "does it work?"
+  himanshu:    "what happens at 10M concurrent requests?"

-  "throw more RAM at it"
+  stateless services, shared-nothing — horizontal scale from day 0

-  UPDATE users SET balance = balance + 100 WHERE id = ?
+  event sourcing + CQRS — the log is truth, state is just a projection

-  retry && hope(true)
+  idempotency keys — every retry is a safe, silent no-op

-  console.log("server is running")
+  p99, p95, error_rate, queue_depth, cache_hit_ratio — all tracked, always

-  kill -9 $(lsof -t -i:3000)
+  graceful shutdown — drain in-flight requests, close pool, exit 0

-  "maintenance window @ 3am, sorry"
+  zero-downtime deploy — readiness probe blocks traffic until warm

-  "works on my machine 🤷"
+  Dockerized, 12-factor, reproducible across every environment
```

---

## `$ ls -la ./tech-stack/`

<div align="center">

## ⚡ Tech Stack

### Backend
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-444444?style=flat-square&logo=express&logoColor=white"/>
</p>

### Databases
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</p>

### Messaging & Realtime
<p>
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white"/>
  <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
</p>

### DevOps & Infra
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white"/>
</p>

### Frontend (when forced)
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
</p>

</div>

---

## `$ git stash list  # branches WIP — coming to main soon`

```
stash@{0}: WIP on learning/kafka-streams-advanced
           → partitioning strategy, consumer group lag monitoring, stream processing

stash@{1}: WIP on learning/kubernetes-operators
           → custom CRDs, controllers, HPA + VPA tuning, pod disruption budgets

stash@{2}: WIP on learning/golang-concurrency-patterns
           → goroutines, channels, select, sync.Pool, context propagation

stash@{3}: WIP on learning/aws-solutions-architect
           → VPC design, ECS Fargate, RDS Multi-AZ, CloudFront, Route53

stash@{4}: WIP on learning/system-design-at-scale
           → consistent hashing, CAP theorem, saga pattern, CQRS in production
```

---

## `$ git blame --date=relative THINGS_I_OBSESS_OVER.md`

```
a4f91c2 (Himanshu  2 hrs ago )   p99 latency       — not avg; every percentile is a user's experience
e83bc71 (Himanshu  1 day ago )   backpressure      — an unbounded queue is a system waiting to die
9d2a44f (Himanshu  3 days ago)   cache hit ratio   — every cache miss is a hidden DB tax
c71f830 (Himanshu  1 wk ago  )   idempotency       — if retries aren't safe, it's not production-ready
3b9e120 (Himanshu  2 wks ago )   graceful shutdown — kill -9 is not a deploy strategy
77a1d09 (Himanshu  1 mo ago  )   zero-downtime     — your CI/CD is your users' problem if you're noisy
f44c201 (Himanshu  2 mos ago )   event sourcing    — state is a lie; the log is the only truth
2e9b881 (Himanshu  3 mos ago )   distributed trace — trace_id in every log, every service, always
```

---

## `$ gh run list --workflow="daily-grind.yml" --status=success`

<div align="center">

<img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=Himanshu48415&theme=tokyonight&hide_border=true&background=0d1117&ring=00f5d4&fire=7b2fff&currStreakLabel=00f5d4&sideLabels=00f5d4&dates=888888&border_radius=6"/>

</div>



</div>

---

## `$ git log --since="1 year ago" --format="%cd" --date=short | sort | uniq -c`

<div align="center">

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Himanshu48415&bg_color=0d1117&color=00f5d4&line=7b2fff&point=ffffff&area=true&hide_border=true&area_color=0a0a2e&custom_title=commit+frequency+—+the+grind+never+stops"/>

</div>

---

## `$ git shortlog -sn --no-merges | head -1  # the numbers`

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=Himanshu48415&theme=darkhub&no-frame=true&margin-w=10&column=7&title=Stars,Followers,Commits,Repositories,PullRequest,Issues,Reviews)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## `$ gh issue create --title "hire-himanshu" --label "priority:critical"`

```
✓  Created issue #1 in Himanshu48415/open-to-work

   Title      :  Let's build something that doesn't fall over at scale
   Assignee   :  @Himanshu48415
   Labels     :  priority:critical · type:opportunity · status:open
   Ping       :  < 1ms    (0% packet loss)
   Uptime     :  99.99%   (coffee daemon: always running)
   Auto-merge :  enabled  — ready to ship ⚡
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/gh_connect_——_LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-singh-4339b02a5/)
[![Gmail](https://img.shields.io/badge/gh_message_——_Gmail-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:himanshusingh48415@gmail.com)
[![LeetCode](https://img.shields.io/badge/gh_solve_——_LeetCode-ffa116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/himanshu152002/)

</div>

<br/>

<div align="center">

```
"Most devs think about features.
 I think about what happens when 10 million people hit it at once."
                                              — Himanshu Singh
```

</div>
