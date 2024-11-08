## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[12] NotoSerifAhom-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that texts shape as per expectation <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/ahom.json: Expected and actual shaping not matching</p>
<ul>
<li>
<p>Shaping did not match: 𑜃𑜢𑜤 (notofonts/noto-fonts#1372)</p>
<pre><code>Expected: na_ahom=0+879|iSign_ahom=0@-231,0+0|uSign_ahom=0@-234,0+0
Got     : na_ahom=0+879|iSign_ahom=0@-431,200+0|uSign_ahom=0@-234,0+0
                                      ^
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -675 879 1843" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g9" d="M481.0,-24.0Q462.0,-24.0 450.0,-18.0Q438.0,-12.0 438.0,1.0L438.0,156.0L261.0,44.0Q247.0,35.0 225.0,22.5Q203.0,10.0 182.0,0.0Q161.0,-10.0 148.0,-10.0Q132.0,-10.0 126.0,-2.0Q120.0,6.0 120.0,19.0L120.0,525.0Q120.0,539.0 135.0,544.5Q150.0,550.0 166.0,550.0Q184.0,550.0 197.0,544.0Q210.0,538.0 210.0,525.0L210.0,425.0Q248.0,457.0 293.5,488.0Q339.0,519.0 382.0,539.5Q425.0,560.0 456.0,560.0Q503.0,560.0 525.5,537.0Q548.0,514.0 548.0,476.0Q548.0,435.0 530.5,417.0Q513.0,399.0 487.0,399.0Q462.0,399.0 450.5,411.0Q439.0,423.0 435.0,436.0Q431.0,450.0 424.0,460.5Q417.0,471.0 392.0,471.0Q375.0,471.0 342.5,454.5Q310.0,438.0 274.5,413.0Q239.0,388.0 210.0,362.0L210.0,81.0L424.0,214.0Q444.0,227.0 464.5,237.5Q485.0,248.0 498.0,248.0Q513.0,248.0 520.5,236.5Q528.0,225.0 528.0,213.0L528.0,1.0Q528.0,-12.0 515.5,-18.0Q503.0,-24.0 481.0,-24.0Z"/> <path id="g43" d="M33.0,490.0Q-24.0,490.0 -62.0,541.0Q-100.0,592.0 -100.0,701.0Q-100.0,741.0 -86.5,787.0Q-73.0,833.0 -47.5,874.5Q-22.0,916.0 14.5,942.0Q51.0,968.0 98.0,968.0Q142.0,968.0 171.5,941.5Q201.0,915.0 216.0,870.0Q231.0,825.0 231.0,770.0Q231.0,685.0 201.5,622.0Q172.0,559.0 126.5,524.5Q81.0,490.0 33.0,490.0ZM53.0,554.0Q94.0,554.0 114.5,584.5Q135.0,615.0 142.0,664.5Q149.0,714.0 149.0,772.0Q149.0,806.0 144.0,836.0Q139.0,866.0 124.5,885.0Q110.0,904.0 83.0,904.0Q56.0,904.0 33.0,886.0Q10.0,868.0 -4.0,821.5Q-18.0,775.0 -18.0,691.0Q-18.0,628.0 0.5,591.0Q19.0,554.0 53.0,554.0Z"/> <path id="g45" d="M-7.0,-330.0Q-41.0,-330.0 -77.0,-322.0Q-113.0,-314.0 -143.0,-292.5Q-173.0,-271.0 -191.5,-232.5Q-210.0,-194.0 -210.0,-134.0L-210.0,-95.0Q-210.0,-82.0 -196.0,-76.0Q-182.0,-70.0 -165.0,-70.0Q-148.0,-70.0 -134.0,-76.0Q-120.0,-82.0 -120.0,-95.0L-120.0,-130.0Q-120.0,-185.0 -107.0,-215.0Q-94.0,-245.0 -70.5,-256.5Q-47.0,-268.0 -16.0,-268.0Q17.0,-268.0 43.0,-263.0Q69.0,-258.0 97.0,-245.0Q103.0,-242.0 111.0,-242.0Q124.0,-242.0 132.0,-248.0Q140.0,-254.0 140.0,-265.0Q140.0,-280.0 124.5,-292.0Q109.0,-304.0 85.0,-312.5Q61.0,-321.0 36.0,-325.5Q11.0,-330.0 -7.0,-330.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g9"/> </g> <g transform="translate(448,200)"> <use href="#g43"/> </g> <g transform="translate(645,0)"> <use href="#g45"/> </g> </svg>  Expected: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -675 879 1655" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g9" d="M481.0,-24.0Q462.0,-24.0 450.0,-18.0Q438.0,-12.0 438.0,1.0L438.0,156.0L261.0,44.0Q247.0,35.0 225.0,22.5Q203.0,10.0 182.0,0.0Q161.0,-10.0 148.0,-10.0Q132.0,-10.0 126.0,-2.0Q120.0,6.0 120.0,19.0L120.0,525.0Q120.0,539.0 135.0,544.5Q150.0,550.0 166.0,550.0Q184.0,550.0 197.0,544.0Q210.0,538.0 210.0,525.0L210.0,425.0Q248.0,457.0 293.5,488.0Q339.0,519.0 382.0,539.5Q425.0,560.0 456.0,560.0Q503.0,560.0 525.5,537.0Q548.0,514.0 548.0,476.0Q548.0,435.0 530.5,417.0Q513.0,399.0 487.0,399.0Q462.0,399.0 450.5,411.0Q439.0,423.0 435.0,436.0Q431.0,450.0 424.0,460.5Q417.0,471.0 392.0,471.0Q375.0,471.0 342.5,454.5Q310.0,438.0 274.5,413.0Q239.0,388.0 210.0,362.0L210.0,81.0L424.0,214.0Q444.0,227.0 464.5,237.5Q485.0,248.0 498.0,248.0Q513.0,248.0 520.5,236.5Q528.0,225.0 528.0,213.0L528.0,1.0Q528.0,-12.0 515.5,-18.0Q503.0,-24.0 481.0,-24.0Z"/> <path id="g43" d="M33.0,490.0Q-24.0,490.0 -62.0,541.0Q-100.0,592.0 -100.0,701.0Q-100.0,741.0 -86.5,787.0Q-73.0,833.0 -47.5,874.5Q-22.0,916.0 14.5,942.0Q51.0,968.0 98.0,968.0Q142.0,968.0 171.5,941.5Q201.0,915.0 216.0,870.0Q231.0,825.0 231.0,770.0Q231.0,685.0 201.5,622.0Q172.0,559.0 126.5,524.5Q81.0,490.0 33.0,490.0ZM53.0,554.0Q94.0,554.0 114.5,584.5Q135.0,615.0 142.0,664.5Q149.0,714.0 149.0,772.0Q149.0,806.0 144.0,836.0Q139.0,866.0 124.5,885.0Q110.0,904.0 83.0,904.0Q56.0,904.0 33.0,886.0Q10.0,868.0 -4.0,821.5Q-18.0,775.0 -18.0,691.0Q-18.0,628.0 0.5,591.0Q19.0,554.0 53.0,554.0Z"/> <path id="g45" d="M-7.0,-330.0Q-41.0,-330.0 -77.0,-322.0Q-113.0,-314.0 -143.0,-292.5Q-173.0,-271.0 -191.5,-232.5Q-210.0,-194.0 -210.0,-134.0L-210.0,-95.0Q-210.0,-82.0 -196.0,-76.0Q-182.0,-70.0 -165.0,-70.0Q-148.0,-70.0 -134.0,-76.0Q-120.0,-82.0 -120.0,-95.0L-120.0,-130.0Q-120.0,-185.0 -107.0,-215.0Q-94.0,-245.0 -70.5,-256.5Q-47.0,-268.0 -16.0,-268.0Q17.0,-268.0 43.0,-263.0Q69.0,-258.0 97.0,-245.0Q103.0,-242.0 111.0,-242.0Q124.0,-242.0 132.0,-248.0Q140.0,-254.0 140.0,-265.0Q140.0,-280.0 124.5,-292.0Q109.0,-304.0 85.0,-312.5Q61.0,-321.0 36.0,-325.5Q11.0,-330.0 -7.0,-330.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g9"/> </g> <g transform="translate(648,0)"> <use href="#g43"/> </g> <g transform="translate(645,0)"> <use href="#g45"/> </g> </svg></p>
</li>
<li>
<p>Shaping did not match: 𑜃𑜡 𑜃𑜝𑜡 (#1)</p>
<pre><code>Expected: na_ahom=0+718|aaSign_ahom=0+264|space=2+220|na_ahom=3+718|medialLa_ahom.sm=3@-38,0+0|aaSign_ahom=3+264
Got     : na_ahom=0+788|aaSign_ahom=0+264|space=2+220|na_ahom=3+788|medialLa_ahom.sm=3@-108,0+0|aaSign_ahom=3+264
                     ^                                           ^                      ^
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -675 2474 1655" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g9" d="M481.0,-24.0Q462.0,-24.0 450.0,-18.0Q438.0,-12.0 438.0,1.0L438.0,156.0L261.0,44.0Q247.0,35.0 225.0,22.5Q203.0,10.0 182.0,0.0Q161.0,-10.0 148.0,-10.0Q132.0,-10.0 126.0,-2.0Q120.0,6.0 120.0,19.0L120.0,525.0Q120.0,539.0 135.0,544.5Q150.0,550.0 166.0,550.0Q184.0,550.0 197.0,544.0Q210.0,538.0 210.0,525.0L210.0,425.0Q248.0,457.0 293.5,488.0Q339.0,519.0 382.0,539.5Q425.0,560.0 456.0,560.0Q503.0,560.0 525.5,537.0Q548.0,514.0 548.0,476.0Q548.0,435.0 530.5,417.0Q513.0,399.0 487.0,399.0Q462.0,399.0 450.5,411.0Q439.0,423.0 435.0,436.0Q431.0,450.0 424.0,460.5Q417.0,471.0 392.0,471.0Q375.0,471.0 342.5,454.5Q310.0,438.0 274.5,413.0Q239.0,388.0 210.0,362.0L210.0,81.0L424.0,214.0Q444.0,227.0 464.5,237.5Q485.0,248.0 498.0,248.0Q513.0,248.0 520.5,236.5Q528.0,225.0 528.0,213.0L528.0,1.0Q528.0,-12.0 515.5,-18.0Q503.0,-24.0 481.0,-24.0Z"/> <path id="g42" d="M267.0,-240.0Q167.0,-240.0 115.5,-187.0Q64.0,-134.0 64.0,-34.0L64.0,349.0Q64.0,404.0 54.0,431.0Q44.0,458.0 23.0,467.5Q2.0,477.0 -32.0,477.0Q-50.0,477.0 -65.0,485.5Q-80.0,494.0 -80.0,514.0Q-80.0,560.0 -29.0,560.0Q57.0,560.0 105.5,514.0Q154.0,468.0 154.0,370.0L154.0,-30.0Q154.0,-113.0 183.0,-145.5Q212.0,-178.0 258.0,-178.0Q291.0,-178.0 317.0,-173.0Q343.0,-168.0 371.0,-155.0Q377.0,-152.0 385.0,-152.0Q398.0,-152.0 406.0,-158.0Q414.0,-164.0 414.0,-175.0Q414.0,-190.0 398.5,-202.0Q383.0,-214.0 359.0,-222.5Q335.0,-231.0 310.0,-235.5Q285.0,-240.0 267.0,-240.0Z"/> <path id="g3" d=""/> <path id="g36" d="M-381.0,-303.0Q-449.0,-303.0 -499.0,-282.0Q-549.0,-261.0 -582.0,-230.5Q-615.0,-200.0 -631.0,-172.0Q-647.0,-144.0 -647.0,-129.0Q-647.0,-117.0 -641.0,-106.5Q-635.0,-96.0 -616.0,-96.0Q-603.0,-96.0 -594.5,-105.0Q-586.0,-114.0 -579.0,-125.0Q-565.0,-145.0 -543.0,-168.5Q-521.0,-192.0 -483.0,-209.0Q-445.0,-226.0 -383.0,-226.0Q-349.0,-226.0 -313.5,-215.5Q-278.0,-205.0 -249.0,-177.0Q-220.0,-149.0 -207.0,-98.0Q-203.0,-84.0 -189.5,-77.0Q-176.0,-70.0 -162.0,-70.0Q-144.0,-70.0 -133.0,-77.0Q-122.0,-84.0 -122.0,-98.0Q-122.0,-112.0 -130.0,-139.5Q-138.0,-167.0 -152.0,-187.0Q-192.0,-248.0 -252.5,-275.5Q-313.0,-303.0 -381.0,-303.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g9"/> </g> <g transform="translate(788,0)"> <use href="#g42"/> </g> <g transform="translate(1052,0)"> <use href="#g3"/> </g> <g transform="translate(1272,0)"> <use href="#g9"/> </g> <g transform="translate(1952,0)"> <use href="#g36"/> </g> <g transform="translate(2060,0)"> <use href="#g42"/> </g> </svg>  Expected: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -675 2334 1655" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g9" d="M481.0,-24.0Q462.0,-24.0 450.0,-18.0Q438.0,-12.0 438.0,1.0L438.0,156.0L261.0,44.0Q247.0,35.0 225.0,22.5Q203.0,10.0 182.0,0.0Q161.0,-10.0 148.0,-10.0Q132.0,-10.0 126.0,-2.0Q120.0,6.0 120.0,19.0L120.0,525.0Q120.0,539.0 135.0,544.5Q150.0,550.0 166.0,550.0Q184.0,550.0 197.0,544.0Q210.0,538.0 210.0,525.0L210.0,425.0Q248.0,457.0 293.5,488.0Q339.0,519.0 382.0,539.5Q425.0,560.0 456.0,560.0Q503.0,560.0 525.5,537.0Q548.0,514.0 548.0,476.0Q548.0,435.0 530.5,417.0Q513.0,399.0 487.0,399.0Q462.0,399.0 450.5,411.0Q439.0,423.0 435.0,436.0Q431.0,450.0 424.0,460.5Q417.0,471.0 392.0,471.0Q375.0,471.0 342.5,454.5Q310.0,438.0 274.5,413.0Q239.0,388.0 210.0,362.0L210.0,81.0L424.0,214.0Q444.0,227.0 464.5,237.5Q485.0,248.0 498.0,248.0Q513.0,248.0 520.5,236.5Q528.0,225.0 528.0,213.0L528.0,1.0Q528.0,-12.0 515.5,-18.0Q503.0,-24.0 481.0,-24.0Z"/> <path id="g42" d="M267.0,-240.0Q167.0,-240.0 115.5,-187.0Q64.0,-134.0 64.0,-34.0L64.0,349.0Q64.0,404.0 54.0,431.0Q44.0,458.0 23.0,467.5Q2.0,477.0 -32.0,477.0Q-50.0,477.0 -65.0,485.5Q-80.0,494.0 -80.0,514.0Q-80.0,560.0 -29.0,560.0Q57.0,560.0 105.5,514.0Q154.0,468.0 154.0,370.0L154.0,-30.0Q154.0,-113.0 183.0,-145.5Q212.0,-178.0 258.0,-178.0Q291.0,-178.0 317.0,-173.0Q343.0,-168.0 371.0,-155.0Q377.0,-152.0 385.0,-152.0Q398.0,-152.0 406.0,-158.0Q414.0,-164.0 414.0,-175.0Q414.0,-190.0 398.5,-202.0Q383.0,-214.0 359.0,-222.5Q335.0,-231.0 310.0,-235.5Q285.0,-240.0 267.0,-240.0Z"/> <path id="g3" d=""/> <path id="g36" d="M-381.0,-303.0Q-449.0,-303.0 -499.0,-282.0Q-549.0,-261.0 -582.0,-230.5Q-615.0,-200.0 -631.0,-172.0Q-647.0,-144.0 -647.0,-129.0Q-647.0,-117.0 -641.0,-106.5Q-635.0,-96.0 -616.0,-96.0Q-603.0,-96.0 -594.5,-105.0Q-586.0,-114.0 -579.0,-125.0Q-565.0,-145.0 -543.0,-168.5Q-521.0,-192.0 -483.0,-209.0Q-445.0,-226.0 -383.0,-226.0Q-349.0,-226.0 -313.5,-215.5Q-278.0,-205.0 -249.0,-177.0Q-220.0,-149.0 -207.0,-98.0Q-203.0,-84.0 -189.5,-77.0Q-176.0,-70.0 -162.0,-70.0Q-144.0,-70.0 -133.0,-77.0Q-122.0,-84.0 -122.0,-98.0Q-122.0,-112.0 -130.0,-139.5Q-138.0,-167.0 -152.0,-187.0Q-192.0,-248.0 -252.5,-275.5Q-313.0,-303.0 -381.0,-303.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g9"/> </g> <g transform="translate(718,0)"> <use href="#g42"/> </g> <g transform="translate(982,0)"> <use href="#g3"/> </g> <g transform="translate(1202,0)"> <use href="#g9"/> </g> <g transform="translate(1882,0)"> <use href="#g36"/> </g> <g transform="translate(1920,0)"> <use href="#g42"/> </g> </svg></p>
</li>
<li>
<p>Shaping did not match: 𑜅𑜞𑜊 𑜅𑜦𑜊 𑜅𑜝𑜊 𑜀𑜝 (#3)</p>
<pre><code>Expected: t_ja_ahom=0+992|medialRa_ahom.sm=0@-280,0+0|space=3+220|eSign_ahom=4+570|t_ja_ahom=4+1142|space=7+220|t_ja_ahom=8+1142|medialLa_ahom.sm=8@-167,0+0|space=11+220|ka_ahom=12+944|medialLa_ahom=12@16,0+0
Got     : t_ja_ahom=0+1142|medialRa_ahom.sm=0@-430,0+0|space=3+220|eSign_ahom=4+570|t_ja_ahom=4+1142|space=7+220|t_ja_ahom=8+1142|medialLa_ahom.sm=8@-167,0+0|space=11+220|ka_ahom=12+944|medialLa_ahom=12@16,0+0
                      ^^                      ^^
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="-178 -675 5794 1655" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g71" d="M213.0,-14.0Q173.0,-14.0 138.0,3.5Q103.0,21.0 81.5,61.0Q60.0,101.0 60.0,169.0Q60.0,242.0 83.0,312.0Q106.0,382.0 144.0,438.0Q182.0,494.0 227.0,527.0Q272.0,560.0 315.0,560.0Q375.0,560.0 410.0,527.5Q445.0,495.0 461.0,439.0Q477.0,383.0 479.0,313.0L484.0,180.0L556.0,428.0Q576.0,499.0 593.0,529.5Q610.0,560.0 629.0,560.0Q644.0,560.0 657.5,551.5Q671.0,543.0 682.5,516.5Q694.0,490.0 704.0,435.0L750.0,177.0Q763.0,104.0 779.0,76.0Q795.0,48.0 830.0,48.0Q872.0,48.0 907.0,86.0Q942.0,124.0 962.5,187.0Q983.0,250.0 983.0,324.0Q983.0,361.0 972.0,381.5Q961.0,402.0 943.5,413.0Q926.0,424.0 908.0,431.0Q878.0,444.0 864.5,464.0Q851.0,484.0 851.0,503.0Q851.0,528.0 867.5,544.0Q884.0,560.0 911.0,560.0Q947.0,560.0 981.5,539.0Q1016.0,518.0 1039.0,471.0Q1062.0,424.0 1062.0,345.0Q1062.0,269.0 1041.0,204.0Q1020.0,139.0 984.0,90.0Q948.0,41.0 903.5,13.5Q859.0,-14.0 812.0,-14.0Q757.0,-14.0 725.0,14.0Q693.0,42.0 677.5,87.0Q662.0,132.0 653.0,183.0L633.0,302.0Q628.0,334.0 623.5,354.0Q619.0,374.0 611.0,374.0Q605.0,374.0 596.0,349.5Q587.0,325.0 576.0,286.0Q565.0,247.0 554.0,205.0L514.0,54.0Q507.0,29.0 494.0,19.5Q481.0,10.0 471.0,10.0Q461.0,10.0 451.5,12.5Q442.0,15.0 434.5,27.0Q427.0,39.0 423.0,66.0L409.0,180.0Q396.0,130.0 371.0,85.5Q346.0,41.0 307.5,13.5Q269.0,-14.0 213.0,-14.0ZM234.0,68.0Q249.0,68.0 270.5,77.5Q292.0,87.0 315.0,113.5Q338.0,140.0 358.5,189.0Q379.0,238.0 393.0,317.0L393.0,347.0Q393.0,424.0 369.0,453.5Q345.0,483.0 309.0,483.0Q275.0,483.0 239.0,450.0Q203.0,417.0 178.5,353.0Q154.0,289.0 154.0,196.0Q154.0,142.0 172.5,105.0Q191.0,68.0 234.0,68.0Z"/> <path id="g38" d="M-455.0,-303.0Q-546.0,-303.0 -616.5,-272.0Q-687.0,-241.0 -738.5,-186.5Q-790.0,-132.0 -823.5,-61.5Q-857.0,9.0 -873.5,88.5Q-890.0,168.0 -890.0,249.0Q-890.0,363.0 -853.0,462.5Q-816.0,562.0 -750.0,638.0Q-684.0,714.0 -595.0,757.0Q-506.0,800.0 -402.0,800.0Q-315.0,800.0 -251.0,786.0Q-187.0,772.0 -144.0,752.0Q-122.0,742.0 -122.0,720.0Q-122.0,707.0 -130.5,700.0Q-139.0,693.0 -151.0,693.0Q-166.0,693.0 -184.0,700.0Q-209.0,709.0 -262.0,721.0Q-315.0,733.0 -410.0,733.0Q-488.0,733.0 -558.0,704.0Q-628.0,675.0 -681.5,615.5Q-735.0,556.0 -765.5,465.0Q-796.0,374.0 -796.0,251.0Q-796.0,184.0 -785.5,116.0Q-775.0,48.0 -752.0,-13.5Q-729.0,-75.0 -690.0,-123.0Q-651.0,-171.0 -593.5,-198.5Q-536.0,-226.0 -458.0,-226.0Q-419.0,-226.0 -374.0,-214.0Q-329.0,-202.0 -289.5,-173.5Q-250.0,-145.0 -228.0,-96.0Q-216.0,-70.0 -181.0,-70.0Q-137.0,-70.0 -137.0,-95.0Q-137.0,-116.0 -153.5,-144.0Q-170.0,-172.0 -190.0,-194.0Q-222.0,-228.0 -268.5,-252.5Q-315.0,-277.0 -364.0,-290.0Q-413.0,-303.0 -455.0,-303.0Z"/> <path id="g3" d=""/> <path id="g47" d="M295.0,-14.0Q280.0,-14.0 268.0,-6.5Q256.0,1.0 256.0,20.0Q256.0,31.0 260.0,40.0L361.0,316.0Q337.0,413.0 290.5,453.0Q244.0,493.0 188.0,493.0Q142.0,493.0 119.5,477.0Q97.0,461.0 97.0,447.0Q97.0,437.0 103.0,432.5Q109.0,428.0 118.0,425.0Q144.0,417.0 158.5,404.0Q173.0,391.0 173.0,366.0Q173.0,341.0 157.5,324.0Q142.0,307.0 110.0,307.0Q71.0,307.0 45.5,334.0Q20.0,361.0 20.0,409.0Q20.0,449.0 39.5,483.0Q59.0,517.0 97.5,538.5Q136.0,560.0 193.0,560.0Q264.0,560.0 317.5,521.5Q371.0,483.0 399.0,423.0L571.0,897.0Q579.0,918.0 589.0,926.0Q599.0,934.0 613.0,934.0Q628.0,934.0 639.0,925.0Q650.0,916.0 650.0,900.0Q650.0,890.0 646.0,877.5Q642.0,865.0 640.0,861.0L335.0,23.0Q328.0,2.0 318.5,-6.0Q309.0,-14.0 295.0,-14.0Z"/> <path id="g36" d="M-381.0,-303.0Q-449.0,-303.0 -499.0,-282.0Q-549.0,-261.0 -582.0,-230.5Q-615.0,-200.0 -631.0,-172.0Q-647.0,-144.0 -647.0,-129.0Q-647.0,-117.0 -641.0,-106.5Q-635.0,-96.0 -616.0,-96.0Q-603.0,-96.0 -594.5,-105.0Q-586.0,-114.0 -579.0,-125.0Q-565.0,-145.0 -543.0,-168.5Q-521.0,-192.0 -483.0,-209.0Q-445.0,-226.0 -383.0,-226.0Q-349.0,-226.0 -313.5,-215.5Q-278.0,-205.0 -249.0,-177.0Q-220.0,-149.0 -207.0,-98.0Q-203.0,-84.0 -189.5,-77.0Q-176.0,-70.0 -162.0,-70.0Q-144.0,-70.0 -133.0,-77.0Q-122.0,-84.0 -122.0,-98.0Q-122.0,-112.0 -130.0,-139.5Q-138.0,-167.0 -152.0,-187.0Q-192.0,-248.0 -252.5,-275.5Q-313.0,-303.0 -381.0,-303.0Z"/> <path id="g6" d="M180.0,-10.0Q164.0,-10.0 149.0,-4.0Q134.0,2.0 134.0,15.0L134.0,336.0Q134.0,392.0 106.5,426.0Q79.0,460.0 36.0,477.0Q20.0,483.0 20.0,499.0Q20.0,511.0 27.0,525.5Q34.0,540.0 45.0,550.0Q56.0,560.0 66.0,560.0Q96.0,560.0 124.5,540.0Q153.0,520.0 175.0,489.5Q197.0,459.0 206.0,427.0Q231.0,456.0 265.5,487.0Q300.0,518.0 338.0,539.0Q376.0,560.0 410.0,560.0Q436.0,560.0 458.5,550.5Q481.0,541.0 497.0,515.5Q513.0,490.0 520.0,442.0Q545.0,470.0 577.5,497.0Q610.0,524.0 644.5,542.0Q679.0,560.0 710.0,560.0Q741.0,560.0 767.0,546.0Q793.0,532.0 808.5,492.5Q824.0,453.0 824.0,377.0L824.0,15.0Q824.0,2.0 810.5,-4.0Q797.0,-10.0 781.0,-10.0Q763.0,-10.0 748.5,-4.0Q734.0,2.0 734.0,15.0L734.0,353.0Q734.0,424.0 720.0,451.0Q706.0,478.0 673.0,478.0Q655.0,478.0 629.5,462.0Q604.0,446.0 576.5,420.0Q549.0,394.0 524.0,362.0L524.0,15.0Q524.0,2.0 510.0,-4.0Q496.0,-10.0 479.0,-10.0Q462.0,-10.0 448.0,-4.0Q434.0,2.0 434.0,15.0L434.0,353.0Q434.0,424.0 420.0,451.0Q406.0,478.0 373.0,478.0Q355.0,478.0 329.0,462.0Q303.0,446.0 275.5,420.0Q248.0,394.0 223.0,362.0Q224.0,359.0 224.0,354.0L224.0,15.0Q224.0,2.0 211.0,-4.0Q198.0,-10.0 180.0,-10.0Z"/> <path id="g35" d="M-488.0,-303.0Q-567.0,-303.0 -631.5,-283.0Q-696.0,-263.0 -743.0,-233.5Q-790.0,-204.0 -815.5,-175.5Q-841.0,-147.0 -841.0,-129.0Q-841.0,-117.0 -835.0,-106.5Q-829.0,-96.0 -810.0,-96.0Q-805.0,-96.0 -797.0,-100.5Q-789.0,-105.0 -785.0,-109.0Q-758.0,-134.0 -717.5,-161.5Q-677.0,-189.0 -620.5,-207.5Q-564.0,-226.0 -488.0,-226.0Q-432.0,-226.0 -378.5,-212.0Q-325.0,-198.0 -284.0,-168.5Q-243.0,-139.0 -227.0,-93.0Q-222.0,-80.0 -207.5,-75.0Q-193.0,-70.0 -177.0,-70.0Q-160.0,-70.0 -148.5,-77.0Q-137.0,-84.0 -137.0,-95.0Q-138.0,-117.0 -147.0,-135.5Q-156.0,-154.0 -169.0,-171.0Q-202.0,-215.0 -252.5,-244.5Q-303.0,-274.0 -363.5,-288.5Q-424.0,-303.0 -488.0,-303.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g71"/> </g> <g transform="translate(712,0)"> <use href="#g38"/> </g> <g transform="translate(1142,0)"> <use href="#g3"/> </g> <g transform="translate(1362,0)"> <use href="#g47"/> </g> <g transform="translate(1932,0)"> <use href="#g71"/> </g> <g transform="translate(3074,0)"> <use href="#g3"/> </g> <g transform="translate(3294,0)"> <use href="#g71"/> </g> <g transform="translate(4269,0)"> <use href="#g36"/> </g> <g transform="translate(4436,0)"> <use href="#g3"/> </g> <g transform="translate(4656,0)"> <use href="#g6"/> </g> <g transform="translate(5616,0)"> <use href="#g35"/> </g> </svg>  Expected: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="-178 -675 5644 1655" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g71" d="M213.0,-14.0Q173.0,-14.0 138.0,3.5Q103.0,21.0 81.5,61.0Q60.0,101.0 60.0,169.0Q60.0,242.0 83.0,312.0Q106.0,382.0 144.0,438.0Q182.0,494.0 227.0,527.0Q272.0,560.0 315.0,560.0Q375.0,560.0 410.0,527.5Q445.0,495.0 461.0,439.0Q477.0,383.0 479.0,313.0L484.0,180.0L556.0,428.0Q576.0,499.0 593.0,529.5Q610.0,560.0 629.0,560.0Q644.0,560.0 657.5,551.5Q671.0,543.0 682.5,516.5Q694.0,490.0 704.0,435.0L750.0,177.0Q763.0,104.0 779.0,76.0Q795.0,48.0 830.0,48.0Q872.0,48.0 907.0,86.0Q942.0,124.0 962.5,187.0Q983.0,250.0 983.0,324.0Q983.0,361.0 972.0,381.5Q961.0,402.0 943.5,413.0Q926.0,424.0 908.0,431.0Q878.0,444.0 864.5,464.0Q851.0,484.0 851.0,503.0Q851.0,528.0 867.5,544.0Q884.0,560.0 911.0,560.0Q947.0,560.0 981.5,539.0Q1016.0,518.0 1039.0,471.0Q1062.0,424.0 1062.0,345.0Q1062.0,269.0 1041.0,204.0Q1020.0,139.0 984.0,90.0Q948.0,41.0 903.5,13.5Q859.0,-14.0 812.0,-14.0Q757.0,-14.0 725.0,14.0Q693.0,42.0 677.5,87.0Q662.0,132.0 653.0,183.0L633.0,302.0Q628.0,334.0 623.5,354.0Q619.0,374.0 611.0,374.0Q605.0,374.0 596.0,349.5Q587.0,325.0 576.0,286.0Q565.0,247.0 554.0,205.0L514.0,54.0Q507.0,29.0 494.0,19.5Q481.0,10.0 471.0,10.0Q461.0,10.0 451.5,12.5Q442.0,15.0 434.5,27.0Q427.0,39.0 423.0,66.0L409.0,180.0Q396.0,130.0 371.0,85.5Q346.0,41.0 307.5,13.5Q269.0,-14.0 213.0,-14.0ZM234.0,68.0Q249.0,68.0 270.5,77.5Q292.0,87.0 315.0,113.5Q338.0,140.0 358.5,189.0Q379.0,238.0 393.0,317.0L393.0,347.0Q393.0,424.0 369.0,453.5Q345.0,483.0 309.0,483.0Q275.0,483.0 239.0,450.0Q203.0,417.0 178.5,353.0Q154.0,289.0 154.0,196.0Q154.0,142.0 172.5,105.0Q191.0,68.0 234.0,68.0Z"/> <path id="g38" d="M-455.0,-303.0Q-546.0,-303.0 -616.5,-272.0Q-687.0,-241.0 -738.5,-186.5Q-790.0,-132.0 -823.5,-61.5Q-857.0,9.0 -873.5,88.5Q-890.0,168.0 -890.0,249.0Q-890.0,363.0 -853.0,462.5Q-816.0,562.0 -750.0,638.0Q-684.0,714.0 -595.0,757.0Q-506.0,800.0 -402.0,800.0Q-315.0,800.0 -251.0,786.0Q-187.0,772.0 -144.0,752.0Q-122.0,742.0 -122.0,720.0Q-122.0,707.0 -130.5,700.0Q-139.0,693.0 -151.0,693.0Q-166.0,693.0 -184.0,700.0Q-209.0,709.0 -262.0,721.0Q-315.0,733.0 -410.0,733.0Q-488.0,733.0 -558.0,704.0Q-628.0,675.0 -681.5,615.5Q-735.0,556.0 -765.5,465.0Q-796.0,374.0 -796.0,251.0Q-796.0,184.0 -785.5,116.0Q-775.0,48.0 -752.0,-13.5Q-729.0,-75.0 -690.0,-123.0Q-651.0,-171.0 -593.5,-198.5Q-536.0,-226.0 -458.0,-226.0Q-419.0,-226.0 -374.0,-214.0Q-329.0,-202.0 -289.5,-173.5Q-250.0,-145.0 -228.0,-96.0Q-216.0,-70.0 -181.0,-70.0Q-137.0,-70.0 -137.0,-95.0Q-137.0,-116.0 -153.5,-144.0Q-170.0,-172.0 -190.0,-194.0Q-222.0,-228.0 -268.5,-252.5Q-315.0,-277.0 -364.0,-290.0Q-413.0,-303.0 -455.0,-303.0Z"/> <path id="g3" d=""/> <path id="g47" d="M295.0,-14.0Q280.0,-14.0 268.0,-6.5Q256.0,1.0 256.0,20.0Q256.0,31.0 260.0,40.0L361.0,316.0Q337.0,413.0 290.5,453.0Q244.0,493.0 188.0,493.0Q142.0,493.0 119.5,477.0Q97.0,461.0 97.0,447.0Q97.0,437.0 103.0,432.5Q109.0,428.0 118.0,425.0Q144.0,417.0 158.5,404.0Q173.0,391.0 173.0,366.0Q173.0,341.0 157.5,324.0Q142.0,307.0 110.0,307.0Q71.0,307.0 45.5,334.0Q20.0,361.0 20.0,409.0Q20.0,449.0 39.5,483.0Q59.0,517.0 97.5,538.5Q136.0,560.0 193.0,560.0Q264.0,560.0 317.5,521.5Q371.0,483.0 399.0,423.0L571.0,897.0Q579.0,918.0 589.0,926.0Q599.0,934.0 613.0,934.0Q628.0,934.0 639.0,925.0Q650.0,916.0 650.0,900.0Q650.0,890.0 646.0,877.5Q642.0,865.0 640.0,861.0L335.0,23.0Q328.0,2.0 318.5,-6.0Q309.0,-14.0 295.0,-14.0Z"/> <path id="g36" d="M-381.0,-303.0Q-449.0,-303.0 -499.0,-282.0Q-549.0,-261.0 -582.0,-230.5Q-615.0,-200.0 -631.0,-172.0Q-647.0,-144.0 -647.0,-129.0Q-647.0,-117.0 -641.0,-106.5Q-635.0,-96.0 -616.0,-96.0Q-603.0,-96.0 -594.5,-105.0Q-586.0,-114.0 -579.0,-125.0Q-565.0,-145.0 -543.0,-168.5Q-521.0,-192.0 -483.0,-209.0Q-445.0,-226.0 -383.0,-226.0Q-349.0,-226.0 -313.5,-215.5Q-278.0,-205.0 -249.0,-177.0Q-220.0,-149.0 -207.0,-98.0Q-203.0,-84.0 -189.5,-77.0Q-176.0,-70.0 -162.0,-70.0Q-144.0,-70.0 -133.0,-77.0Q-122.0,-84.0 -122.0,-98.0Q-122.0,-112.0 -130.0,-139.5Q-138.0,-167.0 -152.0,-187.0Q-192.0,-248.0 -252.5,-275.5Q-313.0,-303.0 -381.0,-303.0Z"/> <path id="g6" d="M180.0,-10.0Q164.0,-10.0 149.0,-4.0Q134.0,2.0 134.0,15.0L134.0,336.0Q134.0,392.0 106.5,426.0Q79.0,460.0 36.0,477.0Q20.0,483.0 20.0,499.0Q20.0,511.0 27.0,525.5Q34.0,540.0 45.0,550.0Q56.0,560.0 66.0,560.0Q96.0,560.0 124.5,540.0Q153.0,520.0 175.0,489.5Q197.0,459.0 206.0,427.0Q231.0,456.0 265.5,487.0Q300.0,518.0 338.0,539.0Q376.0,560.0 410.0,560.0Q436.0,560.0 458.5,550.5Q481.0,541.0 497.0,515.5Q513.0,490.0 520.0,442.0Q545.0,470.0 577.5,497.0Q610.0,524.0 644.5,542.0Q679.0,560.0 710.0,560.0Q741.0,560.0 767.0,546.0Q793.0,532.0 808.5,492.5Q824.0,453.0 824.0,377.0L824.0,15.0Q824.0,2.0 810.5,-4.0Q797.0,-10.0 781.0,-10.0Q763.0,-10.0 748.5,-4.0Q734.0,2.0 734.0,15.0L734.0,353.0Q734.0,424.0 720.0,451.0Q706.0,478.0 673.0,478.0Q655.0,478.0 629.5,462.0Q604.0,446.0 576.5,420.0Q549.0,394.0 524.0,362.0L524.0,15.0Q524.0,2.0 510.0,-4.0Q496.0,-10.0 479.0,-10.0Q462.0,-10.0 448.0,-4.0Q434.0,2.0 434.0,15.0L434.0,353.0Q434.0,424.0 420.0,451.0Q406.0,478.0 373.0,478.0Q355.0,478.0 329.0,462.0Q303.0,446.0 275.5,420.0Q248.0,394.0 223.0,362.0Q224.0,359.0 224.0,354.0L224.0,15.0Q224.0,2.0 211.0,-4.0Q198.0,-10.0 180.0,-10.0Z"/> <path id="g35" d="M-488.0,-303.0Q-567.0,-303.0 -631.5,-283.0Q-696.0,-263.0 -743.0,-233.5Q-790.0,-204.0 -815.5,-175.5Q-841.0,-147.0 -841.0,-129.0Q-841.0,-117.0 -835.0,-106.5Q-829.0,-96.0 -810.0,-96.0Q-805.0,-96.0 -797.0,-100.5Q-789.0,-105.0 -785.0,-109.0Q-758.0,-134.0 -717.5,-161.5Q-677.0,-189.0 -620.5,-207.5Q-564.0,-226.0 -488.0,-226.0Q-432.0,-226.0 -378.5,-212.0Q-325.0,-198.0 -284.0,-168.5Q-243.0,-139.0 -227.0,-93.0Q-222.0,-80.0 -207.5,-75.0Q-193.0,-70.0 -177.0,-70.0Q-160.0,-70.0 -148.5,-77.0Q-137.0,-84.0 -137.0,-95.0Q-138.0,-117.0 -147.0,-135.5Q-156.0,-154.0 -169.0,-171.0Q-202.0,-215.0 -252.5,-244.5Q-303.0,-274.0 -363.5,-288.5Q-424.0,-303.0 -488.0,-303.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g71"/> </g> <g transform="translate(712,0)"> <use href="#g38"/> </g> <g transform="translate(992,0)"> <use href="#g3"/> </g> <g transform="translate(1212,0)"> <use href="#g47"/> </g> <g transform="translate(1782,0)"> <use href="#g71"/> </g> <g transform="translate(2924,0)"> <use href="#g3"/> </g> <g transform="translate(3144,0)"> <use href="#g71"/> </g> <g transform="translate(4119,0)"> <use href="#g36"/> </g> <g transform="translate(4286,0)"> <use href="#g3"/> </g> <g transform="translate(4506,0)"> <use href="#g6"/> </g> <g transform="translate(5466,0)"> <use href="#g35"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-regression]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Font has **proper** whitespace glyph names? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Glyph 0x00A0 is called &quot;nbspace&quot;: Change to &quot;uni00A0&quot;</p>
 [code: not-recommended-00a0]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifAhom/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, coptic, todhri, malayalam, old-permic, math, canadian-aboriginal, duployan, hebrew, syriac, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ahom</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Kpelle, Guinea (Latn, 622,000 speakers), Heiltsuk (Latn, 300 speakers), Mundani (Latn, 34,000 speakers), Southern Kisi (Latn, 360,000 speakers), Cicipu (Latn, 44,000 speakers), Ekpeye (Latn, 226,000 speakers), Vute (Latn, 21,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Ngbaka (Latn, 1,020,000 speakers), Nzakara (Latn, 50,000 speakers), Fur (Latn, 1,230,163 speakers), Bete-Bendi (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Sar (Latn, 500,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), South Central Banda (Latn, 244,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Gulay (Latn, 250,478 speakers), Zapotec (Latn, 490,000 speakers), Kaska (Latn, 125 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Ebira (Latn, 2,200,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Makaa (Latn, 221,000 speakers), Mfumte (Latn, 79,000 speakers), Mango (Latn, 77,000 speakers), Han (Latn, 6 speakers), Ma’di (Latn, 584,000 speakers), Kom (Latn, 360,685 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* na_ahom (U+11703): X=438.0,Y=1.0 (should be at baseline 0?)

* na_ahom (U+11703): X=126.0,Y=-2.0 (should be at baseline 0?)

* na_ahom (U+11703): X=528.0,Y=1.0 (should be at baseline 0?)

* ta_ahom (U+11704): X=844.0,Y=1.0 (should be at baseline 0?)

* ta_ahom (U+11704): X=776.5,Y=-2.0 (should be at baseline 0?)

* ra_ahom (U+1170D): X=703.0,Y=1.5 (should be at baseline 0?)

* sa_ahom (U+1170F): X=606.0,Y=2.0 (should be at baseline 0?)

* sa_ahom (U+1170F): X=528.5,Y=1.5 (should be at baseline 0?)

* dha_ahom (U+11714): X=446.0,Y=-1.0 (should be at baseline 0?)

* ga_ahom.alt: X=118.5,Y=-1.0 (should be at baseline 0?)

* bha_ahom (U+11718): X=373.0,Y=1.0 (should be at baseline 0?)

* bha_ahom (U+11718): X=446.0,Y=-1.0 (should be at baseline 0?)

* medialRa_ahom (U+1171E): X=-292.0,Y=678.0 (should be at cap-height 680?)

* medialRa_ahom.desc: X=-262.0,Y=679.0 (should be at cap-height 680?)

* aSign_ahom (U+11720): X=197.0,Y=681.5 (should be at cap-height 680?)

* awSign_ahom (U+11727): X=28.0,Y=681.0 (should be at cap-height 680?)

* aiSign_ahom (U+11729): X=80.0,Y=678.0 (should be at cap-height 680?)

* three_ahom (U+11733): X=606.0,Y=2.0 (should be at baseline 0?)

* three_ahom (U+11733): X=528.5,Y=1.5 (should be at baseline 0?)

* four_ahom (U+11734): X=606.0,Y=2.0 (should be at baseline 0?)

* four_ahom (U+11734): X=528.5,Y=1.5 (should be at baseline 0?)

* twenty_ahom (U+1173B): X=1053.0,Y=681.0 (should be at cap-height 680?)

* twenty_ahom (U+1173B): X=606.0,Y=2.0 (should be at baseline 0?)

* twenty_ahom (U+1173B): X=528.5,Y=1.5 (should be at baseline 0?)

* rulaiSign_ahom (U+1173E): X=605.0,Y=-1.5 (should be at baseline 0?)

* ca_ahom (U+11740): X=515.5,Y=1.5 (should be at baseline 0?)

* tta_ahom (U+11741): X=844.0,Y=1.0 (should be at baseline 0?)

* tta_ahom (U+11741): X=776.5,Y=-2.0 (should be at baseline 0?)

* ddha_ahom (U+11744): X=446.0,Y=-1.0 (should be at baseline 0?)

* nna_ahom (U+11745): X=846.0,Y=1.0 (should be at baseline 0?)

* nna_ahom (U+11745): X=756.0,Y=1.0 (should be at baseline 0?)

* nna_ahom (U+11745): X=210.0,Y=1.0 (should be at baseline 0?)

* nna_ahom (U+11745): X=120.0,Y=1.0 (should be at baseline 0?)

* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* Gcommaaccent (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* O (U+004F): X=195.5,Y=679.5 (should be at cap-height 680?)

* O (U+004F): X=542.5,Y=679.5 (should be at cap-height 680?)

* OE (U+0152): X=195.5,Y=679.5 (should be at cap-height 680?)

* Oacute (U+00D3): X=195.5,Y=679.5 (should be at cap-height 680?)

* Oacute (U+00D3): X=542.5,Y=679.5 (should be at cap-height 680?)

* Ocircumflex (U+00D4): X=195.5,Y=679.5 (should be at cap-height 680?)

* Ocircumflex (U+00D4): X=542.5,Y=679.5 (should be at cap-height 680?)

* Odieresis (U+00D6): X=195.5,Y=679.5 (should be at cap-height 680?)

* Odieresis (U+00D6): X=542.5,Y=679.5 (should be at cap-height 680?)

* Ograve (U+00D2): X=195.5,Y=679.5 (should be at cap-height 680?)

* Ograve (U+00D2): X=542.5,Y=679.5 (should be at cap-height 680?)

* Ohungarumlaut (U+0150): X=195.5,Y=679.5 (should be at cap-height 680?)

* Ohungarumlaut (U+0150): X=542.5,Y=679.5 (should be at cap-height 680?)

* Oslash (U+00D8): X=195.5,Y=679.5 (should be at cap-height 680?)

* Otilde (U+00D5): X=195.5,Y=679.5 (should be at cap-height 680?)

* Otilde (U+00D5): X=542.5,Y=679.5 (should be at cap-height 680?)

* Q (U+0051): X=195.5,Y=679.5 (should be at cap-height 680?)

* Q (U+0051): X=542.5,Y=679.5 (should be at cap-height 680?)

* Uring (U+016E): X=371.0,Y=979.0 (should be at ascender 980?)

* atilde (U+00E3): X=329.5,Y=680.5 (should be at cap-height 680?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* copyright (U+00A9): X=232.0,Y=679.5 (should be at cap-height 680?)

* copyright (U+00A9): X=612.0,Y=679.5 (should be at cap-height 680?)

* dollar (U+0024): X=253.0,Y=682.0 (should be at cap-height 680?)

* g (U+0067): X=409.0,Y=548.0 (should be at x-height 550?)

* g (U+0067): X=511.5,Y=551.5 (should be at x-height 550?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* gcommaaccent (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* gcommaaccent (U+0123): X=321.0,Y=681.0 (should be at cap-height 680?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* germandbls (U+00DF): X=242.0,Y=680.5 (should be at cap-height 680?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* ntilde (U+00F1): X=378.5,Y=680.5 (should be at cap-height 680?)

* ordfeminine (U+00AA): X=189.0,Y=682.0 (should be at cap-height 680?)

* otilde (U+00F5): X=336.5,Y=680.5 (should be at cap-height 680?)

* percent (U+0025): X=210.0,Y=682.0 (should be at cap-height 680?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* registered (U+00AE): X=232.0,Y=679.5 (should be at cap-height 680?)

* registered (U+00AE): X=612.0,Y=679.5 (should be at cap-height 680?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* t (U+0074): X=97.0,Y=551.0 (should be at x-height 550?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

* tilde (U+02DC): X=269.5,Y=680.5 (should be at cap-height 680?)

* tildecomb (U+0303): X=-266.5,Y=680.5 (should be at cap-height 680?)

* trademark (U+2122): X=379.0,Y=681.0 (should be at cap-height 680?)

* trademark (U+2122): X=755.0,Y=681.0 (should be at cap-height 680?)

* trademark (U+2122): X=144.0,Y=682.0 (should be at cap-height 680?)

* trademark (U+2122): X=101.0,Y=682.0 (should be at cap-height 680?)

* trademark (U+2122): X=253.0,Y=682.0 (should be at cap-height 680?)

* trademark (U+2122): X=206.0,Y=682.0 (should be at cap-height 680?)

* two (U+0032): X=417.0,Y=678.5 (should be at cap-height 680?)

* zero (U+0030): X=146.0,Y=679.0 (should be at cap-height 680?)

* zero (U+0030): X=411.0,Y=679.0 (should be at cap-height 680?)

* commaaccentrotate: X=292.0,Y=681.0 (should be at cap-height 680?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* ca_ahom (U+11740): L&lt;&lt;584.0,378.0&gt;--&lt;583.0,62.0&gt;&gt;/B&lt;&lt;583.0,62.0&gt;-&lt;591.0,116.0&gt;-&lt;605.5,183.5&gt;&gt; = 8.245653868781645
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* ca_ahom (U+11740): L&lt;&lt;584.0,378.0&gt;--&lt;583.0,62.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 10 | 116 | 6 | 117 | 0 | 
| 0% | 0% | 1% | 4% | 46% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
