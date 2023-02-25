what is [Deno](https://deno.land/)?
The easiest, most secure Javascript runtime.

How to install Deno?
curl -fsSL https://deno.land/x/install/install.sh | sh
[Other details](https://deno.land/manual@v1.31.1/getting_started/installation).

[Getting started](https://deno.land/manual@v1.31.1/getting_started/first_steps).

`deno run first_steps.ts`

┌ ⚠️  Deno requests net access to "yirenlu.com".
├ Requested by `fetch()` API
├ Run again with --allow-net to bypass this prompt.
└ Allow? [y/n/A] (y = yes, allow; n = no, deny; A = allow all net permissions) > 

`deno run --allow-net=yirenlu.com first_steps.ts https://yirenlu.com/`

Trying out more [demos](https://examples.deno.land/).
