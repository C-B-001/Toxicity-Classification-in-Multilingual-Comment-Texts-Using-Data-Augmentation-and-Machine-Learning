# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Contextual Augmentation: Data Augmentation by Words with Paradigmatic Relations

  - **[Link]()**https://arxiv.org/pdf/1805.06201
  - **Objective**: The paper presents data augmentation by a new method named Contextual augmentation.
  - **Methods**: They replace words in a text with other words found on the context (the surrounding words) of the word to replace.
  - **Outcomes**: The results are good.
  - **Relation to the Project**: We used this approach for data augmentation.

- **Source 2**: Low Resource Text Classification with ULMFit and Backtranslation.
  
  - **[Link]()** https://arxiv.org/abs/1903.09244![grafik](https://github.com/user-attachments/assets/0bc0f64e-f9ff-4271-9857-c22a94e92874)
  - **Objective**: The paper compares different approaches od data augmentation in NLP. One method is Backtranslation.
  - **Methods**: For Backtranslation, a text is translated from its original language to a different language. This translation is then translated back to the original language. The resulting augmented text usually shows some differences to the original text.
  - **Outcomes**: Using augmented data created by backtranslation improves the performance. Especially in datasets with few samples, backtranslation is better than another augmentation method used by the authors.
  - **Relation to the Project**: We used Backtranslation for our project, but we also used the translations to different languages to create augmented data in multiple languages.

