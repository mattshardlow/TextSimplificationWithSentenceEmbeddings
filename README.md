# TextSimplificationWithSentenceEmbeddings

This repository contains code and system outputs associated with the arxiv paper "Text Simplification with Sentence Embeddings" (Link to be updated)

In this repository you will find the following jupyter notebooks (intended to be run on Google Colab with an A100 with 40GB GPU RAM):
 - Text_Simplification_with_Sentence_Embeddings_part_1_Reconstruction.ipynb - the notebook used to create reconstructions of complex and simple sentences (see Section 4 of the paper)
 - Text_Simplification_with_Sentence_Embeddings_part_2_Reconstruction_Evaluation.ipynb - the notebook used to perform evaluation for the reconstructed embeddings (Section 4)
 - Text_Simplification_with_Sentence_Embeddings_part_3_Neural_Network.ipynb - the notebook used to train a neural network to learn a transformation from complex to simple sentences (Section 5)
 - Text_Simplification_with_Sentence_Embeddings_part_4_Apply_Model.ipynb - the notebook used to perform text simplification of various coropora using the network learnt in part 3 (Section 5 and 6)
 - Text_Simplification_with_Sentence_Embeddings_part_5_NN_Eval.ipynb - the notebook used to perform evaluation of the simplifications resulting from the application of the neural network
 - Text_Simplification_with_Sentence_Embeddings_part_6_NN_Eval_LENS.ipynb - an additional notebook used for evaluating the LENS metric, which required a bespoke installation that was incompatible with other metrics.

Additionally, outputs from each notebook as produced dueing the experiments are given in part1_outputs/, part3_outputs/ and part4outputs/

If you use this research, please do cite the paper above.
