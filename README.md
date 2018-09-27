## LaSOT_Evaluation_Toolkit

This toolkit is utilized for evaluating trackers' performance on a large-scale benchmark LaSOT (https://cis.temple.edu/lasot/).

## Usage
* Download the repository, unzip it to your computer
* Download <a href="https://cis.temple.edu/lasot/toolkit/lasot_tracking_results.zip">tracking result</a>, unzip it to folder `tracking_results/`
* Run `run_tracker_performance_evaluation.m` in Matlab

## Notes
In the file `run_tracker_performance_evaluation.m`, you can
* change `evaluation_dataset_type` (line 25) for evaluation on all 1,400 sequences or 280 testing sequences
* change `norm_dst` (line 28) for precision or normalized precision plots

## Citation
If you use LaSOT and this evaluation toolkit for you researches, please consider citing our paper:
* H. Fan*, L. Lin*, F. Yang*, P. Chu*, G. Deng, S. Yu, H. Bai, Y. Xu, C. Liao, and H. Ling, "LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking", <a href="https://arxiv.org/pdf/1809.07845.pdf">	arXiv:1809.07845</a>, 2018.

## Contact
If you have any questions on <a href="https://cis.temple.edu/lasot/">LaSOT</a>, please feel free to contain Heng Fan at hengfan@temple.
