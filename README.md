# Language Identification for Low-Resource Formosan Languages

Two benchmarks for Formosan language identification. See details in the [paper](https://lrec.elra.info/lrec2026-ws-sigul-24)!

- **Curated by:** Henry Gagnier
- **Language(s) (NLP):** Amis (ami), Bunun (bnn), Rukai (dru), Paiwan (pwn), Puyuma (pyu), Thao (ssf), Sakizaya (szy), Tao (tao), Atayal (tay), and Truku (trv), Kavalan (ckv)
- **License:** MIT

## Citation

```
@inproceedings{gagnier-2026-language,
  title = {Language Identification for Low-Resource Formosan Languages },
  author = {Gagnier, Henry},
  booktitle = {Proceedings of the SIGUL 2026 Joint Workshop with ELE, EURALI, and DCLRL "Towards Inclusivity and Equality: Language Resources and Technologies for Under-Resourced and Endangered Languages},
  month = {May},
  year = {2026},
  pages = {242--252},
  address = {Palma, Mallorca, Spain},
  publisher = {European Language Resources Association (ELRA)},
  editor = {Kr. Ojha, Atul and Sakti, Sakriani and Soria, Claudia and Melero, Maite and P. McCrae, John and Lignos, Constantine and Liu, Chao-Hong and Rigau Claramunt, German and Rehm, Georg},
  doi = {10.63317/2mkubmvbs4wv},
  abstract = {Formosan languages are a critically endangered group of Austronesian languages spoken in Taiwan, with severely limited representation in natural language processing (NLP) research and no support in existing language identification (LID) tools. We present the first systematic evaluation of machine learning models for the language identification of Kavalan, a Formosan language with fewer than 300 known speakers. We construct two benchmarks: a deployment-oriented benchmark with languages commonly confused with Kavalan by existing tools, and a linguistically motivated benchmark of typologically related Formosan languages. We evaluate random forest, support vector machine (SVM), and three pre-trained multilingual models using repeated stratified cross-validation. SVM models with character n-gram features achieve the strongest performance on both benchmarks, with a macro F1 of 0.993 on the deployment benchmark and a macro F1 of 0.906 on the Formosan benchmark, while remaining computationally inexpensive and effective with a low amount of data. Pre-trained multilingual models degrade significantly on the Formosan benchmark, with XLM-RoBERTa falling to a macro F1 of 0.505. These results demonstrate that traditional n-gram-based approaches are effective with low-resource Formosan LID and establish a foundation for downstream NLP tasks supporting the documentation and revitalization of low-resource Formosan languages.}
}
```
