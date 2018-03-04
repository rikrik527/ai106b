# 機率推論 (Probability & Inference)

## Gibbs Sampling Algorithm

* https://mdbookspace.com/view/ai/gibbs.md

```
$ node gibbs
P = [0.5,0.5]
P = [0.6,0.4]
P = [0.62,0.38]
P = [0.624,0.376]
P = [0.6248,0.3752]
5/8=0.625 3/8=0.375
```

## Metropolis-Hasting Algorithm

* https://mdbookspace.com/view/ai/metropolis.md

```
$ node .\metropolis.js
Q = [[0.5,0.5],[0.5,0.5]]
A = [[1,0.6],[1.6666666666666667,1]]
diff = 0.2
Q = [[0.7,0.3],[0.5,0.5]]
A = [[1,1],[1,1]]
diff = 0
```

## EM Algorithm

```
$ npm i j6

$ node em
pA=0.6,0.4 pB=0.5,0.5 delta=9.9999
pA=0.7130122354005162,0.28698776459948394 pB=0.5813393083136625,0.41866069168633735 delta=0.113
pA=0.7452920360819945,0.25470796391800554 pB=0.5692557501718727,0.4307442498281272 delta=0.0323
pA=0.768098834367321,0.23190116563267898 pB=0.5495359141383478,0.45046408586165226 delta=0.0228
pA=0.7831645842999736,0.2168354157000264 pB=0.5346174541475204,0.4653825458524797 delta=0.0151
pA=0.7910552458637528,0.2089447541362473 pB=0.526281167029932,0.4737188329700681 delta=0.0083
pA=0.7945325379936994,0.2054674620063006 pB=0.5223904375178748,0.47760956248212527 delta=0.0039
pA=0.7959286672497986,0.20407133275020142 pB=0.5207298780860259,0.4792701219139741 delta=0.0017
```


