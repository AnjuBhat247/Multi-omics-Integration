# Multi-omics-Integration
<b> _TOWARDS A MULTI-OMICS APPROACH FOR DISEASE-CAUSING MOLECULES IDENTIFICATION USING GRAPH CONVOLUTIONAL NETWORK._ </b>

_This was my internship project of 4 months at Medical Data Laboratory, Hopital L'Archet, Nice._

## ABSTRACT: 
<p align="justify">
The rapid advancement in high-throughput biomedical technologies has enabled the collection of various types of omics data with unprecedented details. While each omics technology can only capture part of the biological complexity, integrating multiple types of omics data can provide a more holistic view of the underlying biological processes. Graph deep learning has recently emerged to incorporate graph structures into a deep learning framework to predict disease causing molecules. Despite the promising results shown by some studies using Graph Convolution Networks (GCNs) in the field of oncology, there is a scarcity of applications in rare diseases, particularly in mitochondrial diseases. Moreover, intellectual disability, another rare disease category, has also received limited attention in the context of multi-omics studies. This neglect can be attributed to various challenges, such as the limited availability of data, the curse of dimensionality inherent in omics data, and the heterogeneous nature of the data associated with these conditions. Consequently, there is a need to address these challenges and explore the potential of GCNs in advancing research and understanding of rare diseases, including mitochondrial diseases and intellectual disability. The recent developments regarding GCN models are a promising resource to enhance the application of multi-omics studies on rare diseases. In order to address this research gap, we have developed a novel GCN model that combines Graph Convolution and GraphSAGE. This model was applied to analyze ten distinct modules of omics data related to mitochondrial diseases, with the aim of accurately classifying genes as pathogenic or non-pathogenic. By employing the best edge weight method tailored to the complexity of each network, our model achieved impressive accuracy ranging from 98% to 100% across the different modules. To further evaluate the model's performance, we also applied it to intellectual disabilities pathology and obtained a remarkable accuracy of 98%. The success of the implemented model in classifying genes as pathogenic or non-pathogenic in both pathologies further highlights the potential of graph deep learning for advancing multi-omics studies and aiding in disease causing molecules diagnosis and treatment.
</p>

## SKILLS USED:
- Python, PyTorch, DGL, NetworkX, Scikit-learn, Pandas, Matplotlib, Seaborn
- GCN, GraphSAGE
- Jupyter, Anaconda, StringDB, GitHub
- Correlation, Entropy, Divergence, Deep Learning, Multi-Omics, Biomedical data

## RESULTS:
- Developed a semi-supervised GCN that improves the molecular identification.
- Achieved 98-99% accuracy by training GCN models on biological pathways and multi-cohort data.

<p align="justify">
<b>Note: </b><br>
- <i>Intellectual_Disabilities.ipynb</i> contains model implementation and complete code related to Intellectual Disabilities Interaction network part. <br>
- <i>Interaction_Brown.ipynb</i> contains same model implementation, but few changes in the code with regard to Mitochondrial Diseases Module. This same notebook can be used to check models' performance on different modules of Mitochondrial Diseases with few changes. Changes to be made are mentioned in the beginning of the notebook.<br>
- <i>Co-Expression_Brown.ipynb</i> notebook contains same model implementation, but few changes in the code with regard to co-expression data of brown module.<br>
- All the necessary data are available in <i>Data</i> folder with seperate folders for 10 modules of Mitochondrial disease and one folder for Intellectual Disability dataset.<br>
- <i>Internship_Final_Report.pdf</i> contains the complete documentation of the project and the results obtained. 
</p>

  ![Candidate_Gene_network_Autism](https://github.com/AnjuBhat247/Multi-omics-Integration/assets/139755515/6acd8977-5744-4778-ba58-f07cc06e78d5)
