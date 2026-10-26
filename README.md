# T2T gapless genome assembly of the neglected crop *Moringa stenopetala*

**A. Gálvez-Salido**, C. Martínez Padilla, P. Contreras Saavedra, A. Ríos Bravo & L. Carretero-Paulet\*

Department of Biology and Geology, Pabellón de Historia Natural – Centro de Investigación de Colecciones Científicas de la Universidad de Almería (PHN-CECOUAL), University of Almería, E04120 Almería, Spain.
Contact: ags408@ual.es (presenting author) · lpaulet@ual.es (\*corresponding author)

Poster presented at the XV Simposio de Investigación en Ciencias Experimentales, University of Almería.
---

## References cited in the introduction

Abiyu, A., Yan, D., Girma, A., Song, X., & Wang, H. (2018). Wastewater treatment potential of *Moringa stenopetala* over *Moringa olifera* as a natural coagulant, antimicrobial agent and heavy metal removals. *Cogent Environmental Science*, *4*(1), Article 1433507. https://doi.org/10.1080/23311843.2018.1433507

Carretero-Paulet, L., Marczuk-Rojas, J. P., & Gálvez-Salido, A. (2026). Nuclear DNA of plastid origin (NUPTs), neglected driver of genome variation and evolutionary innovation. *The Plant Journal*, *125*(3), Article e70685. https://doi.org/10.1111/tpj.70685

Fahey, J. W., Olson, M. E., Stephenson, K. K., Wade, K. L., Chodur, G. M., Odee, D., Nouman, W., Massiah, M., Alt, J., Egner, P. A., & Hubbard, W. C. (2018). The diversity of chemoprotective glucosinolates in Moringaceae (*Moringa* spp.). *Scientific Reports*, *8*, Article 7994. https://doi.org/10.1038/s41598-018-26058-4

Galgaye, G. G., Beshir, H. M., & Roro, A. G. (2020). Physiological responses of moringa (*Moringa stenopetala* L.) seedlings to drought stress under greenhouse conditions, Southern Ethiopia. *Asian Journal of Biotechnology*, *12*(2), 97–107. https://doi.org/10.3923/ajbkr.2020.97.107

Marczuk-Rojas, J. P., Álamo-Sierra, A. M., Salmerón, A., Alcayde, A., Isanbaev, V., & Carretero-Paulet, L. (2024). Spatial and temporal characterization of the rich fraction of plastid DNA present in the nuclear genome of *Moringa oleifera* reveals unanticipated complexity in NUPTs’ formation. *BMC Genomics*, *25*, Article 60. https://doi.org/10.1186/s12864-024-09979-5

Olson, M. E. (2002). Combining data from DNA sequences and morphology for a phylogeny of Moringaceae (Brassicales). *Systematic Botany*, *27*(1), 55–73. https://doi.org/10.1043/0363-6445-27.1.55

---

## Software and databases

### 1. Pre-assembly

**LongQC** — HiFi read quality control
Fukasawa, Y., Ermini, L., Wang, H., Carty, K., & Cheung, M. S. (2020). LongQC: A quality control tool for third generation sequencing long read data. *G3: Genes, Genomes, Genetics*, *10*(4), 1193–1196. https://doi.org/10.1534/g3.119.400864

**SeqKit** — read filtering
Shen, W., Sipos, B., & Zhao, L. (2024). SeqKit2: A Swiss army knife for sequence and alignment processing. *iMeta*, *3*(3), Article e191. https://doi.org/10.1002/imt2.191

**NCBI FCS-Adaptor** — adapter screening
Astashyn, A., Tvedte, E. S., Sweeney, D., Sapojnikov, V., Bouk, N., Joukov, V., Mozes, E., Strope, P. K., Sylla, P. M., Wagner, L., Bidwell, S. L., Brown, L. C., Clark, K., Davis, E. W., Smith-White, B., Hlavina, W., Pruitt, K. D., Schneider, V. A., & Murphy, T. D. (2024). Rapid and sensitive detection of genome contamination at scale with FCS-GX. *Genome Biology*, *25*, Article 60. https://doi.org/10.1186/s13059-024-03198-7

**HiFiAdapterFilt** — adapter removal
Sim, S. B., Corpuz, R. L., Simmonds, T. J., & Geib, S. M. (2022). HiFiAdapterFilt, a memory efficient read processing pipeline, prevents occurrence of adapter sequence in PacBio HiFi reads and their negative impacts on genome assembly. *BMC Genomics*, *23*, Article 157. https://doi.org/10.1186/s12864-022-08375-1

**Jellyfish** — k-mer counting
Marçais, G., & Kingsford, C. (2011). A fast, lock-free approach for efficient parallel counting of occurrences of *k*-mers. *Bioinformatics*, *27*(6), 764–770. https://doi.org/10.1093/bioinformatics/btr011

