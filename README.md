# Semana7

`
MFVFLVLLPLVSSQCVNLTTRTQLPPAYTNSFTRGVYYPDKVFRSSVLHSTQDLFLPFFS
NVTWFHAIHVSGTNGTKRFDNPVLPFNDGVYFASTEKSNIIRGWIFGTTLDSKTQSLLIV
NNATNVVIKVCEFQFCNDPFLGVYYHKNNKSWMESEFRVYSSANNCTFEYVSQPFLMDLE
GKQGNFKNLREFVFKNIDGYFKIYSKHTPINLVRDLPQGFSALEPLVDLPIGINITRFQT
LLALHRSYLTPGDSSSGWTAGAAAYYVGYLQPRTFLLKYNENGTITDAVDCALDPLSETK
CTLKSFTVEKGIYQTSNFRVQPTESIVRFPNITNLCPFGEVFNATRFASVYAWNRKRISN
CVADYSVLYNSASFSTFKCYGVSPTKLNDLCFTNVYADSFVIRGDEVRQIAPGQTGKIAD
YNYKLPDDFTGCVIAWNSNNLDSKVGGNYNYLYRLFRKSNLKPFERDISTEIYQAGSTPC
NGVEGFNCYFPLQSYGFQPTNGVGYQPYRVVVLSFELLHAPATVCGPKKSTNLVKNKCVN
FNFNGLTGTGVLTESNKKFLPFQQFGRDIADTTDAVRDPQTLEILDITPCSFGGVSVITP
GTNTSNQVAVLYQDVNCTEVPVAIHADQLTPTWRVYSTGSNVFQTRAGCLIGAEHVNNSY
ECDIPIGAGICASYQTQTNSPRRARSVASQSIIAYTMSLGAENSVAYSNNSIAIPTNFTI
SVTTEILPVSMTKTSVDCTMYICGDSTECSNLLLQYGSFCTQLNRALTGIAVEQDKNTQE
VFAQVKQIYKTPPIKDFGGFNFSQILPDPSKPSKRSFIEDLLFNKVTLADAGFIKQYGDC
LGDIAARDLICAQKFNGLTVLPPLLTDEMIAQYTSALLAGTITSGWTFGAGAALQIPFAM
QMAYRFNGIGVTQNVLYENQKLIANQFNSAIGKIQDSLSSTASALGKLQDVVNQNAQALN
TLVKQLSSNFGAISSVLNDILSRLDKVEAEVQIDRLITGRLQSLQTYVTQQLIRAAEIRA
SANLAATKMSECVLGQSKRVDFCGKGYHLMSFPQSAPHGVVFLHVTYVPAQEKNFTTAPA
ICHDGKAHFPREGVFVSNGTHWFVTQRNFYEPQIITTDNTFVSGNCDVVIGIVNNTVYDP
LQPELDSFKEELDKYFKNHTSPDVDLGDISGINASVVNIQKEIDRLNEVAKNLNESLIDL
QELGKYEQYIKWPWYIWLGFIAGLIAIVMVTIMLCCMTSCCSCLKGCCSCGSCCKFDEDDSEPVLKGVKLHYT
`


*** Formatting options

max_target_seqs	integer	500	Number of aligned sequences to keep. Use with report formats that do not have separate definition line and alignment sections such as tabular (all outfmt > 4). Not compatible with num_descriptions or num_alignments. Ties are broken by order of sequences in the database.
max_hsps	integer	none	Maximum number of HSPs (alignments) to keep for any single query-subject pair. The HSPs shown will be the best as judged by expect value. This number should be an integer that is one or greater. If this option is not set, BLAST shows all HSPs meeting the expect value criteria. Setting it to one will show only the best HSP for every query-subject pair


 -outfmt <String>
   alignment view options:
     0 = pairwise,
     1 = query-anchored showing identities,
     2 = query-anchored no identities,
     3 = flat query-anchored, show identities,
     4 = flat query-anchored, no identities,
     5 = XML Blast output,
     6 = tabular,
     7 = tabular with comment lines,
     8 = Text ASN.1,
     9 = Binary ASN.1,
    10 = Comma-separated values,
    11 = BLAST archive format (ASN.1) 

   Options 6, 7, and 10 can be additionally configured to produce
   a custom format specified by space delimited format specifiers.
   The supported format specifiers are:
           qseqid means Query Seq-id
              qgi means Query GI
             qacc means Query accesion
          qaccver means Query accesion.version
             qlen means Query sequence length
           sseqid means Subject Seq-id
        sallseqid means All subject Seq-id(s), separated by a ';'
              sgi means Subject GI
           sallgi means All subject GIs
             sacc means Subject accession
          saccver means Subject accession.version
          sallacc means All subject accessions
             slen means Subject sequence length
           qstart means Start of alignment in query
             qend means End of alignment in query
           sstart means Start of alignment in subject
             send means End of alignment in subject
             qseq means Aligned part of query sequence
             sseq means Aligned part of subject sequence
           evalue means Expect value
         bitscore means Bit score
            score means Raw score
           length means Alignment length
           pident means Percentage of identical matches
           nident means Number of identical matches
         mismatch means Number of mismatches
         positive means Number of positive-scoring matches
          gapopen means Number of gap openings
             gaps means Total number of gaps
             ppos means Percentage of positive-scoring matches
           frames means Query and subject frames separated by a '/'
           qframe means Query frame
           sframe means Subject frame
             btop means Blast traceback operations (BTOP)
          staxids means Subject Taxonomy ID(s), separated by a ';'
        sscinames means Subject Scientific Name(s), separated by a ';'
        scomnames means Subject Common Name(s), separated by a ';'
       sblastnames means Subject Blast Name(s), separated by a ';'
                (in alphabetical order)
       sskingdoms means Subject Super Kingdom(s), separated by a ';'
                (in alphabetical order) 
           stitle means Subject Title
       salltitles means All Subject Title(s), separated by a '&lt;&gt;'
          sstrand means Subject Strand
            qcovs means Query Coverage Per Subject
          qcovhsp means Query Coverage Per HSP
