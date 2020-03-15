# dblp 自动化工具

**Demo1**: url=`https://dblp.uni-trier.de/search/publ/api?q=toc%3Adb/conf/nips/nips2018.bht%3A&h=1000&format=json`

**Demo2**: url=`https://dblp.uni-trier.de/search/publ/api?q=stream%3Astreams%2Fconf%2Ficcv%3A&h=1000&format=json&f=1000`

1. `https://dblp.uni-trier.de/search/publ/api`
2.  `?q=stream%3Astreams%2Fconf%2Ficcv%3A`
	1. `stream%3A`
	2. `streams%2F`
	3. `conf%2F`: conf | journals
	4. `iccv%3A`: iccv, nips, iclr, aaai, acl, icml, cvpr, ijcai, ccs, sp, uss, icassp, interspeech, odyssey, slt, eusipco, iscslp | tifs, taslp, speech, spl, csl, jstsp, spm, tii, iotj, tcyb, tsp, taffco, tmm
3. `&h=1000`
4. `&format=json`
5. `&f=1000`

查询关键词描述：

- `q=查询内容`
- `h=hits次数`，表示记录次数，上限 1000
- `format=内容格式`，xml、json等
- `f=first记录号`，超过 1000 记录，可以多次查询，f = f0 + 1000