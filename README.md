# Publicly-available clinical datasets

## EHR records:
[MIMIC-IV](https://www.nature.com/articles/s41597-022-01899-x) | [dataset](https://physionet.org/content/mimiciv/2.2/)
  - Contains ICU-only EHR structured data, text, and images for nearly 300k patients

[MIMIC-III](https://www.nature.com/articles/sdata201635) | [dataset](https://physionet.org/content/mimiciii/1.4/)
  - Contains ICU-only EHR structured data, text, and images for nearly 40k patients

[MIMIC-III CareVue subset](https://physionet.org/content/mimic3-carevue/1.4/)
  - Contains subset of MIMIC-III patients not included in MIMIC-IV

[eICU](https://www.nature.com/articles/sdata2018178) | [dataset](https://physionet.org/content/eicu-crd/2.0/)
  - ICU-only EHR structured data from across the US for 200k admissions

[MOVER](https://mover.ics.uci.edu/index.html)
  - Hospital visit data for surgery patients at UCI.
  - Comprehensive EMR records and waveforms for each patient encounter
  - Contains patient information, medical history, and specific surgical procedure information including: medicines used, lines or drains used, and post-operative complications
  - 58,799 unique patients with data from 83,468 surgeries. Data spans over 4 years.

## Manually Annotated datasets:
[CORAL](https://arxiv.org/abs/2308.03853) | [dataset](https://physionet.org/content/curated-oncology-reports/1.0/)
  - Expert-labeled: 20 breast cancer and 20 pancreatic cancer de-identified progress notes from UCSF, comprehensively annotated
  - Unannotated: 100 breast cancer and 100 pancreatic cancer de-identified progress notes from UCSF, auto-labeled with GPT-4
  - Expert-labeled subset should only be used as a test-set 

[RadQA: A Question Answering Dataset to Improve Comprehension of Radiology Reports](https://aclanthology.org/2022.lrec-1.672/) | [dataset](https://physionet.org/content/radqa/1.0.0/)
  - 1000+ expert-annotated radiology reports from MIMIC-III

[CliniQG4QA: Generating Diverse Questions for Domain Adaptation of Clinical Question Answering](https://github.com/sunlab-osu/CliniQG4QA/)
  - 1287 annotated QA pairs on 36 sampled discharge summaries from MIMIC-III Clinical Notes

[MedAlign: A Clinician-Generated Dataset for Instruction Following with Electronic Medical Records](https://arxiv.org/abs/2308.14089) | [awaiting dataset]
  - Instruction-tuning dataset of 983 questions/instructions from 7 speciaties
  - Specialties include: Internal Medicine, Neurology, Radiology, Cardiology, Oncology, Surgery, and Primary Care
  - 303 are expert-labeled, with EHR references for correct answers also annotated
  - Reference EHR contains structured and note data 

n2c2/i2b2 shared task datasets

## Other datasets:
[CliCR](https://aclanthology.org/N18-1140/)
  - Nearly 100k automated queries from 11,846 clinical case reports for question answering / reading comprehension
    
[EMR-QA](https://aclanthology.org/D18-1258/)
  - i2b2 datasets repurposed for question answering
  - 400,000+ question-answer evidence pairs and 1 million questions-logical forms

[PMC-Patients](https://github.com/pmc-patients/pmc-patients)
  - 167k patient summaries from PMC case reports
  - 3.1M patient-article relevance and 293k patient-patient similarity annotations defined by PubMed citation graph

[Med-HALT: Medical Domain Hallucination Test for Large Language Models](https://github.com/medhalt/medhalt)
  - Medical exam and Pubmed QA datasets
  - Combination of 7 datasets: MedMCQA, HEADQA, MedQA USMILE, MedQA Taiwan, Pubmed

[Benchmarking Large Language Models on Answering and Explaining Challenging Medical Questions](https://arxiv.org/abs/2402.18060) | [dataset](https://github.com/HanjieChen/ChallengeClinicalQA)
  - JAMA Clinical Challenge dataset containing questions based on challenging clinical cases
  - Medbullets comprising USMLE Step 2&3 style clinical questions
  - All are multiple-choice question-answering tasks
  - Each question is accompanied by an expert-written explanation

## Synthetic data:
[Asclepius](https://arxiv.org/abs/2309.00237)
