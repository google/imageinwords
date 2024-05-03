## IIW: Data Sets
We release a subset of human- and model-annotated IIW image & descriptions, as well as human SxS results on Human Authored and Model-Human sourced pairs of descriptions. The model generated descriptions may have hallucinations, information recall losses, or non-human like writing style artifacts. By releasing this subset along with human SxS judgements, we encourage the development of new metrics and evaluation systems to detect them in an automated, scalable manner. It also promotes fair comparison across methods in future work. The set is released under a CC BY 4.0 license.

<b>Human Annotated</b> 

We provide human-authored annotations from the IIW
framework.
<ul>
  <li>IIW-400, a new eval dataset of 400 random images sampled from DOCCI-AAR. Full IIW Task-1 and Task-2 annotations along with 100 human SxS results each on GPT-4V and IIW PaLI-5B models (including model predictions).</li>
  <li>DCI-Test, 112 images re-annotated with the IIW framework along with human SxS results comparing them to DCI’s original human annotations.</li> 
  <li>DOCCI-Test, 100 random images re-annotated with the IIW framework along with human SxS results comparing them to DOCCI’s human annotations.</li>
</ul>

<b>Model Annotated</b> 

We release 2.4k random images annotated by the IIW PaLI-5B model (Tab. 4) comprising of the IIW-400 set (as used for the human SxS evaluation), 1k samples from the LocNar Eval set (from the OpenImages subset), and 1k samples from the Crossmodal-3600 images.
