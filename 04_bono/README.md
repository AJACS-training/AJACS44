# AJACS44/bono


<p><span style="font-size:36px;display:inline-block;line-height:130%;text-indent:0px">ゲノム情報を閲覧・取得し、活用する</span></p>
<p>講習では【実習】を皆さんとやっていきます。早くできてしまった人は、統合TV<a href="http://togotv.dbcls.jp/" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://togotv.dbcls.jp/" /></a>(←このアイコンが目印です) を参考に【発展】をやってみたりしてください。</p>
<hr class="full_hr" />
<p>目次</p>
<div class="contents">
<a id="contents_1"></a>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="#af072cf3">  ウイルスが宿主のゲノムに取り込まれているのを調べる </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#a33e5940">  NCBI </a></li>
<li><a href="#lb2f4ecc">  UCSC Genome Browser+BLAT </a></li></ul></li>
<li><a href="#o641919a">  ウイルスの宿主のゲノムに付与されたアノテーションをゲノムブラウザ上で調べる </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#t3e2b7d7">  Ensembl Genome Browser </a></li></ul></li>
<li><a href="#nd0eeaab">  ゲノム配列が解読された生物種を調べる </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#f123c46d">  GOLD </a></li></ul></li>
<li><a href="#f40f03ce">  DBCLSのツールを使ってみる </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#u57e6556">  GGRNA </a></li>
<li><a href="#k5b7a41a">  GGGenome </a></li></ul></li></ul>
</div>

<hr class="full_hr" />
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習0】このコマの講師、<strong>坊農秀雅</strong>でググりなさい。何件ヒットがありますか？
<a name="plugin_fold_anchor1"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor1')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>覗かないでね。;-p</p>
</div></li></ul>
<h3 id="content_1_0"><a id="af072cf3" href=""title="af072cf3"><span class="sanchor">_</span></a> ウイルスが宿主のゲノムに取り込まれているのを調べる  </h3>

<h3 id="content_1_1"><a id="a33e5940" href=""title="a33e5940">_</a> NCBI  </h3>
<p>National Center for Biotechnology Information. NIHの研究機関の一つで、生命科学系のデータベースの総本山。<strong>NCBI</strong> でググればトップに出てきます。</p>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A1】NCBI ラウス肉腫ウイルスのエントリを表示しなさい。
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>まずは、<a href="http://biosciencedbc.jp/dbsearch/" rel="nofollow">生命科学DB横断検索</a>を用いて「ラウス肉腫ウイルス」の英語名を調べましょう。</li>
<li>それを検索語として、NCBIで検索してみると…。
<a name="plugin_fold_anchor2"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor2')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p><a href="http://www.ncbi.nlm.nih.gov/Taxonomy/Browser/wwwtax.cgi?mode=Info&amp;id=11886&amp;lvl=3&amp;lin=f&amp;keep=1&amp;srchmode=1&amp;unlock" rel="nofollow">http://www.ncbi.nlm.nih.gov/Taxonomy/Browser/wwwtax.cgi?mode=Info&amp;id=11886&amp;lvl=3&amp;lin=f&amp;keep=1&amp;srchmode=1&amp;unlock</a></p>
</div></li>
<li>【発展B1】NCBI Taxonomy Browserを使って、インフルエンザウイルスを検索しなさい。
<ul class="list3" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://www.youtube.com/watch?v=QDxVUCHKOaE" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://www.youtube.com/watch?v=QDxVUCHKOaE" /></a> <a href="http://togotv.dbcls.jp/20090226.html" rel="nofollow">NCBI Taxonomy Browserを使って、生物分類と配列情報を関連させて調べる</a></li></ul></li></ul></li></ul>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A2】右上の'Genome'の'1'をクリックすると、このウイルスのゲノム配列情報のページに飛ぶことができる。ゲノムサイズ、GC含量、遺伝子数を確認しなさい。
<a name="plugin_fold_anchor3"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor3')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>ゲノムサイズ: 9.39kb、GC含量: 54.1%、遺伝子数: 4</p>
</div></li></ul>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A3】さらに'Graphics'をクリックするとどういった情報が得られるでしょうか?
<a name="plugin_fold_anchor4"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor4')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>ウイルスゲノム配列にコードされた遺伝子がグラフィカルに表示される（ゲノムブラウザ）</p>
</div></li></ul>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A4】Taxonomy Browserのラウス肉腫ウイルスのエントリに戻り、右上の'Nucleotide'の数字をクリックし、ラウス肉腫ウイルスの核酸配列として登録されたレコードを閲覧しなさい。そして、上部の検索フォームに検索後'src'を追加することで絞り込み検索をかけ、v-src遺伝子の完全長配列(complete cds)を表示しなさい。
<a name="plugin_fold_anchor5"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor5')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p><a href="http://www.ncbi.nlm.nih.gov/nuccore/M33292.1" rel="nofollow">http://www.ncbi.nlm.nih.gov/nuccore/M33292.1</a></p>
</div></li></ul>

