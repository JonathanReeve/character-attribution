# character-attribution
Probabilistic attribution of character voices in fiction. 

#Contents
 - /charts - figures used in the paper
 - /clarissa - experiments in character attribution for Richardson’s epistolary novel _Clarissa_. 
   - clarissa.xml - a concatenation of all seven TEI XML files of _Clarissa_ from the Oxford Text archive, marked up with regularized letter sender and recipients to aid extraction. 
   - clarisssa-experiments.ipynb - the main notebook of analyses for _Clarissa_
   - clarissa-grid-search.ipynb - experiments with cross-validation grid search for parameter optimization
   - clarissa-vectors.ipynb - experiments with semantic word vector representations of the novel
   - clarissa-with-recepients.ipynb - experiments run again, this time with recepients encoded in the latest version of `clarissa.xml` 
 - /gatsby - experiments with a TEI edition of _The Great Gatsby_, not discussed in the paper
 - /paper - the paper describing this experiment. A readable copy is character-voice.pdf; the rest are build files
 - /waves - experiments with Virginia Woolf’s novel _The Waves_
