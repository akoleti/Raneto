/*
Title: NLP-based information extraction for cancer-related EHR notes
*/


1. Work focuses on extracting information to `improve cancer screening efficiency`.

2. Capture important clinical information on cancer, ranging from information about `tissue specimens` to `disease-related` and outcome information

3. Facilitate translational research by associating `molecular information` with `disease phenotype`

4. `Biomarkers` and `cancer prognosis` are frequently stored in free-text surgical pathology reports

5. <a href="https://pubmed.ncbi.nlm.nih.gov/29155996/">Hierarchical attention networks` </a> for information extraction from cancer pathology reports such as primary cancer site and histological grade which are gathered by cancer registries.

6.  ‘frame semantics’. <a href="https://framenet.icsi.berkeley.edu/fndrupal/">FrameNet</a>: A Knowledge Base for Natural Language Processing.
example, consider that a radiology report may contain tumor information such as “There is a single lesion in segment 7 measuring 1.5 × 1.9 cm”. This evokes a TUMOR DESCRIPTION frame with three elements present: Count (“Single”), Anatomical Site (“segment 7”), and Size (“1.5 × 1.9 cm”).

7. Document-level text classification methods  often application specific and not re-purposable

8.  A binary classifier to determine whether a clinical report is about a potential malignant liver lesion requiring follow up

9. Unspecific extraction methods were used like concept recognition and named entity recognition techniques 

10. MetaMap (identify phrases but do not attempt to connect these to their wider context)

11. cTAKES (identify phrases but do not attempt to connect these to their wider context)

12. Cancer grade information

13. general-purpose cancer NLP resource.

14. This effort would identify widely-needed cancer information types and create an NLP system that supports a broad range of use cases

15. consider what a set of frames for cancer would look like when targeted toward NLP for EHR notes

16. 