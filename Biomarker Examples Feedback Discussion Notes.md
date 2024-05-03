# Biomarker Examples Feedback Discussion Notes
### Participants: Darren Natale, Raja Mazumder, Daniall Masood, Vania Ballesteros
### 05/01/2024


A discussion with Professor Darren Natale, ontology expert and collaborator, was held on 05/01/2024 to obtain feedback on the curated biomarker examples. The examples can be found here: [Curated Biomarker Examples](https://docs.google.com/spreadsheets/d/1vZ68E8K5j0_ipmV4JpRd8YhTL6ib04NjCLT7lCTu4OM/edit?usp=sharing)

Professor Natale annotated specific cells within the dataset using distinct colors in preparation for further discussion. The bullet points below address the main points of the discussion.

-	To start, green colored cells that contained the physiologic biomarkers dilated pupil and increased jaw tremor, were added to the ontology under the category of bodily movement. Other examples like abnormal gait and constricted pupil would also fit under this new category.

-	For the biomarkers in the red colored cells Presence of Aβ plaques and Presence of Aβ plaques in PET, it was agreed that the technology used for biomarker detection should not be part of the biomarker; in this case the biomarker addressed would only be Presence of Aβ plaques. This would also apply to the biomarker Presence of radiographic pulmonary infiltrates, which would instead be Presence of pulmonary infiltrates. It was instead proposed that the technology used could be added as a comment.

-	The specimen category should have data on how the information is being collected. However, for radiographic biomarkers it is unclear whether the name of the organ being imaged (eg: Lung), the word image, or simply no description should go in this field. For this dataset, the specimen category of radiographic biomarkers was registered as image, but further discussion is needed to reach a consensus on this topic.

-	The assessed entity type of the DSP 7901delG mutation biomarker was registered as DSP. This is wrong because the entire gene is not being assessed, only the specific mutation is. The correct assessed entity type is DSP 7901delG.

-	The assessed biomarker entity ID should source back to the most accurate accession for the entity type. For instance, NCBI: 1832 was used as the ID for DSP, however a better accession to use would be HGNC:3052 because it is the primary source. Referencing the previous point, for the corrected entity DSP 7901delG, which refers to a polymorphism; the best accession to use is rs397514039 from dbSNP. Similarly, for the entity Aβ plaque, the best accession to use would be BTO:0002774 because it addresses the correct entity.

-	For the biomarker increased ESR, the best biomarker role category was registered as predictive. This is incorrect because predictive is a category only associated with exposure biomarkers, but this is an example of a medical condition.

-	The examples for activity biomarkers do not fall under that category because concentrations or levels are being measured but not the activity itself. Examples for activity biomarkers are still unclear.
