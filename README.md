## 目前，在GitHub上的这个testgit仓库还是空的，GitHub告诉我们，可以从这个仓库克隆出新的仓库，也可以把一个已有的本地仓库与之关联，然后，把本地仓库的内容推送到GitHub仓库。 O2YB6

更新时间：2026-09-15 06:40:37.468

那么一般情况下，那些分支要推送呢？
3eqbbn.hongyihualang.cn
可以看到 推送成功了，如果我们现在要推送到其他分支，比如dev分支上，我们还是那个命令 git push origin dev
4d71s7.kvb1983.com
Git算不算程序员的必备技能？
2s80rk.kvb1982.com
32u5vu.cdroutlet.com
3z0tfb.kvb1993.com
377l9b.kvb1995.com
我们可以看到如上，推送成功，我们可以继续来截图github上的readme.txt内容 如下：
4bi0ou.kvb1980.com
3azxp5.kvb1999.com
3awjt1.kvb1983.com
3ix27w.kvb1978.com
2vm5nn.kvb1987.com
3f0fm9.ecvyksp.cn
Git算不算程序员的必备技能？
3to1ze.hoodamath2.com
4idl19.kvb1990.com
4clcww.kvb1980.com
3bsflv.kvb1988.com
现在我想把本地更新的readme.txt代码推送到远程库中，使用命令如下：
3byppj.kvb1992.com
466mha.kvb1997.com
Git算不算程序员的必备技能？
3pm95y.kvb1991.com
3fbug4.kvb1998.com
3zxfxx.hothairybushes.com
44a9ew.kvb1990.com
3yt85z.kvb1980.com
4dljgs.kvb1983.com
45kyvo.kvb1980.com
49522d.kvb1982.com
2x688h.compasslandconsultants.com
2rz8fu.kvb1988.com
本地的readme.txt代码如下：
2pwuuz.kvb1995.com
3hfbje.hoodamath2.com
4divsy.kvb1983.com
3t0qoi.kvb1979.com
Git算不算程序员的必备技能？
3ank14.compasslandconsultants.com
比如我现在的github上的readme.txt代码如下：
2ueuur.kvb1992.com
4dz2hn.kvb1988.com
3julxl.cdroutlet.com
47ggps.ecvyksp.cn
使用命令 git push origin master
2zhizh.kvb1978.com
47hylg.kvb1981.com
3kki49.misturabela.com
3fs84q.hothairybushes.com
3trtst.hongyihualang.cn
推送分支就是把该分支上所有本地提交到远程库中，推送时，要指定本地分支，这样，Git就会把该分支推送到远程库对应的远程分支上：
4bmgw8.kvb1992.com
3tlx1e.misturabela.com
3b895i.kvb1986.com
31ao4w.hoodamath2.com
3gx6zp.kvb1990.com
一：推送分支：
328xbr.inmolopez.com
40uf3s.kvb1991.com
2xxt1l.inmolopez.com
Git算不算程序员的必备技能？
3te1jz.kvb1999.com
如下演示：
4hc4hk.kvb1988.com
2moiil.cdroutlet.com
要查看远程库的详细信息 使用 git remote –v
3xwdct.hongyihualang.cn
3kezfw.kvb1989.com
3nb79s.ecvyksp.cn
3vrt2z.kvb1991.com
41o1ow.kvb1991.com
要查看远程库的信息 使用 git remote
3c4xcp.hongyihualang.cn
当你从远程库克隆时候，实际上Git自动把本地的master分支和远程的master分支对应起来了，并且远程库的默认名称是origin。
2xbuam.kvb1997.com
八：多人协作。
4jag3l.kvb1978.com
Git算不算程序员的必备技能？
38j2lr.hoodamath2.com
383o7o.hoodamath2.com
3s3b2s.kvb1997.com
演示如下
3irayp.kvb1996.com
3belcu.kvb1996.com
2.另一种方式是使用git stash pop,恢复的同时把stash内容也删除了。
3qtvup.kvb1987.com
4a1i9t.inmolopez.com
1.git stash apply恢复，恢复后，stash内容并不删除，你需要使用命令git stash drop来删除。
3a2avi.kvb1980.com
工作现场还在，Git把stash内容存在某个地方了，但是需要恢复一下，可以使用如下2个方法：
3rurci.kvb1998.com
3yoqua.cdroutlet.com
375kzf.compasslandconsultants.com
39q29q.kvb1998.com
35ct5p.inmolopez.com
Git算不算程序员的必备技能？
3qpa6e.ecvyksp.cn
工作区是干净的，那么我们工作现场去哪里呢？我们可以使用命令 git stash list来查看下。如下：
3xgly8.kvb1978.com
43zacn.kvb1995.com
3fqxnk.ecvyksp.cn
Git算不算程序员的必备技能？
3whlbb.kvb1980.com
现在，我们回到dev分支上干活了。
3qd04c.kvb1997.com
Git算不算程序员的必备技能？
3n00fn.compasslandconsultants.com
4dls9f.kvb1985.com
修复完成后，切换到master分支上，并完成合并，最后删除issue-404分支。演示如下：
2z4gb3.cdroutlet.com
3wctld.inmolopez.com
Git算不算程序员的必备技能？
3b8u2j.kvb1995.com
3sofgq.misturabela.com
首先我们要确定在那个分支上修复bug，比如我现在是在主分支master上来修复的，现在我要在master分支上创建一个临时分支，演示如下：
2v62j4.ecvyksp.cn
3sh03i.misturabela.com
2xubx5.hongyihualang.cn
33e6qp.kvb1999.com
31gu4j.hongyihualang.cn
35buel.kvb1988.com
4i1k3f.kvb1998.com
3x4vjd.kvb1979.com
所以现在我可以通过创建issue-404分支来修复bug了。
4e2p9i.kvb1993.com
2vzryd.hothairybushes.com
37fhmk.kvb1980.com
Git算不算程序员的必备技能？
3qv0bl.kvb1999.com
并不是我不想提交，而是工作进行到一半时候，我们还无法提交，比如我这个分支bug要2天完成，但是我issue-404 bug需要5个小时内完成。怎么办呢？还好，Git还提供了一个stash功能，可以把当前工作现场 ”隐藏起来”，等以后恢复现场后继续工作。如下：
3kdfdk.kvb1989.com
Git算不算程序员的必备技能？
4ahstq.inmolopez.com
389ydn.compasslandconsultants.com
453j1h.kvb1998.com
2tnok6.kvb1988.com
3et7d0.inmolopez.com
41gfx3.kvb1996.com
比如我在开发中接到一个404 bug时候，我们可以创建一个404分支来修复它，但是，当前的dev分支上的工作还没有提交。比如如下：
3uonmw.kvb1995.com
45qxfx.hoodamath2.com
4e78vk.kvb1987.com
在开发中，会经常碰到bug问题，那么有了bug就需要修复，在Git中，分支是很强大的，每个bug都可以通过一个临时分支来修复，修复完成后，合并分支，然后将临时的分支删除掉。
4cr5ac.kvb1991.com
七：bug分支：
3sbr83.hongyihualang.cn
475s8c.ecvyksp.cn
2n9u27.hongyihualang.cn
3fgh1w.cdroutlet.com
分支策略：首先master主分支应该是非常稳定的，也就是用来发布新版本，一般情况下不允许在上面干活，干活一般情况下在新建的dev分支上干活，干完后，比如上要发布，或者说dev分支代码稳定后可以合并到主分支master上来。
45swho.kvb1980.com
4c20eb.kvb1995.com
3v93kb.ecvyksp.cn
3rcg83.hothairybushes.com
4a2qre.kvb1992.com
30quj5.kvb1987.com
35d6rs.kvb1992.com
2ug1qd.kvb1991.com
410333.compasslandconsultants.com
35cxtf.kvb1998.com
Git算不算程序员的必备技能？
4dciua.kvb1991.com
3vb0mb.kvb1995.com
创建一个dev分支。 修改readme.txt内容。 添加到暂存区。 切换回主分支(master)。 合并dev分支，使用命令 git merge –no-ff -m “注释” dev 查看历史记录 截图如下：
3uhic0.kvb1993.com
通常合并分支时，git一般使用”Fast forward”模式，在这种模式下，删除分支后，会丢掉分支信息，现在我们来使用带参数 –no-ff来禁用”Fast forward”模式。首先我们来做demo演示下：
3tuveh.hoodamath2.com
33s154.kvb1982.com
3.分支管理策略。
49rio0.kvb1981.com
49t16t.kvb1997.com
3hoevo.compasslandconsultants.com
3fc54f.hongyihualang.cn
3dquda.inmolopez.com
2ydr2x.kvb1979.com
4dd5gc.kvb1980.com
3ood3z.inmolopez.com
39tzu9.kvb1990.com
3nvf40.kvb1985.com
3drx5l.ecvyksp.cn
38faa9.compasslandconsultants.com
Git算不算程序员的必备技能？
31v2p8.kvb1989.com
2n3dyh.inmolopez.com
如果我想查看分支合并的情况的话，需要使用命令 git log.命令行演示如下：
3oo64z.kvb1979.com
3rcw28.kvb1985.com
Git算不算程序员的必备技能？
3d6ixx.kvb1981.com
4gibys.kvb1993.com
Git用，=======，标记出不同分支的内容，其中HEAD是指主分支修改的内容，fenzhi1 是指fenzhi1上修改的内容，我们可以修改下如下后保存：
3ds1fe.misturabela.com
Git算不算程序员的必备技能？
36eb5g.kvb1983.com
3oiolo.compasslandconsultants.com
2uwlks.kvb1995.com
现在我们需要在master分支上来合并fenzhi1，如下操作：
3ei478.misturabela.com
45wfro.kvb1992.com
Git算不算程序员的必备技能？
40xg23.kvb1986.com
2t9yj3.hongyihualang.cn
同样，我们现在切换到master分支上来，也在最后一行添加内容，内容为99999999，如下所示：
3t02ls.kvb1999.com
Git算不算程序员的必备技能？
4j9igg.kvb1981.com
3tzylp.compasslandconsultants.com
下面我们还是一步一步来，先新建一个新分支，比如名字叫fenzhi1，在readme.txt添加一行内容8888888，然后提交，如下所示：
2wgw01.hoodamath2.com
39byex.hoodamath2.com
2slfm0.kvb1995.com
3ib0r1.compasslandconsultants.com
41tenr.misturabela.com
如何解决冲突？
3ocezs.kvb1979.com
3rfkyn.kvb1980.com
4aazbp.compasslandconsultants.com
3nsj7n.ecvyksp.cn
2mx7pa.inmolopez.com
删除分支：git branch –d name
46ybmr.kvb1991.com
303z71.kvb1983.com
3u97ig.cdroutlet.com
合并某分支到当前分支：git merge name
49bmuy.kvb1978.com
3f53fj.hothairybushes.com
创建+切换分支：git checkout –b name
3464sz.kvb1978.com
3sqwj4.inmolopez.com
切换分支：git checkout name
2y9qeg.kvb1983.com
3mw0eu.cdroutlet.com
创建分支：git branch name
3t0jco.kvb1995.com
466vj2.inmolopez.com
3semwg.hoodamath2.com
41ff6n.inmolopez.com
查看分支：git branch
2wj1ku.kvb1991.com
3d1jfz.compasslandconsultants.com
4e5usi.kvb1982.com
总结创建与合并分支命令如下：
435f27.kvb1989.com
2vu1kl.kvb1998.com
3y833u.kvb1982.com
3jyb3f.kvb1996.com
Git算不算程序员的必备技能？
4criuc.kvb1996.com
合并完成后，我们可以接着删除dev分支了，操作如下：
31bqkx.kvb1999.com
注意到上面的Fast-forward信息，Git告诉我们，这次合并是“快进模式”，也就是直接把master指向dev的当前提交，所以合并速度非常快。
41f5qj.hoodamath2.com
412pwj.misturabela.com
32prrn.cdroutlet.com
3cu8ci.cdroutlet.com
2vibwf.kvb1987.com
48rv36.hoodamath2.com
3u83qp.kvb1993.com
git merge命令用于合并指定分支到当前分支上，合并后，再查看readme.txt内容，可以看到，和dev分支最新提交的是完全一样的。
339agk.hongyihualang.cn
3yykka.kvb1981.com
39q6c5.ecvyksp.cn
3m7t7k.kvb1985.com
3qkcls.hoodamath2.com
Git算不算程序员的必备技能？
3xbku6.cdroutlet.com
39dbli.kvb1980.com
424xq2.kvb1997.com
3wyrlk.kvb1997.com
现在我们可以把dev分支上的内容合并到分支master上了，可以在master分支上，使用如下命令 git merge dev 如下所示：
3x25u5.misturabela.com
Git算不算程序员的必备技能？
4byixx.kvb1983.com
现在dev分支工作已完成，现在我们切换到主分支master上，继续查看readme.txt内容如下：
2qvo9m.hoodamath2.com
3u3n8e.kvb1982.com
30dutx.kvb1988.com
2s5vyr.cdroutlet.com
2qplwm.kvb1983.com
3tgjnz.ecvyksp.cn
2swz2f.kvb1989.com
2tj3c0.kvb1988.com
2x108a.kvb1980.com
3n0uh7.kvb1997.com
2ye6io.kvb1998.com
30bjwq.misturabela.com
Git算不算程序员的必备技能？
2n27ip.inmolopez.com
42drgm.kvb1991.com
3u2q4i.kvb1982.com
3hl9y2.compasslandconsultants.com
首先我们先来查看下readme.txt内容，接着添加内容77777777，如下：
46a6a0.kvb1980.com
3p6jrw.compasslandconsultants.com
3b3lmr.ecvyksp.cn
4gzdql.kvb1999.com
3aobi5.kvb1989.com
3xurzi.kvb1980.com
3e97t7.compasslandconsultants.com
3alioo.inmolopez.com
42m63t.ecvyksp.cn
42fks9.misturabela.com
3yh4kb.inmolopez.com
4h6p7b.kvb1986.com
36uyek.compasslandconsultants.com
2z440c.hoodamath2.com
git branch查看分支，会列出所有的分支，当前分支前面会添加一个星号。然后我们在dev分支上继续做demo，比如我们现在在readme.txt再增加一行 7777777777777
3thspl.kvb1981.com
2o2mzd.cdroutlet.com
3m9pwk.ecvyksp.cn
git checkout dev
36725l.kvb1983.com
416qtl.hongyihualang.cn
3bn3ew.cdroutlet.com
4f9qwn.kvb1999.com
git branch dev
3r72pn.kvb1991.com
45g87f.hoodamath2.com
2rp2ru.kvb1985.com
2lhged.hongyihualang.cn
2sgeng.cdroutlet.com
2sr9b7.ecvyksp.cn
git checkout 命令加上 –b参数表示创建并切换，相当于如下2条命令
4b0mox.kvb1988.com
2v5a3q.kvb1988.com
2rouic.ecvyksp.cn
Git算不算程序员的必备技能？
2t0z3c.cdroutlet.com
首先，我们来创建dev分支，然后切换到dev分支上。如下操作：
3xvu5l.compasslandconsultants.com
在 版本回填退里，你已经知道，每次提交，Git都把它们串成一条时间线，这条时间线就是一个分支。截止到目前，只有一条时间线，在Git里，这个分支叫主分支，即master分支。HEAD严格来说不是指向提交，而是指向master，master才是指向提交的，所以，HEAD指向的就是当前分支。
3mddgg.kvb1978.com
49pesk.ecvyksp.cn
3udqd7.hoodamath2.com
47bgui.kvb1983.com
六：创建与合并分支。
2v6zm3.hoodamath2.com
44asqc.kvb1979.com
3sd80r.hongyihualang.cn
Git算不算程序员的必备技能？
4a2uaz.kvb1995.com
4fz7e6.kvb1999.com
398giz.hongyihualang.cn
接着在我本地目录下 生成testgit2目录了，如下所示：
3nm9d7.kvb1988.com
3mgbkl.ecvyksp.cn
Git算不算程序员的必备技能？
4gui6p.kvb1982.com
4df7vb.kvb1993.com
现在，远程库已经准备好了，下一步是使用命令git clone克隆一个本地库了。如下所示：
33eiep.kvb1982.com
3q6427.kvb1992.com
Git算不算程序员的必备技能？
48fjr8.kvb1998.com
如下，我们看到：
39g4qx.kvb1980.com
3v6b8c.kvb1982.com
Git算不算程序员的必备技能？
3yyisd.kvb1990.com
首先，登录github，创建一个新的仓库，名字叫testgit2.如下：
38jpgg.hoodamath2.com
现在我们想，假如远程库有新的内容了，我想克隆到本地来 如何克隆呢？
2w5iaz.kvb1999.com
如何从远程库克隆？上面我们了解了先有本地库，后有远程库时候，如何关联远程库。
3wc1hj.ecvyksp.cn
2lazd8.hongyihualang.cn
把本地master分支的最新修改推送到github上了，现在你就拥有了真正的分布式版本库了。
312hr4.kvb1998.com
2vfv30.kvb1990.com
3d5xfp.hothairybushes.com
3zsu1m.kvb1980.com
3v52iy.kvb1982.com
git push origin master
3a294c.kvb1978.com
2yjhkm.misturabela.com
2v34sv.kvb1987.com
3rq059.kvb1992.com
30vlid.kvb1981.com
从现在起，只要本地作了提交，就可以通过如下命令：
42rjtm.kvb1985.com
34qrtj.hongyihualang.cn
2tgzjf.hongyihualang.cn
Git算不算程序员的必备技能？
3e70dw.compasslandconsultants.com
416plw.cdroutlet.com
由于远程库是空的，我们第一次推送master分支时，加上了 –u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。推送成功后，可以立刻在github页面中看到远程库的内容已经和本地一模一样了，上面的要输入github的用户名和密码如下所示：
2lm355.cdroutlet.com
把本地库的内容推送到远程，使用 git push命令，实际上是把当前分支master推送到远程。
3tyhx9.compasslandconsultants.com
Git算不算程序员的必备技能？
32548k.hongyihualang.cn
3kjcxs.kvb1979.com
所有的如下：
4508k9.hothairybushes.com
git remote add origin
3ri6xj.kvb1987.com
现在，我们根据GitHub的提示，在本地的testgit仓库下运行命令：

---

# e8j0tv
Auto-created repository for publishing - 2026-09-15T06:40:31.515Z
