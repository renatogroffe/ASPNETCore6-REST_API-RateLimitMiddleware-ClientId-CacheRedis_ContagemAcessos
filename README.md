# ASPNETCore6-REST_API-RateLimitMiddleware-ClientId-CacheRedis_ContagemAcessos
Exemplo de API REST para contagem de acessos criada com .NET 6 + ASP.NET Core e que faz uso do projeto AspNetCoreRateLimit + cache distribuído com Redis para testes de Rate Limit (com um Header de Subscription/Client Id). Inclui um Worker Service que consome a API e implementa o pattern Fallback com Polly para tratamento de falhas.
