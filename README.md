## Git算不算程序员的必备技能？ M62K3

更新时间：2026-09-15 07:11:52.930

39sebs.kvb1991.com
380it2.misturabela.com
4ec9fp.kvb1989.com
Git算不算程序员的必备技能？
3gsclw.cdroutlet.com
在Repository name填入testgit，其他保持默认设置，点击“Create repository”按钮，就成功地创建了一个新的Git仓库：
2uevwe.ecvyksp.cn
3q8kgd.kvb1992.com
Git算不算程序员的必备技能？
2ygaez.inmolopez.com
首先，登录github上，然后在右上角找到“create a new repo”创建一个新的仓库。如下：
2lspam.compasslandconsultants.com
3n42zj.misturabela.com
2t1txt.kvb1996.com
44knmc.kvb1989.com
39leth.kvb1982.com
3g2rz0.hothairybushes.com
4i1w6v.kvb1989.com
2r493k.misturabela.com
2q474d.inmolopez.com
现在的情景是：我们已经在本地创建了一个Git仓库后，又想在github创建一个Git仓库，并且希望这两个仓库进行远程同步，这样github的仓库可以作为备份，又可以其他人通过该仓库来协作。
34j7jz.hongyihualang.cn
如何添加远程库？
403mn4.misturabela.com
3tsk48.misturabela.com
Git算不算程序员的必备技能？
3cjyji.ecvyksp.cn
点击 Add Key，你就应该可以看到已经添加的key。
4affew.kvb1998.com
3137gx.hoodamath2.com
368qq0.hongyihualang.cn
Git算不算程序员的必备技能？
3ed1bp.hongyihualang.cn
37rjh3.kvb1990.com
39rn4c.hongyihualang.cn
4gv8mx.kvb1991.com
2vsmgo.inmolopez.com
2ralms.hoodamath2.com
2qus6q.hothairybushes.com
3skmyf.kvb1978.com
2qnf0d.kvb1978.com
46acjw.inmolopez.com
第二步：登录github,打开” settings”中的SSH Keys页面，然后点击“Add SSH Key”,填上任意title，在Key文本框里黏贴id_rsa.pub文件的内容。
3k67r4.kvb1985.com
2w1rmx.inmolopez.com
3q82ls.hoodamath2.com
3blm1b.cdroutlet.com
31ltxo.cdroutlet.com
3nwn0a.kvb1979.com
2lh9sy.compasslandconsultants.com
4eodvs.kvb1998.com
3tya7x.kvb1991.com
id_rsa是私钥，不能泄露出去，id_rsa.pub是公钥，可以放心地告诉任何人。
2qb6xz.hothairybushes.com
39ire6.hoodamath2.com
Git算不算程序员的必备技能？
2yg4yu.misturabela.com
34r99f.kvb1993.com
2s0ozh.hothairybushes.com
2tos5t.kvb1991.com
3hllh4.kvb1981.com
ssh-keygen -t rsa –C “youremail@example.com”, 由于我本地此前运行过一次，所以本地有，如下所示：
3ivotj.kvb1979.com
4ghkt1.kvb1980.com
3ldo1k.inmolopez.com
3wijmu.kvb1981.com
第一步：创建SSH Key。在用户主目录下，看看有没有.ssh目录，如果有，再看看这个目录下有没有id_rsa和id_rsa.pub这两个文件，如果有的话，直接跳过此如下命令，如果没有的话，打开命令行，输入如下命令：
44wca4.kvb1995.com
3d7gp9.hongyihualang.cn
43t3pa.compasslandconsultants.com
39t7rh.kvb1999.com
49samo.hothairybushes.com
2yfyzh.kvb1989.com
在了解之前，先注册github账号，由于你的本地Git仓库和github仓库之间的传输是通过SSH加密的，所以需要一点设置：
3g9ju3.hoodamath2.com
五：远程仓库。
2r2x6g.cdroutlet.com
3o1zs6.misturabela.com
3imacy.kvb1992.com
2rbhvn.kvb1982.com
Git算不算程序员的必备技能？
3vrbmn.inmolopez.com
再来看看我们testgit目录，添加了3个文件了。如下所示：
2twl1u.kvb1990.com
2mldd3.inmolopez.com
4djmiv.kvb1982.com
Git算不算程序员的必备技能？
3hmd8v.kvb1986.com
可以使用如下命令 git checkout -- b.txt，如下所示：
3sjjpd.misturabela.com
3bite5.misturabela.com
34dzi6.kvb1982.com
3l5m37.kvb1978.com
33p837.hoodamath2.com
3oyzub.kvb1991.com
3vrtec.misturabela.com
2vwc7n.hothairybushes.com
只要没有commit之前，如果我想在版本库中恢复此文件如何操作呢？
42jwwk.hoodamath2.com
4f3zkx.kvb1979.com
Git算不算程序员的必备技能？
3thvss.kvb1986.com
3gcl9g.compasslandconsultants.com
49tjem.kvb1995.com
如上：一般情况下，可以直接在文件目录中把文件删了，或者使用如上rm命令：rm b.txt ，如果我想彻底从版本库中删掉了此文件的话，可以再执行commit命令 提交掉，现在目录是这样的，
2vtkxr.kvb1981.com
38krv1.hongyihualang.cn
Git算不算程序员的必备技能？
3mrehz.ecvyksp.cn
假如我现在版本库testgit目录添加一个文件b.txt,然后提交。如下：
3kha5m.hoodamath2.com
二：删除文件。
3fk9dc.kvb1979.com
注意：命令git checkout -- readme.txt 中的 -- 很重要，如果没有 -- 的话，那么命令变成创建分支了。
32ibh5.kvb1987.com
37ntcv.hongyihualang.cn
3rlnv6.inmolopez.com
48di3j.cdroutlet.com
39p5ir.hothairybushes.com
Git算不算程序员的必备技能？
3okmt5.compasslandconsultants.com
对于第二种情况，我想我们继续做demo来看下，假如现在我对readme.txt添加一行 内容为6666666666666，我git add 增加到暂存区后，接着添加内容7777777，我想通过撤销命令让其回到暂存区后的状态。如下所示：
3v4l42.compasslandconsultants.com
2.另外一种是readme.txt已经放入暂存区了，接着又作了修改，撤销修改就回到添加暂存区后的状态。
3grosv.inmolopez.com
2swuap.kvb1988.com
3i7ooz.cdroutlet.com
1.readme.txt自动修改后，还没有放到暂存区，使用 撤销修改就回到和版本库一模一样的状态。
3ef83k.kvb1993.com
45gnk7.kvb1995.com
2ykp4r.hongyihualang.cn
378are.hothairybushes.com
2vof8u.kvb1982.com
31n3qh.kvb1978.com
命令 git checkout --readme.txt 意思就是，把readme.txt文件在工作区做的修改全部撤销，这里有2种情况，如下：
3008fi.kvb1996.com
Git算不算程序员的必备技能？
3p5zib.kvb1981.com
2nzt7m.hongyihualang.cn
3fsjtj.kvb1988.com
3c69n4.cdroutlet.com
33p4ff.kvb1996.com
git checkout -- readme.txt,如下所示：
379sa2.kvb1986.com
40u7jp.kvb1979.com
可以发现，Git会告诉你，git checkout -- file 可以丢弃工作区的修改，如下命令：
4c9u1o.kvb1993.com
Git算不算程序员的必备技能？
4944lq.inmolopez.com
3kpwow.kvb1979.com
2noz0h.inmolopez.com
3m38lv.kvb1983.com
37m6mn.ecvyksp.cn
但是现在我不想使用上面的2种方法，我想直接想使用撤销命令该如何操作呢？首先在做撤销之前，我们可以先用 git status 查看下当前的状态。如下所示：
2xnkmo.kvb1996.com
49qygg.kvb1985.com
3et2rq.kvb1979.com
第二：我可以按以前的方法直接恢复到上一个版本。使用 git reset --hard HEAD^
3m66r6.kvb1995.com
2nf9ap.hoodamath2.com
第一：如果我知道要删掉那些内容的话，直接手动更改去掉那些需要的文件，然后add添加到暂存区，最后commit掉。
48ywrd.hongyihualang.cn
在我未提交之前，我发现添加5555555555555内容有误，所以我得马上恢复以前的版本，现在我可以有如下几种方法可以做修改：
4csbvv.kvb1987.com
3o4w7t.kvb1991.com
3cjfau.cdroutlet.com
2u7y3g.cdroutlet.com
Git算不算程序员的必备技能？
3siyf2.inmolopez.com
3ewus3.hothairybushes.com
2nq571.misturabela.com
比如我现在在readme.txt文件里面增加一行 内容为555555555555，我们先通过命令查看如下：
31ghlc.ecvyksp.cn
3n5drd.kvb1989.com
41bx4x.kvb1982.com
38mkgb.kvb1982.com
一：撤销修改：
3q4rdd.ecvyksp.cn
36gzqu.kvb1992.com
3o01bl.kvb1991.com
4in3p9.kvb1993.com
四：Git撤销修改和删除文件操作。
39ha93.inmolopez.com
2t3z6w.kvb1982.com
Git算不算程序员的必备技能？
2mwqzb.inmolopez.com
接着我们可以使用git commit一次性提交到分支上，如下：
3oio7g.hongyihualang.cn
3gf5hg.kvb1986.com
2qrvan.inmolopez.com
37krr5.ecvyksp.cn
Git算不算程序员的必备技能？
2zmtsj.kvb1987.com
2lc38e.ecvyksp.cn
现在我们先使用git add 命令把2个文件都添加到暂存区中，再使用git status来查看下状态，如下：
3qc4ky.kvb1993.com
Git算不算程序员的必备技能？
3bl70m.ecvyksp.cn
3owvsa.kvb1998.com
41i593.inmolopez.com
41uod4.misturabela.com
42s2vt.cdroutlet.com
我们在readme.txt再添加一行内容为4444444，接着在目录下新建一个文件为test.txt 内容为test，我们先用命令 git status来查看下状态，如下：
4hfbj4.kvb1989.com
我们继续使用demo来演示下：
4d96f0.kvb1989.com
3whsg7.kvb1990.com
第二步：使用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支上。
4dof75.kvb1995.com
3vi422.cdroutlet.com
35t1o5.compasslandconsultants.com
第一步：是使用 git add 把文件添加进去，实际上就是把文件添加到暂存区。
3aavmp.kvb1989.com
3341in.kvb1981.com
3j51oy.kvb1981.com
我们前面说过使用Git提交文件到版本库有两步：
40l52b.compasslandconsultants.com
版本库(Repository)：工作区有一个隐藏目录.git,这个不属于工作区，这是版本库。其中版本库里面存了很多东西，其中最重要的就是stage(暂存区)，还有Git为我们自动创建了第一个分支master,以及指向master的一个指针HEAD。
33klwj.kvb1993.com
工作区：就是你在电脑上看到的目录，比如目录下testgit里的文件(.git隐藏目录版本库除外)。或者以后需要再新建的目录文件等等都属于工作区范畴。
4389nj.inmolopez.com
48n7hp.kvb1983.com
3dlihd.inmolopez.com
3ur2xn.hoodamath2.com
三：理解工作区与暂存区的区别？
3u7k0r.cdroutlet.com
可以看到 目前已经是最新的版本了。
40ssj6.compasslandconsultants.com
3y2e5e.kvb1996.com
Git算不算程序员的必备技能？
30qh07.kvb1991.com
2x1h4m.kvb1987.com
3258sa.kvb1998.com
37q86b.cdroutlet.com
git reset --hard 6fcfc89来恢复了。演示如下：
3xjguk.ecvyksp.cn
通过上面的显示我们可以知道，增加内容3333的版本号是 6fcfc89.我们现在可以命令
4f3r7p.kvb1982.com
3yg5yo.kvb1995.com
Git算不算程序员的必备技能？
2t5twg.kvb1997.com
37donn.kvb1987.com
git reset --hard 版本号 ，但是现在的问题假如我已经关掉过一次命令行或者333内容的版本号我并不知道呢？要如何知道增加3333内容的版本号呢？可以通过如下命令即可获取到版本号：git reflog 演示如下：
352jdc.ecvyksp.cn
44tkof.kvb1980.com
我们看到 增加333333 内容我们没有看到了，但是现在我想回退到最新的版本，如：有333333的内容要如何恢复呢？我们可以通过版本号回退，使用命令方法如下：
38d8g7.cdroutlet.com
3e6639.ecvyksp.cn
4g2vpn.kvb1991.com
Git算不算程序员的必备技能？
3wumjo.kvb1980.com
43t1j2.hoodamath2.com
可以看到，内容已经回退到上一个版本了。我们可以继续使用git log 来查看下历史记录信息，如下：
4j7xeg.kvb1985.com
2rh42l.hongyihualang.cn
3s6ll0.compasslandconsultants.com
2yfvei.kvb1986.com
42uct6.hongyihualang.cn
Git算不算程序员的必备技能？
2vzbfk.kvb1998.com
再来查看下 readme.txt内容如下：通过命令cat readme.txt查看
41n5y3.hoodamath2.com
Git算不算程序员的必备技能？
3jau5s.kvb1995.com
2nn0wi.compasslandconsultants.com
如果想回退到上一个版本的命令如下操作：
2s6j2v.hongyihualang.cn
3jdqn8.hongyihualang.cn
4att3s.kvb1998.com
448im0.compasslandconsultants.com
Git算不算程序员的必备技能？
44k656.kvb1983.com
3yhc6v.kvb1983.com
现在我想使用版本回退操作，我想把当前的版本回退到上一个版本，要使用什么命令呢？可以使用如下2种命令，第一种是：git reset --hard HEAD^ 那么如果要回退到上上个版本只需把HEAD^ 改成 HEAD^^ 以此类推。那如果要回退到前100个版本的话，使用上面的方法肯定不方便，我们可以使用下面的简便命令操作：git reset --hard HEAD~100 即可。未回退之前的readme.txt内容如下：
4dz57y.kvb1986.com
Git算不算程序员的必备技能？
3cwpow.misturabela.com
git log命令显示从最近到最远的显示日志，我们可以看到最近三次提交，最近的一次是,增加内容为333333.上一次是添加内容222222，第一次默认是 111111.如果嫌上面显示的信息太多的话，我们可以使用命令 git log –pretty=oneline 演示如下：
2vmmki.kvb1988.com
3ug7nd.kvb1981.com
2nojhf.hoodamath2.com
3h4hs5.kvb1990.com
4a6mwh.hothairybushes.com
4gtwar.kvb1979.com
3nugmq.kvb1997.com
3j1zzv.kvb1979.com
3l4ywr.misturabela.com
44rq69.kvb1989.com
40ht8n.kvb1985.com
4htp2o.kvb1989.com
4e3iwm.kvb1993.com
Git算不算程序员的必备技能？
38satw.misturabela.com
2rpv7v.kvb1979.com
4dan4e.kvb1999.com
43izh9.kvb1998.com
现在我已经对readme.txt文件做了三次修改了，那么我现在想查看下历史记录，如何查呢？我们现在可以使用命令 git log 演示如下所示：
3ne6k5.kvb1986.com
2q2r0p.kvb1985.com
3z51h0.ecvyksp.cn
3slje8.kvb1998.com
2xr6ax.kvb1998.com
Git算不算程序员的必备技能？
3nmd37.kvb1996.com
45fmes.kvb1995.com
内容为33333333333333.继续执行命令如下：
3j258c.kvb1997.com
如上，我们已经学会了修改文件，现在我继续对readme.txt文件进行修改，再增加一行
4561ww.kvb1993.com
二：版本回退：
3ya98o.misturabela.com
3omh0d.kvb1990.com
Git算不算程序员的必备技能？
3ybnpd.misturabela.com
3l6ef2.kvb1980.com
3qqtqu.kvb1978.com
46gahw.kvb1979.com
3gq9yf.kvb1979.com
如下：
3iw88a.kvb1992.com
2wkz2t.kvb1990.com
知道了对readme.txt文件做了什么修改后，我们可以放心的提交到仓库了，提交修改和提交文件是一样的2步(第一步是git add 第二步是：git commit)。
40z6ia.kvb1991.com
34va5c.misturabela.com
2sqlda.inmolopez.com
如上可以看到，readme.txt文件内容从一行11111111改成 二行 添加了一行22222222内容。
4dgwgd.kvb1997.com
49xnca.kvb1988.com
Git算不算程序员的必备技能？
3pmaug.cdroutlet.com
git diff readme.txt 如下：
4czk6y.kvb1982.com
3z9e20.hothairybushes.com
3ff3ky.hothairybushes.com
4dhklv.kvb1985.com
419nye.kvb1985.com
接下来我想看下readme.txt文件到底改了什么内容，如何查看呢？可以使用如下命令：
38dnf3.compasslandconsultants.com
33bgmz.kvb1999.com
4hhvpu.kvb1978.com
45a4iu.hoodamath2.com
2rvpj7.ecvyksp.cn
3pwmyr.kvb1979.com
3vpnwp.hongyihualang.cn
3rf8la.hothairybushes.com
4cjsh2.kvb1993.com
上面的命令告诉我们 readme.txt文件已被修改，但是未被提交的修改。
46yxkg.kvb1990.com
3pj1lk.kvb1993.com
47tys5.hongyihualang.cn
3o9jh2.kvb1997.com
42avjz.misturabela.com
3szgq7.hothairybushes.com
4a7izc.kvb1991.com
Git算不算程序员的必备技能？
4bm1tf.kvb1983.com
说明没有任何文件未提交，但是我现在继续来改下readme.txt内容，比如我在下面添加一行2222222222内容，继续使用git status来查看下结果，如下：
3cvee8.kvb1988.com
3kgi5t.kvb1979.com
48fglu.inmolopez.com
Git算不算程序员的必备技能？
2o1qix.hothairybushes.com
现在我们已经提交了一个readme.txt文件了，我们下面可以通过命令git status来查看是否还有文件未提交，如下：
4by38l.kvb1980.com
3kn6n9.compasslandconsultants.com
Git算不算程序员的必备技能？
4fhsst.kvb1979.com
第二步：用命令 git commit告诉Git，把文件提交到仓库。
42hvzh.compasslandconsultants.com
如果和上面一样，没有任何提示，说明已经添加成功了。
3slhbn.hongyihualang.cn
33t6kh.kvb1991.com
Git算不算程序员的必备技能？
2u4fbc.kvb1983.com
4gzhf3.kvb1983.com
38g66w.kvb1988.com
4eth2i.kvb1979.com
2vsyux.kvb1993.com
48dj9a.hoodamath2.com
2phhi9.misturabela.com
3qk3qf.hoodamath2.com
3ig9w2.hothairybushes.com
3vaaa0.kvb1987.com
40b2xb.compasslandconsultants.com
4070rg.cdroutlet.com
第一步：使用命令 git add readme.txt添加到暂存区里面去。如下：
3jdc3s.kvb1991.com
3x33i4.hoodamath2.com
我在版本库testgit目录下新建一个记事本文件 readme.txt 内容如下：11111111
41n335.compasslandconsultants.com
36guk8.compasslandconsultants.com
4a63h0.kvb1988.com
3husvp.kvb1985.com
2u2ftm.kvb1978.com
4e7t5x.kvb1993.com
下面先看下demo如下演示：
3rghr2.kvb1993.com
4avz33.kvb1983.com
41a2iv.hothairybushes.com
把文件添加到版本库中。首先要明确下，所有的版本控制系统，只能跟踪文本文件的改动，比如txt文件，网页，所有程序的代码等，Git也不列外，版本控制系统可以告诉你每次的改动，但是图片，视频这些二进制文件，虽能也能由版本控制系统管理，但没法跟踪文件的变化，只能把二进制文件每次改动串起来，也就是知道图片从1kb变成2kb，但是到底改了啥，版本控制也不知道。

---

# fkp3ifev
Auto-created repository for publishing - 2026-09-15T07:11:47.104Z