**GenomeScope** — genome size estimation
Vurture, G. W., Sedlazeck, F. J., Nattestad, M., Underwood, C. J., Fang, H., Gurtowski, J., & Schatz, M. C. (2017). GenomeScope: Fast reference-free genome profiling from short reads. *Bioinformatics*, *33*(14), 2202–2204. https://doi.org/10.1093/bioinformatics/btx153

**TeloSearchLR** — telomeric motif identification
Chung, G., Piano, F., & Gunsalus, K. C. (2025). TeloSearchLR: An algorithm to detect novel telomere repeat motifs using long sequencing reads. *G3: Genes, Genomes, Genetics*, *15*(6), Article jkaf062. https://doi.org/10.1093/g3journal/jkaf062

### 2. Assembly

**hifiasm** — haplotype-resolved assembly (HiFi + Hi-C)
Cheng, H., Concepcion, G. T., Feng, X., Zhang, H., & Li, H. (2021). Haplotype-resolved *de novo* assembly using phased assembly graphs with hifiasm. *Nature Methods*, *18*(2), 170–175. https://doi.org/10.1038/s41592-020-01056-5

Cheng, H., Jarvis, E. D., Fedrigo, O., Koepfli, K.-P., Urban, L., Gemmell, N. J., & Li, H. (2022). Haplotype-resolved assembly of diploid genomes without parental data. *Nature Biotechnology*, *40*(9), 1332–1335. https://doi.org/10.1038/s41587-022-01261-x

**purge_dups** — haplotig purging
Guan, D., McCarthy, S. A., Wood, J., Howe, K., Wang, Y., & Durbin, R. (2020). Identifying and removing haplotypic duplication in primary genome assemblies. *Bioinformatics*, *36*(9), 2896–2898. https://doi.org/10.1093/bioinformatics/btaa025

**Pilon** — polishing
Walker, B. J., Abeel, T., Shea, T., Priest, M., Abouelliel, A., Sakthikumar, S., Cuomo, C. A., Zeng, Q., Wortman, J., Young, S. K., & Earl, A. M. (2014). Pilon: An integrated tool for comprehensive microbial variant detection and genome assembly improvement. *PLoS ONE*, *9*(11), Article e112963. https://doi.org/10.1371/journal.pone.0112963

**Chlomito** — organellar contig removal
Song, W., Li, C., Lu, Y., Shen, D., Jia, Y., Huo, Y., Piao, W., & Jin, H. (2024). Chlomito: A novel tool for precise elimination of organelle genome contamination from nuclear genome assembly. *Frontiers in Plant Science*, *15*, Article 1430443. https://doi.org/10.3389/fpls.2024.1430443

### 3. Scaffolding

**HiC-Pro** — Hi-C data processing
Servant, N., Varoquaux, N., Lajoie, B. R., Viara, E., Chen, C.-J., Vert, J.-P., Heard, E., Dekker, J., & Barillot, E. (2015). HiC-Pro: An optimized and flexible pipeline for Hi-C data processing. *Genome Biology*, *16*, Article 259. https://doi.org/10.1186/s13059-015-0831-x

**YaHS** — Hi-C scaffolding
Zhou, C., McCarthy, S. A., & Durbin, R. (2023). YaHS: Yet another Hi-C scaffolding tool. *Bioinformatics*, *39*(1), Article btac808. https://doi.org/10.1093/bioinformatics/btac808

**Juicer** — contact maps
Durand, N. C., Shamim, M. S., Machol, I., Rao, S. S. P., Huntley, M. H., Lander, E. S., & Aiden, E. L. (2016). Juicer provides a one-click system for analyzing loop-resolution Hi-C experiments. *Cell Systems*, *3*(1), 95–98. https://doi.org/10.1016/j.cels.2016.07.002

### 4. Gap closing and telomere identification

**quarTeT** (GapFiller and TeloExplorer modules)
Lin, Y., Ye, C., Li, X., Chen, Q., Wu, Y., Zhang, F., Pan, R., Zhang, S., Chen, S., Wang, X., Cao, S., Wang, Y., Yue, Y., Liu, Y., & Yue, J. (2023). quarTeT: A telomere-to-telomere toolkit for gap-free genome assembly and centromeric repeat identification. *Horticulture Research*, *10*(8), Article uhad127. https://doi.org/10.1093/hr/uhad127

