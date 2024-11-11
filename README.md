# GMSATD 1.0
This is my MSc thesis project. Currently, the source code is private as it has yet to be presented for the final defense. I will make all files available once I have presented and received the necessary permissions from the school. Stay tuned, and thank you for your understanding!

## Title _"A GENERIC MULTITASK SUMMARIZER FOR AMHARIC TEXT DOCUMENTS"_

## Abstract
The thesis presents a generic multitask summarizer architecture for Amharic text documents, aiming to address the challenges of information overload and automatic text analysis in the digital era. The existing summarization methods are not able to adapt to the specific needs of the user or the document being summarized. They are limited to a single summarization approach to generate summaries, which can lead to suboptimal results. The architecture is designed to accommodate three main summarization tasks and incorporates multiple extractive-based approaches, providing a versatile framework for implementing various extractive text summarization methods. Additionally, the thesis introduces two novel graph-based summarization methods, extending the prominent algorithms TextRank and LexRank. The research investigates the impact of different term weighting methods, similarity measures, and feature weightings on the performance of the proposed summarization system, utilizing datasets collected from diverse Amharic news websites. Prototypes for frequency-based summarization (FBSumer), feature extraction-based summarization (FEBSumer), and graph-based summarization (GraphSumer) have been developed and evaluated using the Java version of the ROUGE toolkit (n-gram) to measure precision, recall, and F-measure. Comparative analysis with related methods in automatic text summarization demonstrates the substantial improvements achieved by the proposed methods. Overall, this work contributes a unique architecture and novel methodologies, advancing the field of automatic text summarization for Amharic text documents and addressing the specific linguistic and contextual challenges inherent to the Amharic language.

**Keywords:** Multitask, Sentence Extraction, Latent Semantic Analysis, Graph-Based Sentence Ranking

## Acknowledgement
First and foremost, I praise the almighty God for his love and for revitalizing my life. Then I would like to thank my advisor Dr. Anubhav Kumar for his valuable comments, support, and guidance. I would also like to thank my family, who at times put me at the edge of my nerve but who always happen to be watching my back, and to my classmates for their undying support and answering all my questions. My heartfelt gratitude goes to my friends because they were never tiered to suggest me new ideas and support me throughout the entire project.

## Design and Implementation of GMSATD
The design and implementation of the proposed generic multitask summarization architecture for Amharic text documents are discussed. The system named as Generic Multitask Summarizer for Amharic Text Documents (GMSATD) is able to solve three main summarization tasks: Generic text-driven summarization, Query-based summarization, and Keyword or Headline generation. To process these tasks, the system provides several extraction-based summarization techniques and approaches.

The global architecture of GMSATD consists of five major modules:
1. **Preprocessing Module**
2. **Input Representation Module**
3. **Sentence Ranking Module**
4. **Sentence Selection Module**
5. **Summary Generation Module**

Each summarization task and technique is parameterizable through user settings. Different instantiations of GMSATD are implemented to accommodate various summarization tasks.

## Project Structure
```
your-repo-name/
│
├── README.md
├── GMSATD/
│   ├── lib/
│   ├── GMSATD.jar
│   └── README.txt
├── snapshots/
│   ├── snapshot1.png
│   ├── snapshot2.png
│   └── ...
├── JRE/
│   └── jre1.8/
│       ├── bin/
│       ├── lib/
│       └── ...
└── LICENSE
```

- `GMSATD.jar`: The executable jar file containing the source code.
- `snapshots/`: Directory containing snapshots of the system.
- `JRE/`: Directory containing the required Java Runtime Environment (JRE) 1.8.

## Usage
1. Ensure you have Java Runtime Environment (JRE) 1.8 installed.
2. Download the `GMSATD.jar` file and place it in a suitable directory.
3. Run the jar file using the command:
   ```sh
   java -jar GMSATD.jar

## Snapshots
Here are some snapshots of the system in action:
![System Snapshot 1](https://github.com/Bushra-KB/GMSATD/snapshots/snap1.jpg) 
![System Snapshot 2](/snapshots/snapshot2.png)

## License
This project is licensed under **the GNU General Public License v3.0**.
