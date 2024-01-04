# Tutorial Template Project

This is a [Dagster](https://dagster.io/) project made to be used alongside the official [Dagster tutorial](https://docs.dagster.io/tutorial).

```sh
(.venv) gesogeso@gesogeso ~/src/tmp/dagster-tutorial (main) $ duckdb analytics.hackernews
v0.9.2 3c695d7ba9
Enter ".help" for usage hints.
D .database
analytics: analytics.hackernews
D .table
topstories
D select * from public.topstories;
┌─────────────────┬─────────────┬───┬──────────────────────┬──────────────────────┐
│       by        │ descendants │ … │         url          │         text         │
│     varchar     │   double    │   │       varchar        │       varchar        │
├─────────────────┼─────────────┼───┼──────────────────────┼──────────────────────┤
│ madmax108       │       106.0 │ … │ https://www.morlin…  │                      │
│ NN88            │       755.0 │ … │ https://www.busine…  │                      │
│ hhs             │        96.0 │ … │ https://www.uni-wu…  │                      │
│ paulolc         │        15.0 │ … │ https://lamport.az…  │                      │
│ serialx         │         5.0 │ … │ https://swizec.com…  │                      │
│ aarroyoc        │       306.0 │ … │ https://twitter.co…  │                      │
│ CharlesW        │        56.0 │ … │ https://www.lilygo…  │                      │
│ T-A             │        19.0 │ … │ https://github.com…  │                      │
│ lunarcave       │         4.0 │ … │ https://amber-lang…  │                      │
│ wolframkriesing │         0.0 │ … │ https://jskatas.or…  │                      │
│ divbzero        │         1.0 │ … │ https://www.latime…  │                      │
│ todsacerdoti    │        10.0 │ … │ https://macadie.in…  │                      │
│ leiferik        │       123.0 │ … │ https://www.backbl…  │                      │
│ ingve           │         8.0 │ … │ https://utcc.utoro…  │                      │
│ 1970-01-01      │         5.0 │ … │ https://flashpoint…  │                      │
│ w4lker          │        84.0 │ … │ https://katelynsil…  │                      │
│ ibobev          │        69.0 │ … │ https://livepluspl…  │                      │
│ LaserPineapple  │        84.0 │ … │ https://osansevier…  │                      │
│ api             │        58.0 │ … │ https://github.com…  │                      │
│ belter          │         3.0 │ … │ https://www.bonham…  │                      │
│   ·             │          ·  │ · │          ·           │          ·           │
│   ·             │          ·  │ · │          ·           │          ·           │
│   ·             │          ·  │ · │          ·           │          ·           │
│ ColinWright     │        12.0 │ … │ https://arxiv.org/…  │                      │
│ accessd         │        64.0 │ … │ https://github.com…  │ Hi! I&#x27;ve been…  │
│ johntfella      │         0.0 │ … │ https://vimeo.com/…  │                      │
│ manicennui      │         0.0 │ … │ https://arstechnic…  │                      │
│ MarlonPro       │        46.0 │ … │ https://designsyst…  │                      │
│ memalign        │       213.0 │ … │ https://abagames.g…  │                      │
│ noteness        │        20.0 │ … │ https://github.com…  │                      │
│ reqo            │        23.0 │ … │ https://www.fleet.…  │                      │
│ attractivechaos │       165.0 │ … │ https://github.com…  │                      │
│ anigbrowl       │         9.0 │ … │ https://www.gamesp…  │                      │
│ gslin           │       173.0 │ … │ https://www.youtub…  │                      │
│ whoishiring     │       357.0 │ … │                      │ Please state the l…  │
│ gslin           │         0.0 │ … │ https://www.eff.or…  │                      │
│ internetter     │         7.0 │ … │ https://www.scmaga…  │                      │
│ admp            │       108.0 │ … │ https://github.com…  │                      │
│ apollinaire     │         3.0 │ … │ https://www.thepar…  │                      │
│ EclipseMantis   │        14.0 │ … │                      │ Hey, HN!\nLong-tim…  │
│ todsacerdoti    │        19.0 │ … │ https://wozniak.ca…  │                      │
│ perihelions     │       231.0 │ … │ https://www.nytime…  │                      │
│ weinzierl       │        54.0 │ … │ https://blog.cr.yp…  │                      │
├─────────────────┴─────────────┴───┴──────────────────────┴──────────────────────┤
│ 100 rows (40 shown)                                        10 columns (4 shown) │
└─────────────────────────────────────────────────────────────────────────────────┘
D
```
