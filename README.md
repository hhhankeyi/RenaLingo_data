# RenaLingo_data

## Introduction
### AI Prompts for VQA Construction
The prompts used by GPT-5 to construct VQA tasks. The prompt language, physician assessment language, and case information language are all Chinese.
LM Fundamental Pathology VQAs
- The prompt used for generating LM-based fundamental pathology VQAs is as follows:
  •	Expert knowledge framework: S.II 1.1 LM_Expert_knowledge_framework
  •	Prompt: S.II 1.2 LM_prompt
EM Fundamental Pathology VQAs
- The prompt used for generating EM-based fundamental pathology VQAs is as follows:
  •	Expert knowledge framework: S.II 2.1 EM_Expert_knowledge_framework
  •	Prompt: S.II 2.2 EM_prompt
IF Intensity Fundamental Pathology VQAs
- The prompt used for generating IF-intensity fundamental pathology VQAs is as follows:
  •	Prompt: S.II 3.1 IF_intensity_prompt
IF Deposition Fundamental Pathology VQAs
- The prompt used for generating IF-deposition fundamental pathology VQAs is as follows:
  •	Expert knowledge framework: S.II 4.1 IF_deposition_Expert_knowledge_framework
  •	Prompt: S.II 4.2 IF_deposition_prompt
Integrative Diagnostic VQAs
- The prompt used for generating integrative diagnostic VQAs is as follows:
  •	Prompt: S.II 5.1 Diagnose_prompt

### AI Prompts for Evaluation
The prompts are used during the evaluation experiments. The prompt language, physician assessment language, and case information language are all Chinese.
Fundamental Pathology VQAs
Using IF-intensity VQAs as an example, the evaluation pipeline consisted of three stages.
1.	Modality-aware guidance generation (GPT-5.1):
o	Prompt: S.III 1.1 Fundamental_GPT5.1
2.	ROI-aware evidence extraction (Gemini-2.5-Pro):
o	Prompt: S.III 1.2 Fundamental_Gemini2.5Pro
3.	Clinicopathological diagnosis (Gemini-2.5-Pro):
o	Prompt: S.III 1.3 Fundamental_Gemini2.5Pro
Integrative Diagnostic VQAs
For integrative diagnostic VQAs, the evaluation pipeline similarly consisted of three stages.
1.	Modality-aware guidance generation (GPT-5.1):
o	Prompt: S.III 2.1 Diagnose_GPT5.1
2.	ROI-aware evidence extraction (Gemini-2.5-Pro):
o	Prompt: S.III 2.2 Diagnose_Gemini2.5Pro
3.	Clinicopathological diagnosis (Gemini-2.5-Pro):
o	Prompt: S.III 2.3 Diagnose_Gemini2.5Pro

## License
This project is licensed under the MIT License.
