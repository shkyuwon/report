Representative Orthologs Identifier

REPRESENTATIVE ORTHOLOGS
The main concept is designating a representative gene of in-paralogs (co-orthologs) which stands for the most conserved genes that are assigned based on the phylogenetic tree between all member of orthologs including the co-orthologs in the other species (Figure a). If the in-paralogs are ancestral genes, the software designates a representative gene among the ancestral in-paralogs and finally the descendant genes are assigned to the representative genes (Figure b).

SUPPORTS
Windows 64bit and Linux(with Mono runtime)

USAGE
report.exe  <newick tree file path> <output file path> <outgroup species list separated with a blank>
	The gene name should consist of species name and gene number separated by ‘_’ letter.
	Ex) A gene of Oryza sativa: osativa_1 or O.sativa_1

Example:
(Microsoft Windows 32bit/64bit) 
report.exe sample1.tre result.txt H.vulgare B.distachyon
(Linux)
mono report.exe sample1.tre result.txt H.vulgare B.distachyon

