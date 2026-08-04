---
title: "Build a Postgres Job Queue with SKIP LOCKED, No Redis"
url: "https://www.prisma.io/blog/you-dont-need-a-job-queue-postgres-already-has-skip-locked"
date: "2026-07-17"
feed_url: "https://www.prisma.io/blog/rss.xml"
---
Postgres can run a reliable background job queue with FOR UPDATE SKIP LOCKED. Build a worker queue with retries using pg and Prisma Postgres, no broker required.
