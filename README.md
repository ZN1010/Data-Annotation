Annotation Guideline:

1. Every dialogue will come with 3 annotation questions.

2. The first question asks about whether the summary is a nonspecific template of the source dialogue. As long as a summary is somewhat specific to the dialogue (e.g., they share the same topic), we mark it as "f" (aka false). **An nonspecific template is a general template that is not directly related to the dialogue, and we mark it as "t" (aka true)**. For example, "可以加关注，有问题再咨询。", "祝您身体健康", "祝宝宝早日康复", and "建议你平时多了解下病毒的相关知识。" are nonspecific templates. We expect that most of the summaries in the dataset are NOT nonspecific templates (FYI, there are only 3 nonspecific templates in the first 30 diaglogues).
 
3. **Medical term asked in both question 2 and 3 refers to a disease name, a treatment method, a medicine name, and any biomedical vocabularies.** For example, "脑出血" and "聚维酮碘溶液" are medical terms. You do not need to treat words that are commonly used in daily life as medical terms. For example, "手术", "睡眠", "棉签", and "诊断" are NOT medical terms.

4. Question 2 asks to find all medical terms in the summary that do not appear in the source dialogue, while questions 3 asks to find all medical terms in the summary that also show up in the source dialogue. When you need to enter multiple medical terms in either question 2 or 3, please use "," (**English version comma**) to seperate each term. Leave it blank if you do not find any medical terms for either question 2 or 3.

5. As **an annotation trick**, it is recommended that you first read the summary. Then, identify all the medical terms in the summary and search ("control-F") each of them in the dialogue. By doing that, you should be able to answer question 2 and 3. Finally, after you become more familar with the summary and the dialogue, answer question 1. You don't have to enter text. Just search ("control-F"), copy-paste, and modify "t or f" to either "t" or "f".



The first 30 dialogues (IDs from 2 to 64) and the last 400 dialogues (IDs from 2130 to 2815) have been annotated. You may take a look at them as some annotation examples. Don't hesitate to contact **njz5124@psu.edu** for further assistance. Thanks!
