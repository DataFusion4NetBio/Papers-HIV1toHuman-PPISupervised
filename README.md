# Papers-HIV1toHuman-PPISupervised
Data fusion to predict HIV-1 virus vs. Human protein interactions 

Please cite: 

- Major paper: 

@article{qi2010semi,
  title={Semi-supervised multi-task learning for predicting interactions between HIV-1 and human proteins},
  author={Qi, Yanjun and Tastan, Oznur and Carbonell, Jaime G and Klein-Seetharaman, Judith and Weston, Jason},
  journal={Bioinformatics},
  volume={26},
  number={18},
  pages={i645--i652},
  year={2010},
  publisher={Oxford Univ Press}
}
 
 <BR>

- Abstract
 
Motivation: Protein-protein interactions (PPIs) are critical for virtually every biological function. Recently, researchers suggested to use supervised learning for the task of classifying pairs of proteins as interacting or not. However, its performance is largely restricted by the availability of truly interacting proteins ({\em labeled}).  Meanwhile there exist a considerable amount of protein pairs where an association appears between two partners, but not enough experimental evidence to support it as a direct interaction ({\em partially labeled}).
 
Results: We propose a semi-supervised multi-task framework for predicting PPIs from not only {\em labeled}, but also {\em partially labeled} reference sets. The basic idea is to perform multi-task learning on a supervised classification task and a semi-supervised task.  The supervised classifier trains a multi-layer perceptron network for PPI predictions from {\em labeled} examples. The semi-supervised auxiliary task shares network layers of the supervised classifier and trains with {\em partially labeled} examples. Semi-supervision could be utilized in multiple ways. We tried three approaches in this paper, (1) classification (to distinguish partial positives with negatives); (2) ranking (to rate partial positive more likely than negatives); (3) embedding (to assure data clusters get similar labels).  We applied this framework to identify the set of interacting pairs between HIV-1 and human proteins. Our method improved upon the state-of-the-art method for this task indicating the benefits of semi-supervised multi-task learning using auxiliary information.
 
 <BR>

- Related Papers: 

1. O. Tastan, Y. Qi, J.G. Carbonell, J. Klein-Seetharaman, (2015) 
"Refining Literature Curated Protein Interactions Using Expert Opinions", The 20th Pacific Symposium on Biocomputing (PSB) 20 , (PSB15) (PDF) (TalkSlide) 

2. O. Tastan, Y. Qi, J.G. Carbonell, J. Klein-Seetharaman, ìPrediction of Interactions between HIV-1 and Human Proteins by Information Integrationì, Pacific Symposium on Biocomputing 14: (PSB-2009) Jan. 2009 

 

 <BR>
 - Some details in this supporting website @ http://www.cs.cmu.edu/%7Eqyj/HIVsemi/
 

·          Prior work of this paper: O. Tastan, Y. Qi, J.G. Carbonell, J. Klein-Seetharaman, ìPrediction of Interactions between HIV-1 and Human Proteins by Information Integrationì, Pacific Symposium on Biocomputing 14: (PSB-2009) Jan. 2009 (Supplementary Web)
 
·          Details about feature sets used !
 
·          Download all features used in this paper ! ==> (18 features for all possible HIV-Human Pairs)
 
·          Download IDs of the pairs : ==> (HIV Id: Human ID) for all hiv-Human pairs in the above feature file !
 
 
Data and Reference Sets Sharing:  
 
·          The top ranked 2500 predictions between HIV-1 and Human proteins 
 
·          The experts labelled positive PPIs pairs is shared 
 
·          The NIAID GroupI HIV-1 to human protein pairs (partial positive) are downloadable 
 
·          The NIAID GroupII HIV-1 to human protein pairs could be downloaded 
 