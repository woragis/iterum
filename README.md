# Iterum

Empresa — CRM, API e landing page.

## Estrutura

| Pasta no root | Repo GitHub | Papel |
|---------------|-------------|-------|
| `frontend/` | [iterum-crm](https://github.com/woragis/iterum-crm) | CRM (Next.js) |
| `backend/` | [iterum-api-next](https://github.com/woragis/iterum-api-next) | API Next |
| `landing-page/` | [iterum-landing-page](https://github.com/woragis/iterum-landing-page) | Site institucional |
| `iterum-contrato/` | — | HTML estático do contrato (inline no root) |

## Clonar

```bash
git clone --recurse-submodules git@github.com:woragis/iterum.git
cd iterum
git submodule update --init --recursive
```

Repos filhos ainda precisam ser criados no GitHub e receber o primeiro push.