**SOAP GapCloser** (SOAPdenovo2 package)
Luo, R., Liu, B., Xie, Y., Li, Z., Huang, W., Yuan, J., He, G., Chen, Y., Pan, Q., Liu, Y., Tang, J., Wu, G., Zhang, H., Shi, Y., Liu, Y., Yu, C., Wang, B., Lu, Y., Han, C., . . . Wang, J. (2012). SOAPdenovo2: An empirically improved memory-efficient short-read *de novo* assembler. *GigaScience*, *1*(1), Article 18. https://doi.org/10.1186/2047-217X-1-18

**seqtk** (`seqtk telo`) — telomere identification
Li, H. (n.d.). *seqtk: Toolkit for processing sequences in FASTA/Q formats* [Computer software]. GitHub. https://github.com/lh3/seqtk

### 5. Quality assessment

**BUSCO** (v6) and **OrthoDB** (v12)
Tegenfeldt, F., Kuznetsov, D., Manni, M., Berkeley, M., Zdobnov, E. M., & Kriventseva, E. V. (2025). OrthoDB and BUSCO update: Annotation of orthologs with wider sampling of genomes. *Nucleic Acids Research*, *53*(D1), D516–D522. https://doi.org/10.1093/nar/gkae987

**Merqury**
Rhie, A., Walenz, B. P., Koren, S., & Phillippy, A. M. (2020). Merqury: Reference-free quality, completeness, and phasing assessment for genome assemblies. *Genome Biology*, *21*, Article 245. https://doi.org/10.1186/s13059-020-02134-9

**BlobToolKit**
Challis, R., Richards, E., Rajan, J., Cochrane, G., & Blaxter, M. (2020). BlobToolKit – Interactive quality assessment of genome assemblies. *G3: Genes, Genomes, Genetics*, *10*(4), 1361–1374. https://doi.org/10.1534/g3.119.400908

### 6. Annotation

**EDTA** — transposable elements
Ou, S., Su, W., Liao, Y., Chougule, K., Agda, J. R. A., Hellinga, A. J., Lugo, C. S. B., Elliott, T. A., Ware, D., Peterson, T., Jiang, N., Hirsch, C. N., & Hufford, M. B. (2019). Benchmarking transposable element annotation methods for creation of a streamlined, comprehensive pipeline. *Genome Biology*, *20*, Article 275. https://doi.org/10.1186/s13059-019-1905-y

**RepeatExplorer2** — tandem repeats (Illumina reads)
Novák, P., Neumann, P., & Macas, J. (2020). Global analysis of repetitive DNA from unassembled sequence reads using RepeatExplorer2. *Nature Protocols*, *15*(11), 3745–3776. https://doi.org/10.1038/s41596-020-0400-y

**Tandem Repeats Finder (TRF)** — tandem repeats (assembly)
Benson, G. (1999). Tandem repeats finder: A program to analyze DNA sequences. *Nucleic Acids Research*, *27*(2), 573–580. https://doi.org/10.1093/nar/27.2.573

**Infernal** — non-coding RNA genes
Nawrocki, E. P., & Eddy, S. R. (2013). Infernal 1.1: 100-fold faster RNA homology searches. *Bioinformatics*, *29*(22), 2933–2935. https://doi.org/10.1093/bioinformatics/btt509

**Rfam** — RNA family database
Ontiveros-Palacios, N., Cooke, E., Nawrocki, E. P., Triebel, S., Marz, M., Rivas, E., Griffiths-Jones, S., Petrov, A. I., Bateman, A., & Sweeney, B. (2025). Rfam 15: RNA families database in 2025. *Nucleic Acids Research*, *53*(D1), D258–D267. https://doi.org/10.1093/nar/gkae1023

**tRNAscan-SE** — tRNA genes
Chan, P. P., Lin, B. Y., Mak, A. J., & Lowe, T. M. (2021). tRNAscan-SE 2.0: Improved detection and functional classification of transfer RNA genes. *Nucleic Acids Research*, *49*(16), 9077–9096. https://doi.org/10.1093/nar/gkab688

**HISAT2** — RNA-seq alignment
Kim, D., Paggi, J. M., Park, C., Bennett, C., & Salzberg, S. L. (2019). Graph-based genome alignment and genotyping with HISAT2 and HISAT-genotype. *Nature Biotechnology*, *37*(8), 907–915. https://doi.org/10.1038/s41587-019-0201-4

**BRAKER3** — protein-coding gene prediction (OrthoDB protein evidence: see BUSCO/OrthoDB above)
Gabriel, L., Brůna, T., Hoff, K. J., Ebel, M., Lomsadze, A., Borodovsky, M., & Stanke, M. (2024). BRAKER3: Fully automated genome annotation using RNA-seq and protein evidence with GeneMark-ETP, AUGUSTUS, and TSEBRA. *Genome Research*, *34*(5), 769–777. https://doi.org/10.1101/gr.278090.123

