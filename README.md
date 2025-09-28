This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

Show minimal example of issues with the documented [middleware matcher](https://nextjs.org/docs/app/api-reference/file-conventions/middleware#matcher)

See [middleware.ts](./middleware.ts) copied from the official next.js docs - https://nextjs.org/docs/app/api-reference/file-conventions/middleware#matcher

When trying to run this project it exits with this error:
```
Error parsing `/:nextData(_next/data/[^/]{1,})?/api/*{(\\.json)}?` https://nextjs.org/docs/messages/invalid-route-source
Reason: Unexpected MODIFIER at 37, expected END

  /:nextData(_next/data/[^/]{1,})?/api/*{(\\.json)}?
                                       ^

[Error: Invalid source: /:nextData(_next/data/[^/]{1,})?/api/*{(\\.json)}?]
```
