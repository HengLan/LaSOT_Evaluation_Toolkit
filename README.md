## LaSOT_Evaluation_Toolkit

This toolkit is utilized for evaluating trackers' performance on a large-scale benchmark LaSOT (https://cis.temple.edu/lasot/).

## Notification (Downloading dataset and tracking results)

There is a problem with the data sever. Please use the following links to download dataset:

* Download the whole dataset through Google driver: https://bit.ly/LaSOTAll
* Download each category through Google driver: https://bit.ly/LaSOTEach
* Download the whole dataset through Baidu Pan: https://pan.baidu.com/s/1UbcQIU-Fpps7Jqq4WHRRkA
* Download each category through Baidu Pan: https://pan.baidu.com/s/1xFANiqkBHytE7stMOLUpLQ

In order to download the tracking results, please directly use the following link (including toolkit and complete results):
* Download the toolkit and complete tracking results: https://cis.temple.edu/lasot/toolkit/LaSOT_Evaluation_Toolkit.zip


## Usage
* Download the repository, unzip it to your computer
* Download <a href="https://cis.temple.edu/lasot/toolkit/lasot_tracking_results.zip">tracking result</a>, unzip it to folder `tracking_results/`
* Run `run_tracker_performance_evaluation.m` in Matlab

## Notes
In the file `run_tracker_performance_evaluation.m`, you can
* change `evaluation_dataset_type` (line 25) for evaluation on all 1,400 sequences or 280 testing sequences
* change `norm_dst` (line 28) for precision or normalized precision plots

In the file `utils/plot_draw_save.m`
* change the plotting settings to get the appropriate plots

## Citation
If you use LaSOT and this evaluation toolkit for you researches, please consider citing our paper:
* H. Fan*, L. Lin*, F. Yang*, P. Chu*, G. Deng, S. Yu, H. Bai, Y. Xu, C. Liao, and H. Ling. <a href="https://arxiv.org/pdf/1809.07845.pdf">LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking</a>. In *CVPR*, 2019.

## Contact
If you have any questions on <a href="https://cis.temple.edu/lasot/">LaSOT</a>, please feel free to contain Heng Fan at hengfan@temple.
