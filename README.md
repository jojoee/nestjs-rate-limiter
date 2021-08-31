# nestjs-rate-limiter

[Rate Limiter Module for NestJS](https://github.com/ozkanonur/nestjs-rate-limiter) with modifications
- add `enable` flag option to enable or disable the feature
- apply rate limit on only GraphQL request and disable to other types of request
- using IP from `request.ip` or `request.headers['X-Forwarded-For']`
- not support `Fastify` platform
