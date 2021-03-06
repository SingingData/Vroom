# The VROOM Audio Dataset 
### VROOM stands for "Various Recordings of Other Motors"
Last Updated January 8, 2020

VROOM is a collection of motorized vehicle and motor tool audio recordings for use in machine learning.

This dataset is a complement to the extensive Urban Sound Dataset https://urbansounddataset.weebly.com/. We found existing collections of urban sound lacked detailed labeled samples of industrial motor powered sounds.  In VROOM, we deliver data samples of industrial motor powered sound with more detailed labels regarding the device, craft, settings and environment.

Specifically, this dataset includes:
- Machine tooling, including class lables of power tools like metal lathe run at correct and incorrect speed settings.
- Several distinct commercial ferry boat motors from Washington State Ferry System.
- Commercial aircraft landings at LAX and SEA.  
- Miscellaneous power motor samples across power tool, aircraft and marine craft categories.

The data samples in this repo are all one second in duration with a 32000 sample rate.  
Should you want to reconstitute the original recording, the data samples are labeled by sample and sequence of each chunk.

This data repository was created to enable industrial sound machine learning, and was part of a presentation at the WiML workshop at NeurIPS 2019 in Vancouver. The poster presented at that workshop is here.  See NeurIPS poster here.  https://github.com/SingingData/Vroom/blob/master/img/Ryan-NeurIPS-poster.pdf

The goal is to add to this repository over time to enable machine learning practitioners to train models on industrial audio.  Contributions and feedback from the community are welcome.

Thanks,

Patty Ryan

