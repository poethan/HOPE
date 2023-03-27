# HOPE: A Task-Oriented and Human-Centric Evaluation Framework Using Professional Post-Editing Towards More Effective MT Evaluation

<img src="https://github.com/aaronlifenghan/HOPE/blob/main/HOPE_metric_logo-v2.png" width=200>


Place holder for data sharing for translation evaluation framework HOPE: a human-centric and task-oriented MT evaluation framework using professional post-editing

**Abstract**

Traditional automatic evaluation metrics for machine translation have been widely criticized by linguists due to their low accuracy, lack of transparency, focus on language mechanics rather than semantics, and low agreement with human quality evaluation. Human evaluations in the form of MQM-like scorecards have always been carried out in real industry setting by both clients and translation service providers (TSPs). However, traditional human translation quality evaluations are costly to perform and go into great linguistic detail, raise issues as to  
inter-rater reliability (IRR) and are not designed to measure quality of worse than premium quality translations. 
In this work, we introduce \textbf{HOPE}, a task-oriented and  \textit{\textbf{h}}uman-centric evaluation framework for machine translation output based \textit{\textbf{o}}n professional \textit{\textbf{p}}ost-\textit{\textbf{e}}diting annotations. It contains only a limited number of commonly occurring error types, and uses a scoring model with geometric progression of error penalty points (EPPs) reflecting error severity level to each translation unit.  
The initial experimental work carried out on English-Russian language pair MT outputs on marketing content type of text from highly technical domain reveals that our evaluation framework is quite  effective in reflecting the MT output quality regarding both overall system-level performance and segment-level transparency, and it increases the IRR for error type interpretation. 
The approach has several key advantages, such as ability to measure and compare less than perfect MT output from different systems, ability to indicate human perception of quality, immediate estimation of the labor effort required to bring MT output to premium quality, low-cost and faster application, as well as higher IRR. Our experimental data is available at [Git-HOPE](https://github.com/lHan87/HOPE)

**File instruction**: 
"Test22-scoring-10-9-2021.xlsm": the 111 segments of English-to-Russian MT using GoogleMT and another System, including data of human offered reference translations, scoring sheeting using HOPE evaluation framework. 
Open-source for non-profit research. 
For comercial usage, please contact: @copyright Logrus Global <serge.gladkoff [at] logrusglobal.com> https://logrusglobal.com 

**PPT-download, presentation and demo** [Here](https://drive.google.com/drive/folders/1lOSiMe3cFmzSt6vtovJGU6MZ8t2bs_0Y?usp=sharing) and [Here](https://drive.google.com/drive/folders/1sajkcrnDgTOFiYVkFjYqh9EDYUhneYqA?usp=sharing) 

------------------------
Reference:

Serge Gladkoff and Lifeng Han. 2022. HOPE: A Task-Oriented and Human-Centric Evaluation Framework Using Professional Post-Editing Towards More Effective MT Evaluation. In Proceedings of the Thirteenth Language Resources and Evaluation Conference, pages 13–21, Marseille, France. European Language Resources Association.

@inproceedings{gladkoff-han-2022-hope,
    title = "{HOPE}: A Task-Oriented and Human-Centric Evaluation Framework Using Professional Post-Editing Towards More Effective {MT} Evaluation",
    author = "Gladkoff, Serge  and
      Han, Lifeng",
    booktitle = "Proceedings of the Thirteenth Language Resources and Evaluation Conference",
    month = jun,
    year = "2022",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2022.lrec-1.2",
    pages = "13--21",
    abstract = "Traditional automatic evaluation metrics for machine translation have been widely criticized by linguists due to their low accuracy, lack of transparency, focus on language mechanics rather than semantics, and low agreement with human quality evaluation. Human evaluations in the form of MQM-like scorecards have always been carried out in real industry setting by both clients and translation service providers (TSPs). However, traditional human translation quality evaluations are costly to perform and go into great linguistic detail, raise issues as to inter-rater reliability (IRR) and are not designed to measure quality of worse than premium quality translations. In this work, we introduce \textbf{HOPE}, a task-oriented and \textit{ \textbf{h} }uman-centric evaluation framework for machine translation output based \textit{ \textbf{o} }n professional \textit{ \textbf{p} }ost-\textit{ \textbf{e} }diting annotations. It contains only a limited number of commonly occurring error types, and uses a scoring model with geometric progression of error penalty points (EPPs) reflecting error severity level to each translation unit. The initial experimental work carried out on English-Russian language pair MT outputs on marketing content type of text from highly technical domain reveals that our evaluation framework is quite effective in reflecting the MT output quality regarding both overall system-level performance and segment-level transparency, and it increases the IRR for error type interpretation. The approach has several key advantages, such as ability to measure and compare less than perfect MT output from different systems, ability to indicate human perception of quality, immediate estimation of the labor effort required to bring MT output to premium quality, low-cost and faster application, as well as higher IRR. Our experimental data is available at \url{https://github.com/lHan87/HOPE}.",
}
