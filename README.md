# learn-cicd-typescript-starter (Hushik)

Էս repo-ն պարունակում ա «Hushik» app-ի TypeScript starter code-ը՝ [Sovorem.am](https://sovorem.am)-ի «Learn CICD» course-ի համար։

## Local Development

Համոզվի, որ Node-ի version-ը 22+ ա։

Պրոյեկտի root-ում ստեղծիր `.env` ֆայլ՝ սենց պարունակությամբ․

```bash
PORT="8080"
```

Run արա server-ը․

```bash
npm install
npm run dev
```

_Սենց server-ը run ա անում առանց database-ի (non-database mode)։_ Կբացի մի պարզ webpage `http://localhost:8080` հասցեում։

Դեռ պետք չի database setup անել կամ webpage-ի վրա ինտերակտիվություն ավելացնել։ Դրա հրահանգները կգան course-ի մեջ ավելի ուշ։