<h3 id="content_1_2"><a id="lb2f4ecc" href=""title="lb2f4ecc">_</a> UCSC Genome Browser+BLAT  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A5】得たv-src遺伝子の塩基配列を宿主のニワトリのゲノムに<a href="http://genome.ucsc.edu/cgi-bin/hgBlat?command=start" rel="nofollow">BLAT検索</a>しなさい。その結果'details'をクリックすることで得た詳細検索結果を精査することで宿主から持ちだした配列のどの部分に変異が入ったか、確認しなさい。
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>参考:  <a href="http://www.youtube.com/watch?v=uMwhJQZoyfE" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://www.youtube.com/watch?v=uMwhJQZoyfE" /></a> <a href="http://togotv.dbcls.jp/20121030.html" rel="nofollow">ウイルスの持ち出した宿主の遺伝子配列がコードされている領域をアミノ酸配列レベルでゲノム中から探し当てる 2012</a></li></ul></li></ul>

<h3 id="content_1_3"><a id="o641919a" href=""title="o641919a"><span class="sanchor">_</span></a> ウイルスの宿主のゲノムに付与されたアノテーションをゲノムブラウザ上で調べる  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A6】BLAT検索結果の'browser'をクリックすると、検索配列がヒットしたゲノム領域にジャンプすることができる。出てきたページはゲノムブラウザと呼ばれ、ゲノム配列上のさまざまなアノテーションが「統合」されているツールである。
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>上部のzoom inで'10x'ボタンを押して遺伝子コード領域を拡大してみなさい。</li>
<li>下部のTrackにおいて、'Restr Enzymes'(制限酵素の意味)で'full'を選択し、refreshボタンを押しなさい。ゲノムブラウザにどういった情報が付加されましたか?
<ul class="list3" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://youtu.be/AleaXJKHuiY" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://youtu.be/AleaXJKHuiY" /></a> <a href="http://togotv.dbcls.jp/20120528.html" rel="nofollow"> UCSC Genome Browserの使い方～表示+ENCODE編～ 2012</a></li></ul></li>
<li>【発展B2】 UCSC Genome Browserを使って、今見ている領域のDNA配列を取得しなさい。
<ul class="list3" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://youtu.be/JvrE_YtM8z0" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://youtu.be/JvrE_YtM8z0" /></a> <a href="http://togotv.dbcls.jp/20131113.html" rel="nofollow">UCSC Genome Browserの使い方～配列取得編～ 2013</a></li></ul></li></ul></li></ul>

<h3 id="content_1_4"><a id="t3e2b7d7" href=""title="t3e2b7d7">_</a> Ensembl Genome Browser  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A7】同様のゲノムブラウザとしてよく使われているものに<a href="http://ensembl.org/" rel="nofollow">Ensembl</a>（アンサンブル）がある。ヒトを中心に出芽酵母までのゲノムとそのアノテーションが閲覧できる。EnsemblでヒトSRC遺伝子を検索し、ゲノムブラウザ上でその領域を表示しなさい。さらに、zoom out機能を使い、SRC遺伝子コード領域の周りを表示しなさい。
<a name="plugin_fold_anchor6"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor6')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p><a href="http://asia.ensembl.org/Homo_sapiens/Gene/Summary?db=core;g=ENSG00000197122;r=20:35973088-36034453" rel="nofollow">http://asia.ensembl.org/Homo_sapiens/Gene/Summary?db=core;g=ENSG00000197122;r=20:35973088-36034453</a></p>
</div>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://jp.youtube.com/watch?v=RgSC-mii7Q8" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://jp.youtube.com/watch?v=RgSC-mii7Q8" /></a> <a href="http://togotv.dbcls.jp/20090129.html" rel="nofollow">Ensemblゲノムブラウザを使って遺伝子を眺める2009</a></li>
<li>【発展B3】<a href="http://ensemblgenomes.org/" rel="nofollow">Ensembl Genomes</a>にはさらに多くの生物種のゲノム情報が同じインターフェースで統合されている。生物種によって収録されている情報はさまざまである。上部の'Species'のリンクから検索ページを表示し、<strong>Drosophila</strong>で検索し、各speciesでどの程度情報が利用可能となっているか調べなさい。その後、カイコ(<em>Bombyx mori</em>)のものと比較しなさい。</li></ul></li></ul>

