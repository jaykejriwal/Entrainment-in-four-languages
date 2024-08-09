# Entrainment-in-four-languages
Python program for understanding the relationship between lexical, syntactic, semantic and auditory entrainment in English, Hungarian, Spanish and Slovak.

## Dataset
We utilized state-of-the-art DNN embeddings such as BERT and TRIpLet Loss network (TRILL) vectors to extract features for measuring lexical, syntactic, semantic and auditory similarities of turns within dialogues in four comparable spoken corpora of four different languages, namely Columbia Games corpus, Budapest Games corpus, UBA Games Corpus and Sk Games corpus. 

The input folder shows the sample files required for processing.

Columbia Games corpus can be downloaded from https://catalog.ldc.upenn.edu/LDC2021S02

UBA Games Corpus is freely available at https://ri.conicet.gov.ar/handle/11336/191235

Slovak Games corpus is available upon request by mailing it to the authors

Budapest Games corpus is available upon request by mailing it to the authors

## Required Software
ffmpeg (Download from https://www.ffmpeg.org/download.html)

sentence-transformers (pip install sentence-transformers)

tensorflow (pip install tensorflow)

textgrid (Install textgrid from https://github.com/kylebgorman/textgrid)

TRILL vectors model (Download from https://tfhub.dev/google/nonsemantic-speech-benchmark/trill/3)

## Execution instruction
Four Jupyter Notebook files are uploaded. Each file presents a step-by-step procedure for extracting features and measuring entrainment at different linguistic levels. 

## Citation
J. Kejriwal and Š. Beňuš, "Lexical, syntactic, semantic and acoustic entrainment in Slovak, Spanish, English, and Hungarian: A cross-linguistic comparison," (2024). Submitted to Speech Communication Journal (decision is major revision). https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4729223
