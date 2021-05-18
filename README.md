# sesamum101

Background

Sesamum indicum L. is one of the major oil crop traditionally used in Korean food culture as cooking oil, seasoning or decoration food ([Kim et al 2016](https://www.sciencedirect.com/science/article/pii/S2352618116300099)). This member of mint family harbors valuable nutritional and health benefits to human mainly for lignans (sesamin, sesamolin, sesaminol and sesamol). Based on the recent Korean nutritional and health survey, the daily lignan intake from sesame oil is up to 77% with 18.39 mg  and 13.26 mg per person for males and females respectively ([Kim et al 2020](https://www.mdpi.com/2304-8158/9/4/394)).



From last decade, tremenduous effort brought this orphan crop into the genomics era. 

Initial genome was rendered using BAC clone and short-read approchaes using Yuzhi11 cultivar (Ref). Meanwhile, the OCRI generated a contig level assembly (ref) that have been updated in linkage group later on (ref). The availaibility of the reference Chinese cultivars Zhongzhi13 facilaitate the identification and validation of molecular marker relative to plant height (ref), yield components (ref), drought stress (ref), salinity stress (ref) and waterlogging stress (ref).

Moreover, a pangenome was constructed based on One idian cultivar and four chineses genotypes including  two cultivars and three landraces.

The strategies employed for the pangenome was based on a single reference assembly (Zhongzhi13) as a backbone representative. Despite the huge contribution of this single refence genome, it cannot represent properly the complete genomic sequence diversity in Sesame species. 
Therefore the need of high quality genome resource from different origin may help to get inside into the variability among genotypes at genomic level. Besides, having a good quality korean cultivar genome will drastically improve the ongoing korean sesamum breeding activities for oil (Jin husband), lignan (ref), and disease restistance (ref azecova) in the Korean environment.

The cultivar Goenbaek exhibited not only high yield characteristics but also resistant to sesamum Phytophtora blight resistance ([Kim et al 2018](http://www.koreabreedjournal.org/journal/view.html?doi=10.9787/KJBS.2018.50.3.256), [Asegova et al 2021](https://www.frontiersin.org/articles/10.3389/fpls.2021.604709/full))  


To speed up the Korean genomic-assisted sesame breeding program, a chromosomal-grade genome assembly of the cultivar Goenbaek was generated using Short-read, long-reads and chromosome conformation Hi-C technologies. 

The long-reads genome assembly results in 1000 contigs with an N50 of 1000 bp. By including the Hi-c data set, we were able to anchore the contigs into 13 chromosmes as expected. The new Sesamum genome spanned 1000 bp with a high contiguity of 1000 bp representing 10% of the estimated size.  


The present whole-genome scale data constitutes a valuable resource that will contribute to the sesame breeding. Besides, it provide an additionnal candidate genome to extend the existing sesame pangenome.
 




01. Data Note | Tutorial for my paper | GigaScience


[Paper Reference](https://academic.oup.com/gigascience/article/10/4/giab027/6237163?searchresult=1)



![img](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/gigascience/10/4/10.1093_gigascience_giab027/1/m_giab027fig3.jpeg?Expires=1623438881&Signature=gP~CVr2nDc6zzW3XeiLPYCJrkckPKfKFDjC7CiroSc5k2OE5L8yPYvqDF4js2ereN2TbKlJ990OWtWxE9frBqY4RhCBdVZH-kfOuG0WXxGiGrjp8yZA6lstEZgpIStL~dF~8QXYtSH7guywcEXNhZEZF985KntBRzwy3E4zynQtLDMQr43zUibIHnne8ymoq98VRP83GHL-NYzaf~2jSRcqRE9bJhDzta5XY8RZeA2Tpf7tvQUPXqs9YNAvoI5qW7y~89fcMsEoz-2ovdWNYk2-6BSqj2jYBSU5q6eioq~L7DxfmdLzQfAcIF5u3P3N4qp4G6dnODw1qBc8NhfcJEA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA)

02. Faire u tree map entre Zhongzhi13 version 2 and our data et les autres si possible

![ing](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/gigascience/9/12/10.1093_gigascience_giaa123/1/m_giaa123fig1.jpeg?Expires=1623748297&Signature=hoTfq5pslEyt2~x2w8abvF5h5kgy8wDMwshvtr6iKYZULKdqkPQ9L6Il4RFy6BM3WnPcMNK3ozWbfWFJgJUrIk3GMTL7aD39v6KB31lX7Q7yhV~KoI6CCAYHWzStvQ1DUhwSss-9o8YqX-kl0QUaKy~Wd-y~KCeucK2VeK3biSSIVQx6xlahkal1kv9BXRX3u4DLAaqQzMNwpL0dZTo5cIEFbu91wVi6Q0gAC-n2qC61F~AyLzb38epX5P5G-~cZV68XuHZKV9MroYXkY8pM1UEw4xFd9OBYo7pVz14CG1IieHF1S~XEAxhI~Z7LqueymjB2aZAUr6gM6zz1FVqr4A__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA)



Tutorial [ici](https://www.r-graph-gallery.com/235-treemap-with-subgroups.html) et simplement [ici](https://www.r-graph-gallery.com/234-a-very-basic-treemap.html)


03. Faire le BUSCO analysis des six data comme ici



![img](https://camo.githubusercontent.com/7cbc3e3132336b9c16387af482836d3c09c85ef7fd15a4c62881f2f1af946810/68747470733a2f2f6f75702e73696c76657263686169722d63646e2e636f6d2f6f75702f6261636b66696c652f436f6e74656e745f7075626c69632f4a6f75726e616c2f67696761736369656e63652f372f31322f31302e313039335f67696761736369656e63655f6769793134312f312f676979313431666967332e6a7065673f457870697265733d31363137303737333530265369676e61747572653d5432737e594b586c776b73747364516b306841713750414e68357974673857347a674c45364e65517169656b7642524f4f5358676275344e2d715645616e424f394e785a7474646444387430657069786f626f61686c394c4358747e39526358383735454f37307164666b3871335234615274793479486467645578613670643351304e3057486a563652497571322d4b702d6156374c4b7537566c6f694d5179534739424e78354577767630784435394d4c7559562d3049304832494d764f6563465336634a42363631364967626d45616a6c6279665a4f35495667646b36444a6877463042424d673879643577754d686b4f5331514742666c784579625535386c50666e53426d414e436b534a3161574e7048506c4d386c53536b4952565431474c7474536358536c4b39444e34536b417a5a6b72796a5465334938687a2d5a5a494679476b504d71376b4f4537724b547274675f5f264b65792d506169722d49643d41504b4149453547354352444b36524433504741)




04. Pour les repeats faut faire ce style


![img](https://camo.githubusercontent.com/6d094ad937739217f79934191db70fd2f28dc5b7229bf328a22c2bdff5ad8307/68747470733a2f2f6f75702e73696c76657263686169722d63646e2e636f6d2f6f75702f6261636b66696c652f436f6e74656e745f7075626c69632f4a6f75726e616c2f67696761736369656e63652f372f31322f31302e313039335f67696761736369656e63655f6769793134312f312f676979313431666967352e6a7065673f457870697265733d31363137303737343436265369676e61747572653d64766c4c314d3947794f4f4859797a756965765473727079794a4b6b6a5842637a484346364a3153737053324e37395a69537737483847744671745a4339654e466a6833705a4f635a614e68345050526659613865727a7a676674716257797172555a496947356a79626e4e75526548764e50715258466a6f3767563749345a4f4947505a5a437e7747634a44712d55573243696a5342394156327a4447687452365454796b62713753503030444a4b656758756b726d364b516b6c3747726471387a6f476b4236436e6b6a7376554e6f6245527e465776572d53694c6779506e4b7546634f4a57346c447e4f3778564531574a6c2d6354786f4265616f54412d55794d65536b6f774676467e676c6373625a576e5a346d46556537574857465941614f6a785958327a375078735964504178496a4879364b61456271434650397437456e7534573342655577417a7a5462787930515f5f264b65792d506169722d49643d41504b4149453547354352444b36524433504741)

Ou bien de cette maniere





![img](https://camo.githubusercontent.com/d2f494c5dec98229cfb788178328a22a18b510b8135335aeb4b6a529a7277337/68747470733a2f2f6d656469612e737072696e6765726e61747572652e636f6d2f66756c6c2f737072696e6765722d7374617469632f696d6167652f61727425334131302e313033382532467334313436372d3032302d32303530382d322f4d656469614f626a656374732f34313436375f323032305f32303530385f466967335f48544d4c2e706e673f61733d77656270)


Pour la phylogeny le circos et le orthofinder graph faire comme ceci



![img](https://camo.githubusercontent.com/def7f4d0da9a37671c40d5042e77a96e6a14bfed1389bd1561f693526c0c0c1f/68747470733a2f2f6d656469612e737072696e6765726e61747572652e636f6d2f66756c6c2f737072696e6765722d7374617469632f696d6167652f61727425334131302e313033382532467334313436372d3032302d31393638312d312f4d656469614f626a656374732f34313436375f323032305f31393638315f466967315f48544d4c2e706e673f61733d77656270)

#######################################################

Pour les LEA suivre cette methodw de [Dossa et al 2018](https://link.springer.com/article/10.1186/s12864-019-6091-5)




Example de LEA paper


- [Dissecting the Genomic Diversification of Late Embryogenesis Abundant (LEA) Protein Gene Families in Plants](https://academic.oup.com/gbe/article/11/2/459/5165404#131051515)

Ici ils ont bien mis les PFAM des different LEA types


- [Late Embryogenesis Abundant (LEA) Gene Family in Maize: Identification, Evolution, and Expression Profiles](https://link.springer.com/article/10.1007/s11105-015-0901-y)

- [Genome-wide identification of the LEA protein gene family in grapevine (Vitis vinifera L.)](https://link.springer.com/article/10.1007/s11295-019-1364-3)

- [Genome-wide identification of the LEA protein gene family in grapevine (Vitis vinifera L.)](https://link.springer.com/article/10.1007/s11295-019-1364-3)


- [Genome-wide search and structural and functional analyses for late embryogenesis-abundant (LEA) gene family in poplar](https://bmcplantbiol.biomedcentral.com/articles/10.1186/s12870-021-02872-3)


- [Genome-Wide Identification and Expression Profiles of Late Embryogenesis-Abundant (LEA) Genes during Grain Maturation in Wheat (Triticum aestivum L.)](https://www.mdpi.com/2073-4425/10/9/696)



### QTL Mapping


[Fine mapping of a kernel length‑related gene with potential value for maize breeding](https://link.springer.com/epdf/10.1007/s00122-020-03749-z?sharing_token=VqVWEkLqaVFrk0vlWT-szfe4RwlQNchNByi7wbcMAY4UCpT2N65xjFjixhSV8FGphtwC5khxREa6MG0grewEknFzlqZKp0ci2HRtRYsyJAdJatoHOOsilE3cOY_bt1UvExyoMepEyE57yyvH78fJpYLe9ctKnbp3qS3fNhe2VWA%3D)


![img](https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs00122-020-03749-z/MediaObjects/122_2020_3749_Fig1_HTML.png?as=webp)

### Capsicum


[New reference genome sequences of hot pepper reveal the massive evolution of plant disease-resistance genes by retroduplication](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-017-1341-9)


![img](https://media.springernature.com/full/springer-static/image/art%3A10.1186%2Fs13059-017-1341-9/MediaObjects/13059_2017_1341_Fig1_HTML.gif?as=webp)




Faire aussi syntheny entre sulement Zhongzhi13 et Goenbaek ou tous les six pourquoi pas



Et peut etre ajouter un tree des LATE EMBRYOGENESIS ABUNDANT GENES



Un genome d'un lamiales [Genome structure and evolution of Antirrhinum majus L](https://www.nature.com/articles/s41477-018-0349-9#Sec8)

![img](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41477-018-0349-9/MediaObjects/41477_2018_349_Fig2_HTML.png?as=webp)








### Onion linkage map construction


[Construction of an Onion (Allium cepa L.) Genetic Linkage Map Using Genotyping-by-Sequencing Analysis with a Reference Gene Set and Identification of QTLs Controlling Anthocyanin Synthesis and Content](https://www.mdpi.com/2223-7747/9/5/616/htm)


![img](https://www.mdpi.com/plants/plants-09-00616/article_deploy/html/images/plants-09-00616-g002a.png)

### Mineral 


2021 | Pearl millet | [Multi-environment QTL mapping for grain Iron and Zinc content using bi-parental RIL mapping population in pearl millet](https://www.frontiersin.org/articles/10.3389/fpls.2021.659789/abstract)

2018 | Pearl millet | [Mapping Grain Iron and Zinc Content Quantitative Trait Loci in an Iniadi-Derived Immortal Population of Pearl Millet](https://www.mdpi.com/2073-4425/9/5/248)


2020 | Israel |[Genetic Architecture Underpinning Yield Components and Seed Mineral–Nutrients in Sesame](https://www.mdpi.com/2073-4425/11/10/1221/htm)



### Internode elongation gene


2018 | Soybean | [Combining QTL-seq and linkage mapping to fine map a wild soybean allele characteristic of greater plant height](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-018-4582-4)


![img](https://media.springernature.com/full/springer-static/image/art%3A10.1186%2Fs12864-018-4582-4/MediaObjects/12864_2018_4582_Fig1_HTML.gif?as=webp)

2016 | Sesame | [Updated sesame genome assembly and fine mapping of plant height and seed coat color QTLs using a new high-density genetic map](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-015-2316-4#Sec8)



2019  | Sesame | [Identification of a Sidwf1 gene controlling short internode length trait in the sesame dwarf mutant dw607](https://link.springer.com/article/10.1007/s00122-019-03441-x)


2018 | Sesame | [Genetic analysis of yield contributing traits and mapping of QTLs in a recombinant inbred line (RIL) population of sesame (Sesamum indicum L.)](http://ejplantbreeding.org/index.php/EJPB/article/view/2592)



2019 | Tomato | [Identification and Characterization of EI (Elongated Internode) Gene in Tomato (Solanum lycopersicum)](https://www.mdpi.com/1422-0067/20/9/2204)

2014 | Rice | [QTL analysis of internode elongation in response to gibberellin in deepwater rice ](https://academic.oup.com/aobpla/article/doi/10.1093/aobpla/plu028/158543)

2014 | Wheat | [QTLs for uppermost internode and spike length in two wheat RIL populations and their affect upon plant height at an individual QTL level](https://link.springer.com/article/10.1007/s10681-014-1156-7#Sec2)



2015 | Maize | [Genetic Dissection of Internode Length Above the Uppermost Ear in Four RIL Populations of Maize (Zea mays L.)](https://academic.oup.com/g3journal/article/5/2/281/6025322?login=true)





2020 | Wheat | [The contribution of photosynthesis traits and plant height components to plant height in wheat at the individual quantitative trait locus level](https://www.nature.com/articles/s41598-020-69138-0)

2012 | Wheat | [QTL Detection of Internode Length and Its Component Index in Wheat Using Two Related RIL Populations](https://link.springer.com/article/10.1556/CRC.2012.0002)



2007 | Rice | [A Major QTL Confers Rapid Internode Elongation in response to water rice in deep water rice](https://www.jstage.jst.go.jp/article/jsbbs/57/4/57_4_305/_pdf)


2007 | Soybean | [Genomic Regions Containing QTL for Plant Height, Internodes Length, and Flower Color in Soybean [Glycine max (L.) Merr.]](https://www.jstor.org/stable/4608808?seq=1#metadata_info_tab_contents)


### sesamolin, sesamol in sesamum sp ... The japanese team...amaizing work



2020 | The Plant Journal | [(+)‐Sesamin‐oxidising CYP92B14 shapes specialised lignan metabolism in sesame](https://onlinelibrary.wiley.com/doi/full/10.1111/tpj.14989)


2019 | The Plant Journal | [Glycoside‐specific glycosyltransferases catalyze regio‐selective sequential glucosylations for a sesame lignan, sesaminol triglucoside](https://onlinelibrary.wiley.com/doi/full/10.1111/tpj.14586)

2018 | Plant and Cell Physiology | [Formation of a Methylenedioxy Bridge in (+)-Epipinoresinol by CYP81Q3 Corroborates with Diastereomeric Specialization in Sesame Lignans](https://academic.oup.com/pcp/article/59/11/2278/5062626?login=true)

2017 | Nature Communications | [Oxidative rearrangement of (+)-sesamin by CYP92B14 co-generates twin dietary lignans in sesame](https://www.nature.com/articles/s41467-017-02053-7)

2008 | The Plant Journal | [Sequential glucosylation of a furofuran lignan, (+)‐sesaminol, by Sesamum indicum UGT71A9 and UGT94D1 glucosyltransferases](https://onlinelibrary.wiley.com/doi/10.1111/j.1365-313X.2008.03428.x?utm_source=TrendMD&utm_medium=cpc&utm_campaign=The_Plant_Journal_TrendMD_0&sid=WOL_tmd1b)


2006 | PNAS | [Formation of two methylenedioxy bridges by a Sesamum CYP81Q protein yielding a furofuran lignan, (+)-sesamin](https://www.pnas.org/content/103/26/10116.short)

-----------------------------------------------------------------------------------------------------------------------------------


2021


 Excellent reference for sesame paper ---> Two versions | Both in Nature genetics | [Version China long reads](https://www.nature.com/articles/s41588-021-00808-z.pdf) | [Version Germany short reads](https://www.nature.com/articles/s41588-021-00807-0.pdf)
 
 
 
 The Chinese pipeline
 
 ![pipeline](https://media.springernature.com/full/springer-static/esm/art%3A10.1038%2Fs41588-021-00808-z/MediaObjects/41588_2021_808_Fig8_ESM.jpg?as=webp)
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 [A high-quality genome assembly highlights rye genomic characteristics and agronomically important genes | Nature Genetics](https://www.nature.com/articles/s41588-021-00808-z)


May include this in the S. indicum genome | [Genome-wide analysis of the apple CaCA superfamily reveals that MdCAX proteins are involved in the abiotic stress response as calcium transporters](https://link.springer.com/article/10.1186/s12870-021-02866-1)


2021



[Lignans of Sesame (Sesamum indicum L.): A Comprehensive Review](https://www.mdpi.com/1420-3049/26/4/883)


[QTL mapping of PEG-induced drought tolerance at the early seedling stage in sesame using whole genome re-sequencing](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0247681)

2020 

[A novel motif in the 5’‐UTR of an orphan gene ‘Big Root Biomass’ modulates root biomass in sesame](https://onlinelibrary.wiley.com/doi/abs/10.1111/pbi.13531)

[High-resolution temporal transcriptome sequencing unravels ERF and WRKY as the master players in the regulatory networks underlying sesame responses to waterlogging and recovery](https://www.sciencedirect.com/science/article/pii/S0888754320320206) | Inspiration from [here](http://www.plantcell.org/content/31/5/974)


2016 



[Updated sesame genome assembly and fine mapping of plant height and seed coat color QTLs using a new high-density genetic map](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-015-2316-4)


2014 


[Genome sequencing of the high oil crop sesame provides insight into oil biosynthesis](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2014-15-2-r39)


2013 



[Genome sequencing of the important oilseed crop Sesamum indicum L](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-1-401)


2006


[Formation of two methylenedioxy bridges by a Sesamum CYP81Q protein yielding a furofuran lignan, ()-sesamin](https://www.pnas.org/content/pnas/103/26/10116.full.pdf)

# Olive

2004


[A molecular linkage map of olive (Olea europaea L.) based on RAPD, microsatellite, and SCAR markers](https://cdnsciencepub.com/doi/10.1139/g03-091)

2016 

[Genome sequence of the olive tree, Olea europaea](https://academic.oup.com/gigascience/article/5/1/s13742-016-0134-5/2720990)




2017

[Genome of wild olive and the evolution of oil biosynthesis](https://www.pnas.org/content/114/44/E9413)



2018

[Single nucleotide polymorphism (SNP) diversity in an olive germplasm collection](https://www.actahort.org/books/1199/1199_5.htm)




2019

[High Levels of Variation Within Gene Sequences of Olea europaea L.](https://www.frontiersin.org/articles/10.3389/fpls.2018.01932/full)


[Genome wide association study of 5 agronomic traits in olive (Olea europaea L.)](https://www.nature.com/articles/s41598-019-55338-w)





2020


[EST–SNP Study of Olea europaea L. Uncovers Functional Polymorphisms between Cultivated and Wild Olives](https://www.mdpi.com/2073-4425/11/8/916)




[Genome-Wide Identification, Evolutionary Patterns, and Expression Analysis of bZIP Gene Family in Olive (Olea europaea L.)](https://www.mdpi.com/2073-4425/11/5/510)





[Genomic evidence for recurrent genetic admixture during the domestication of Mediterranean olive trees (Olea europaea L.)](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-020-00881-6)