<h3 id="content_1_5"><a id="nd0eeaab" href=""title="nd0eeaab"><span class="sanchor">_</span></a> ゲノム配列が解読された生物種を調べる  </h3>

<h3 id="content_1_6"><a id="f123c46d" href=""title="f123c46d">_</a> GOLD  </h3>
<blockquote><p class="quotation"><strong>GOLD genome</strong> でググる</p></blockquote>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A8】GOLDにアクセスし、ゲノム配列解読プロジェクトが完了し、Complete Genomeが得られている生物種の数を調べなさい。また、それらの Archaeal/Bacterial/Eukaryalの内訳も調べなさい。
<a name="plugin_fold_anchor7"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor7')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>2014年1月16日現在では、Complete Genome Projects: 12722 Archaeal: 317 Bacterial: 12093 Eukaryal: 312</p>
</div>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://youtu.be/quLYfmeeaZ8" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://youtu.be/quLYfmeeaZ8" /></a> <a href="http://togotv.dbcls.jp/20131029.html" rel="nofollow">GOLD -Genomes Online databaseを使い倒す 2013</a></li></ul></li></ul>

<h3 id="content_1_7"><a id="f40f03ce" href=""title="f40f03ce"><span class="sanchor">_</span></a> DBCLSのツールを使ってみる  </h3>
<p>DBCLSではこれらのゲノムデータに対して素早く快適に検索ができるよう技術開発を行っております。その成果でできたツールを簡単に紹介します。</p>

<h3 id="content_1_8"><a id="u57e6556" href=""title="u57e6556">_</a> GGRNA  </h3>
<p>遺伝子名や断片配列（塩基配列やアミノ酸配列）で<span class="noexists">RefSeq<a href="http://MotDB.DBCLS.jp/?cmd=edit&amp;page=RefSeq&amp;refer=AJACS44%2Fbono">?</a></span>を検索できるサイト。DBCLS謹製。</p>
<blockquote><p class="quotation"><a href="http://GGRNA.dbcls.jp/" rel="nofollow">http://GGRNA.dbcls.jp/</a></p></blockquote>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A9】GGRNAを使って、PEST配列を含む予測アミノ酸配列の数をヒトで調べなさい。マウスだといくつか?
<a name="plugin_fold_anchor8"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor8')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>762こ。<a href="http://ggrna.dbcls.jp/ja/hs/aa%3aPEST" rel="nofollow">http://ggrna.dbcls.jp/ja/hs/aa%3aPEST</a> マウスでは247こ。 <a href="http://ggrna.dbcls.jp/ja/mm/aa%3aPEST" rel="nofollow">http://ggrna.dbcls.jp/ja/mm/aa%3aPEST</a></p>
</div>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://www.youtube.com/watch?v=E-k114Gts0c" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://www.youtube.com/watch?v=E-k114Gts0c" /></a> <a href="http://togotv.dbcls.jp/20120124.html" rel="nofollow">GGRNAで遺伝子をGoogleのように検索する</a></li></ul></li></ul>

