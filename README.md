# ML4RG-Gene-2-birds
Unveiling Bird Morphology Evolution through Deep-Learning Based Image Embedding and Gene Association Testing

*Introduction*

Birds exhibit a wide range of sizes, shapes, colors, and behaviors. This diversity has captured the attention of researchers for centuries.
By expanding our understanding of avian biology, we hope to get a deeper insight into bird evolution, adaptation, ecology or even conservation. \\
Specifically, unraveling the genetic code that defines this plethora of avian coloration is of particular interest for this project. We leveraged the deep learning model CLIP (Contrastive Language-Image Pretraining) from OpenAI in order to analyze the intricate relationship between bird images and their respective genetic information. The CLIP image embeddings were utilized as input to train and evaluate multiple classifiers with the aim to predict the presence or absence of certain coloration genes of interest. The performance of these classifiers was then thoroughly inspected and benchmarked.


*Data overview*

In the project "Unveiling Bird Morphology Evolution through Deep-Learning Based Image
Embedding and Gene Association Testing", we explored the correlation between bird pheno-
types, represented by a dataset of approximately 23,000 bird images, an annotation dataframe
containing the family, subspecies and scientific name of the presented birds, and the corre-
sponding genomes of the birds.
The bird images stem from Birds of the World (“Birds of the world”, 2020) which is propriatary and therefore not included in this repository.
All images were organized into directories based on the respective bird families, encompass-
ing a total of 249 different families. Additionally, we had access to genomic data for 265 bird species.


*Approach*

We selected several classical machine learning and deep learning models to predict the presence or absence
of candidate genes associated with bird coloration using image embeddings from CLIP. The notebooks along with the final presentation and report can be found in this repsository.
