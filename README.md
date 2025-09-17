# The Twelve-Factor App — short reflection

Link: https://12factor.net/

I find the "12-Factor App" principles interesting because they provide clear, practical guidelines for building modern web applications that are portable and maintainable. The ideas about strict separation of config from code, treating backing services (databases, caches, queues) as attached resources, and building stateless processes help make apps easier to deploy, scale, and debug.

Particularly useful is the focus on storing config in the environment (not in code) — that encourages safer deployments and fewer accidental secrets in version control. Overall, these patterns are compact but powerful guidelines for real-world engineering, especially in teams building microservices or cloud-native apps.

*Public note:* This repository is part of a course assignment and is public. Do not commit secrets (API keys, passwords, `.env` with credentials) to this repo.