<h3 id="content_1_9"><a id="k5b7a41a" href=""title="k5b7a41a">_</a> GGGenome  </h3>
<p>塩基配列を高速に検索することができるツール。代表的なモデル生物のゲノムまたは転写産物のデータベースを対象に検索可能。DBCLS謹製。</p>
<blockquote><p class="quotation"><a href="http://GGGenome.dbcls.jp/" rel="nofollow">http://GGGenome.dbcls.jp/</a></p></blockquote>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A10】GGGenomeを使って、ヒトゲノム中で、塩基配列<strong>AGGTCAAAATGACCT</strong>が完全マッチする箇所は何箇所あるか調べなさい。またその検索に要した時間は何秒ほどか?
<a name="plugin_fold_anchor9"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor9')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>11+5=16箇所。<a href="http://gggenome.dbcls.jp/ja/hg19/AGGTCAAAATGACCT" rel="nofollow">http://gggenome.dbcls.jp/ja/hg19/AGGTCAAAATGACCT</a></p>
</div>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>さらに1baseミスマッチを許すと、その数はどうなるか?
<a name="plugin_fold_anchor10"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor10')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>400+386=786箇所。<a href="http://gggenome.dbcls.jp/ja/hg19/1/AGGTCAAAATGACCT" rel="nofollow">http://gggenome.dbcls.jp/ja/hg19/1/AGGTCAAAATGACCT</a></p>
</div></li>
<li>さらにさらに2baseミスマッチを許すと、その数はどうなるか?検索時間の変化も留意せよ。
<a name="plugin_fold_anchor11"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor11')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>13827+13998=27825箇所。<a href="http://gggenome.dbcls.jp/ja/hg19/2/AGGTCAAAATGACCT" rel="nofollow">http://gggenome.dbcls.jp/ja/hg19/2/AGGTCAAAATGACCT</a></p>
</div></li>
<li>【発展B4】上記と同様の検索をC.elegansゲノムを対象に検索してみなさい。また、それ以外の生物種も試してみなさい。
<ul class="list3" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://youtu.be/CyjR8WzR3Q8" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://youtu.be/CyjR8WzR3Q8" /></a> <a href="http://togotv.dbcls.jp/20131025.html" rel="nofollow">高速配列検索 GGGenome《ゲゲゲノム》の使い方</a></li></ul></li></ul></li></ul>
# AJACS44/bono


<p><span style="font-size:36px;display:inline-block;line-height:130%;text-indent:0px">ゲノム情報を閲覧・取得し、活用する</span></p>
<p>講習では【実習】を皆さんとやっていきます。早くできてしまった人は、統合TV<a href="http://togotv.dbcls.jp/" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://togotv.dbcls.jp/" /></a>(←このアイコンが目印です) を参考に【発展】をやってみたりしてください。</p>
<hr class="full_hr" />
<p>目次</p>
<div class="contents">
<a id="contents_1"></a>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li><a href="#af072cf3">  ウイルスが宿主のゲノムに取り込まれているのを調べる </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#a33e5940">  NCBI </a></li>
<li><a href="#lb2f4ecc">  UCSC Genome Browser+BLAT </a></li></ul></li>
<li><a href="#o641919a">  ウイルスの宿主のゲノムに付与されたアノテーションをゲノムブラウザ上で調べる </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#t3e2b7d7">  Ensembl Genome Browser </a></li></ul></li>
<li><a href="#nd0eeaab">  ゲノム配列が解読された生物種を調べる </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#f123c46d">  GOLD </a></li></ul></li>
<li><a href="#f40f03ce">  DBCLSのツールを使ってみる </a>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li><a href="#u57e6556">  GGRNA </a></li>
<li><a href="#k5b7a41a">  GGGenome </a></li></ul></li></ul>
</div>

<hr class="full_hr" />
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習0】このコマの講師、<strong>坊農秀雅</strong>でググりなさい。何件ヒットがありますか？
<a name="plugin_fold_anchor1"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor1')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>覗かないでね。;-p</p>
</div></li></ul>
<h3 id="content_1_0"><a id="af072cf3" href=""title="af072cf3"><span class="sanchor">_</span></a> ウイルスが宿主のゲノムに取り込まれているのを調べる  </h3>