**EnTAP** — functional annotation
Hart, A. J., Ginzburg, S., Xu, M. S., Fisher, C. R., Rahmatpour, N., Mitton, J. B., Paul, R., & Wegrzyn, J. L. (2020). EnTAP: Bringing faster and smarter functional annotation to non-model eukaryotic transcriptomes. *Molecular Ecology Resources*, *20*(2), 591–604. https://doi.org/10.1111/1755-0998.13106

**eggNOG-mapper** and **eggNOG** database
Cantalapiedra, C. P., Hernández-Plaza, A., Letunic, I., Bork, P., & Huerta-Cepas, J. (2021). eggNOG-mapper v2: Functional annotation, orthology assignments, and domain prediction at the metagenomic scale. *Molecular Biology and Evolution*, *38*(12), 5825–5829. https://doi.org/10.1093/molbev/msab293

Huerta-Cepas, J., Szklarczyk, D., Heller, D., Hernández-Plaza, A., Forslund, S. K., Cook, H., Mende, D. R., Letunic, I., Rattei, T., Jensen, L. J., von Mering, C., & Bork, P. (2019). eggNOG 5.0: A hierarchical, functionally and phylogenetically annotated orthology resource based on 5090 organisms and 2502 viruses. *Nucleic Acids Research*, *47*(D1), D309–D314. https://doi.org/10.1093/nar/gky1085

**InterProScan**
Jones, P., Binns, D., Chang, H.-Y., Fraser, M., Li, W., McAnulla, C., McWilliam, H., Maslen, J., Mitchell, A., Nuka, G., Pesseat, S., Quinn, A. F., Sangrador-Vegas, A., Scheremetjew, M., Yong, S.-Y., Lopez, R., & Hunter, S. (2014). InterProScan 5: Genome-scale protein function classification. *Bioinformatics*, *30*(9), 1236–1240. https://doi.org/10.1093/bioinformatics/btu031

**KofamScan** — KEGG orthology assignment
Aramaki, T., Blanc-Mathieu, R., Endo, H., Ohkubo, K., Kanehisa, M., Goto, S., & Ogata, H. (2020). KofamKOALA: KEGG Ortholog assignment based on profile HMM and adaptive score threshold. *Bioinformatics*, *36*(7), 2251–2252. https://doi.org/10.1093/bioinformatics/btz859

**KEGG** database
Kanehisa, M., Furumichi, M., Sato, Y., Matsuura, Y., & Ishiguro-Watanabe, M. (2025). KEGG: Biological systems database as a model of the real world. *Nucleic Acids Research*, *53*(D1), D672–D677. https://doi.org/10.1093/nar/gkae909

**Gene Ontology**
Gene Ontology Consortium. (2023). The Gene Ontology knowledgebase in 2023. *Genetics*, *224*(1), Article iyad031. https://doi.org/10.1093/genetics/iyad031

### 7. Additional analyses

**BLAST+** — *in silico* hybridizations (satellite DNA, NUPTs and NUMTs)
Camacho, C., Coulouris, G., Avagyan, V., Ma, N., Papadopoulos, J., Bealer, K., & Madden, T. L. (2009). BLAST+: Architecture and applications. *BMC Bioinformatics*, *10*, Article 421. https://doi.org/10.1186/1471-2105-10-421

**DIAMOND** — protein alignment for intragenomic synteny
Buchfink, B., Reuter, K., & Drost, H.-G. (2021). Sensitive protein alignments at tree-of-life scale using DIAMOND. *Nature Methods*, *18*(4), 366–368. https://doi.org/10.1038/s41592-021-01101-x

**MCScanX** — intragenomic synteny
Wang, Y., Tang, H., DeBarry, J. D., Tan, X., Li, J., Wang, X., Lee, T., Jin, H., Marler, B., Guo, H., Kissinger, J. C., & Paterson, A. H. (2012). MCScanX: A toolkit for detection and evolutionary analysis of gene synteny and collinearity. *Nucleic Acids Research*, *40*(7), Article e49. https://doi.org/10.1093/nar/gkr1293

---

## Acknowledgements

This research was supported by the projects "El modelo agrícola de Almería ante el cambio global. Propuestas desde la genómica de la agrobiodiversidad (OrphanEvolGen)" (PID2023-146207OB-I00), funded by the 2023 Call for Knowledge Generation Projects and associated predoctoral training actions of the Spanish Ministry of Science and Innovation, and "Puesta en valor del cultivo huérfano etíope *Moringa stenopetala* mediante la secuenciación y anotación funcional de su genoma (shiferawgenome)" (UAL2024_1), funded by the 2024 Plan Propio for International Cooperation (Program I) of the University of Almería, granted to Dr. Lorenzo Carretero-Paulet.
