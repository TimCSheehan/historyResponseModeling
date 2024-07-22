# histroryResponseModeling
`Code AND data necessary to replicate`:
[Distinguishing response from stimulus driven history biases](https://www.biorxiv.org/content/10.1101/2023.01.11.523637v1.abstract) (preprint)

### Broad Summary: 
The field of *causal analysis* seeks to determine the underlying causal graph connecting observable phenomenon. A necessary (but non-sufficient) element for one factor to cause annother is that the two variables are correlated. Further we would demand that this correlation is not mediated by a third unobserved factor. In this study, we tackle a very specific question: *how can we know whether perceptual biases towards the past are driven by previously seen stimuli or by the responses elicited by those stimuli?* This question is complicated in studying *serial dependence in human perception* as both past stimuli **and** past responses are highly correlated with one annother, making their relative influences challenging to untangle. We further find that history independent biases (a bias to report stimuli further from vertical/horizontal) can further confound this process.

Using an entirely bottom-up simulation based approach we develop a rigorous method to seperating these two competing bias sources. Our approach is verified on simulated data and then applied to an empirical dataset providing strong evidence that the biases in question are driven by past responses (rather than past stimuli).

To run code: download or clone repo and run notebooks within folder. 

## Notebooks
[`sim_respBiases_main.ipynb`](https://github.com/TimCSheehan/historyResponseModeling/blob/main/sim_respBiases_main.ipynb) Walks through model and analysis. Easily allows exploration of additional hypotheses and expanded power analyses

[`UMI_BIAS_Clean_v1.ipynb`](https://github.com/TimCSheehan/historyResponseModeling/blob/main/UMI_BIAS_Clean_v1.ipynb) Empirical analysis example.

## Modules
[`responseModel.py`](https://github.com/TimCSheehan/historyResponseModeling/blob/main/responseModel.py) run simulation, visualize and quantify biases.

[`SD_functions.py`](https://github.com/TimCSheehan/historyResponseModeling/blob/main/SD_functions.py) helper functions for measuring and visualizing history biases


## Folders
`/Figs` Raw figures used in manuscript

`/data` Contains .csv file of experiment used in empirical analysis


## Contact
Questions, comments, or thoughts on expanding? Contact Timothy Sheehan <tsheehan@ucsd.edu>.