<h3 id="content_1_1"><a id="a33e5940" href=""title="a33e5940">_</a> NCBI  </h3>
<p>National Center for Biotechnology Information. NIHの研究機関の一つで、生命科学系のデータベースの総本山。<strong>NCBI</strong> でググればトップに出てきます。</p>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A1】NCBI ラウス肉腫ウイルスのエントリを表示しなさい。
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>まずは、<a href="http://biosciencedbc.jp/dbsearch/" rel="nofollow">生命科学DB横断検索</a>を用いて「ラウス肉腫ウイルス」の英語名を調べましょう。</li>
<li>それを検索語として、NCBIで検索してみると…。
<a name="plugin_fold_anchor2"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor2')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p><a href="http://www.ncbi.nlm.nih.gov/Taxonomy/Browser/wwwtax.cgi?mode=Info&amp;id=11886&amp;lvl=3&amp;lin=f&amp;keep=1&amp;srchmode=1&amp;unlock" rel="nofollow">http://www.ncbi.nlm.nih.gov/Taxonomy/Browser/wwwtax.cgi?mode=Info&amp;id=11886&amp;lvl=3&amp;lin=f&amp;keep=1&amp;srchmode=1&amp;unlock</a></p>
</div></li>
<li>【発展B1】NCBI Taxonomy Browserを使って、インフルエンザウイルスを検索しなさい。
<ul class="list3" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://www.youtube.com/watch?v=QDxVUCHKOaE" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://www.youtube.com/watch?v=QDxVUCHKOaE" /></a> <a href="http://togotv.dbcls.jp/20090226.html" rel="nofollow">NCBI Taxonomy Browserを使って、生物分類と配列情報を関連させて調べる</a></li></ul></li></ul></li></ul>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A2】右上の'Genome'の'1'をクリックすると、このウイルスのゲノム配列情報のページに飛ぶことができる。ゲノムサイズ、GC含量、遺伝子数を確認しなさい。
<a name="plugin_fold_anchor3"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor3')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>ゲノムサイズ: 9.39kb、GC含量: 54.1%、遺伝子数: 4</p>
</div></li></ul>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A3】さらに'Graphics'をクリックするとどういった情報が得られるでしょうか?
<a name="plugin_fold_anchor4"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor4')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>ウイルスゲノム配列にコードされた遺伝子がグラフィカルに表示される（ゲノムブラウザ）</p>
</div></li></ul>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A4】Taxonomy Browserのラウス肉腫ウイルスのエントリに戻り、右上の'Nucleotide'の数字をクリックし、ラウス肉腫ウイルスの核酸配列として登録されたレコードを閲覧しなさい。そして、上部の検索フォームに検索後'src'を追加することで絞り込み検索をかけ、v-src遺伝子の完全長配列(complete cds)を表示しなさい。
<a name="plugin_fold_anchor5"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor5')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p><a href="http://www.ncbi.nlm.nih.gov/nuccore/M33292.1" rel="nofollow">http://www.ncbi.nlm.nih.gov/nuccore/M33292.1</a></p>
</div></li></ul>

<h3 id="content_1_2"><a id="lb2f4ecc" href=""title="lb2f4ecc">_</a> UCSC Genome Browser+BLAT  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A5】得たv-src遺伝子の塩基配列を宿主のニワトリのゲノムに<a href="http://genome.ucsc.edu/cgi-bin/hgBlat?command=start" rel="nofollow">BLAT検索</a>しなさい。その結果'details'をクリックすることで得た詳細検索結果を精査することで宿主から持ちだした配列のどの部分に変異が入ったか、確認しなさい。
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>参考:  <a href="http://www.youtube.com/watch?v=uMwhJQZoyfE" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://www.youtube.com/watch?v=uMwhJQZoyfE" /></a> <a href="http://togotv.dbcls.jp/20121030.html" rel="nofollow">ウイルスの持ち出した宿主の遺伝子配列がコードされている領域をアミノ酸配列レベルでゲノム中から探し当てる 2012</a></li></ul></li></ul>

