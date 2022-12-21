# Myosin10-full-KO-RNAseq

Paper summary:
The oocyte must grow and mature before fertilization, thanks to a close dialogue with the somatic cells which surround it. Part of this communication is through filopodialike protrusions, called transzonal projections (TZPs), sent by the somatic cells to the oocyte membrane. To investigate the contribution of TZPs to oocyte quality, we impaired their structure by generating a full knockout mouse of the TZP structural component Myosin-X (MYO10). Using spinning disk and super-resolution microscopy combined with a machine learning approach to phenotype oocyte morphology, we show that the lack of Myo10 decreases TZP density during oocyte growth. Reduction in TZPs does not prevent oocyte growth but impairs oocyte-matrix integrity. Importantly, we reveal by transcriptomic analysis that gene expression is altered in TZP-deprived oocytes, and that oocyte maturation and subsequent early embryonic development are partially affected, effectively reducing mouse fertility. We propose that TZPs play a role in the structural integrity of the germline-somatic complex, which is essential for regulating gene expression in the oocyte and thus its developmental potential.

File description:

Workflow-Step1._Fastq_Quality_Control_with_FASTQC_and_MultiQC.ga : Sequencing quality control with FastQC + multiQC 

Workflow-Step2._Alignement_Bowtie2_QC_alignement_MultiQC.ga : Alignment with Bowtie2 and alignment QC with MultiQC

Workflow-Step3._DESeq2_analysis_with_featurecounts_MQ10___plots_and_QC.ga : DESeq2 analysis with featurecounts MQ10;  plots and QC

Workflow-Step4._Reformate_DESeq2_outputs.ga : Reformate DESeq2 outputs, significant data Padj<0.05

Reference genome :
Ensembl_GTF_Mus_musculus.GRCm38.94
PRJEB56821