<h3 id="content_1_3"><a id="o641919a" href=""title="o641919a"><span class="sanchor">_</span></a> ウイルスの宿主のゲノムに付与されたアノテーションをゲノムブラウザ上で調べる  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A6】BLAT検索結果の'browser'をクリックすると、検索配列がヒットしたゲノム領域にジャンプすることができる。出てきたページはゲノムブラウザと呼ばれ、ゲノム配列上のさまざまなアノテーションが「統合」されているツールである。
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>上部のzoom inで'10x'ボタンを押して遺伝子コード領域を拡大してみなさい。</li>
<li>下部のTrackにおいて、'Restr Enzymes'(制限酵素の意味)で'full'を選択し、refreshボタンを押しなさい。ゲノムブラウザにどういった情報が付加されましたか?
<ul class="list3" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://youtu.be/AleaXJKHuiY" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://youtu.be/AleaXJKHuiY" /></a> <a href="http://togotv.dbcls.jp/20120528.html" rel="nofollow"> UCSC Genome Browserの使い方～表示+ENCODE編～ 2012</a></li></ul></li>
<li>【発展B2】 UCSC Genome Browserを使って、今見ている領域のDNA配列を取得しなさい。
<ul class="list3" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://youtu.be/JvrE_YtM8z0" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://youtu.be/JvrE_YtM8z0" /></a> <a href="http://togotv.dbcls.jp/20131113.html" rel="nofollow">UCSC Genome Browserの使い方～配列取得編～ 2013</a></li></ul></li></ul></li></ul>

<h3 id="content_1_4"><a id="t3e2b7d7" href=""title="t3e2b7d7">_</a> Ensembl Genome Browser  </h3>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A7】同様のゲノムブラウザとしてよく使われているものに<a href="http://ensembl.org/" rel="nofollow">Ensembl</a>（アンサンブル）がある。ヒトを中心に出芽酵母までのゲノムとそのアノテーションが閲覧できる。EnsemblでヒトSRC遺伝子を検索し、ゲノムブラウザ上でその領域を表示しなさい。さらに、zoom out機能を使い、SRC遺伝子コード領域の周りを表示しなさい。
<a name="plugin_fold_anchor6"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor6')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p><a href="http://asia.ensembl.org/Homo_sapiens/Gene/Summary?db=core;g=ENSG00000197122;r=20:35973088-36034453" rel="nofollow">http://asia.ensembl.org/Homo_sapiens/Gene/Summary?db=core;g=ENSG00000197122;r=20:35973088-36034453</a></p>
</div>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://jp.youtube.com/watch?v=RgSC-mii7Q8" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://jp.youtube.com/watch?v=RgSC-mii7Q8" /></a> <a href="http://togotv.dbcls.jp/20090129.html" rel="nofollow">Ensemblゲノムブラウザを使って遺伝子を眺める2009</a></li>
<li>【発展B3】<a href="http://ensemblgenomes.org/" rel="nofollow">Ensembl Genomes</a>にはさらに多くの生物種のゲノム情報が同じインターフェースで統合されている。生物種によって収録されている情報はさまざまである。上部の'Species'のリンクから検索ページを表示し、<strong>Drosophila</strong>で検索し、各speciesでどの程度情報が利用可能となっているか調べなさい。その後、カイコ(<em>Bombyx mori</em>)のものと比較しなさい。</li></ul></li></ul>

<h3 id="content_1_5"><a id="nd0eeaab" href=""title="nd0eeaab"><span class="sanchor">_</span></a> ゲノム配列が解読された生物種を調べる  </h3>

<h3 id="content_1_6"><a id="f123c46d" href=""title="f123c46d">_</a> GOLD  </h3>
<blockquote><p class="quotation"><strong>GOLD genome</strong> でググる</p></blockquote>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A8】GOLDにアクセスし、ゲノム配列解読プロジェクトが完了し、Complete Genomeが得られている生物種の数を調べなさい。また、それらの Archaeal/Bacterial/Eukaryalの内訳も調べなさい。
<a name="plugin_fold_anchor7"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor7')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>2014年1月16日現在では、Complete Genome Projects: 12722 Archaeal: 317 Bacterial: 12093 Eukaryal: 312</p>
</div>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://youtu.be/quLYfmeeaZ8" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://youtu.be/quLYfmeeaZ8" /></a> <a href="http://togotv.dbcls.jp/20131029.html" rel="nofollow">GOLD -Genomes Online databaseを使い倒す 2013</a></li></ul></li></ul>

<h3 id="content_1_7"><a id="f40f03ce" href=""title="f40f03ce"><span class="sanchor">_</span></a> DBCLSのツールを使ってみる  </h3>
<p>DBCLSではこれらのゲノムデータに対して素早く快適に検索ができるよう技術開発を行っております。その成果でできたツールを簡単に紹介します。</p>

<h3 id="content_1_8"><a id="u57e6556" href=""title="u57e6556">_</a> GGRNA  </h3>
<p>遺伝子名や断片配列（塩基配列やアミノ酸配列）で<span class="noexists">RefSeq<a href="http://MotDB.DBCLS.jp/?cmd=edit&amp;page=RefSeq&amp;refer=AJACS44%2Fbono">?</a></span>を検索できるサイト。DBCLS謹製。</p>
<blockquote><p class="quotation"><a href="http://GGRNA.dbcls.jp/" rel="nofollow">http://GGRNA.dbcls.jp/</a></p></blockquote>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A9】GGRNAを使って、PEST配列を含む予測アミノ酸配列の数をヒトで調べなさい。マウスだといくつか?
<a name="plugin_fold_anchor8"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor8')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>762こ。<a href="http://ggrna.dbcls.jp/ja/hs/aa%3aPEST" rel="nofollow">http://ggrna.dbcls.jp/ja/hs/aa%3aPEST</a> マウスでは247こ。 <a href="http://ggrna.dbcls.jp/ja/mm/aa%3aPEST" rel="nofollow">http://ggrna.dbcls.jp/ja/mm/aa%3aPEST</a></p>
</div>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://www.youtube.com/watch?v=E-k114Gts0c" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://www.youtube.com/watch?v=E-k114Gts0c" /></a> <a href="http://togotv.dbcls.jp/20120124.html" rel="nofollow">GGRNAで遺伝子をGoogleのように検索する</a></li></ul></li></ul>

<h3 id="content_1_9"><a id="k5b7a41a" href=""title="k5b7a41a">_</a> GGGenome  </h3>
<p>塩基配列を高速に検索することができるツール。代表的なモデル生物のゲノムまたは転写産物のデータベースを対象に検索可能。DBCLS謹製。</p>
<blockquote><p class="quotation"><a href="http://GGGenome.dbcls.jp/" rel="nofollow">http://GGGenome.dbcls.jp/</a></p></blockquote>
<ul class="list1" style="padding-left:16px;margin-left:16px"><li>【実習A10】GGGenomeを使って、ヒトゲノム中で、塩基配列<strong>AGGTCAAAATGACCT</strong>が完全マッチする箇所は何箇所あるか調べなさい。またその検索に要した時間は何秒ほどか?
<a name="plugin_fold_anchor9"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor9')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>11+5=16箇所。<a href="http://gggenome.dbcls.jp/ja/hg19/AGGTCAAAATGACCT" rel="nofollow">http://gggenome.dbcls.jp/ja/hg19/AGGTCAAAATGACCT</a></p>
</div>
<ul class="list2" style="padding-left:16px;margin-left:16px"><li>さらに1baseミスマッチを許すと、その数はどうなるか?
<a name="plugin_fold_anchor10"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor10')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>400+386=786箇所。<a href="http://gggenome.dbcls.jp/ja/hg19/1/AGGTCAAAATGACCT" rel="nofollow">http://gggenome.dbcls.jp/ja/hg19/1/AGGTCAAAATGACCT</a></p>
</div></li>
<li>さらにさらに2baseミスマッチを許すと、その数はどうなるか?検索時間の変化も留意せよ。
<a name="plugin_fold_anchor11"></a>
<div class="plugin_fold_title_plus" onclick="return plugin_fold_onclick(this,event,'plugin_fold_anchor11')"><p>←こたえは左の+マークをクリックすると出てきます</p>
</div>
<div class="plugin_fold_body"><p>13827+13998=27825箇所。<a href="http://gggenome.dbcls.jp/ja/hg19/2/AGGTCAAAATGACCT" rel="nofollow">http://gggenome.dbcls.jp/ja/hg19/2/AGGTCAAAATGACCT</a></p>
</div></li>
<li>【発展B4】上記と同様の検索をC.elegansゲノムを対象に検索してみなさい。また、それ以外の生物種も試してみなさい。
<ul class="list3" style="padding-left:16px;margin-left:16px"><li>参考: <a href="http://youtu.be/CyjR8WzR3Q8" rel="nofollow"><img src="http://dbcls.rois.ac.jp/~bono/images/togotv-s.png" alt="http://youtu.be/CyjR8WzR3Q8" /></a> <a href="http://togotv.dbcls.jp/20131025.html" rel="nofollow">高速配列検索 GGGenome《ゲゲゲノム》の使い方</a></li></ul></li></ul></li></ul>
