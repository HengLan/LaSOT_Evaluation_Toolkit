## UPDATE: A new challenging subset is added!

We released a newly collected extension subset of 15 categories with 150 videos (very challenging!!!) for one-shot evaluation of tracking algorithms. Check the description in this <a href="https://arxiv.org/abs/2009.03465">paper</a>. More details including the data, complete evaluation toolkit and results of 48 trackers are available at this <a href="https://www.cs.stonybrook.edu/~cvl/projects/lasot/">project</a>.

## LaSOT_Evaluation_Toolkit

This toolkit is utilized for evaluating trackers' performance on a large-scale benchmark LaSOT (http://vision.cs.stonybrook.edu/~lasot/).



## Notification (Downloading dataset and tracking results)

There is a problem with the data sever. Please use the following links to download dataset:}

* Download the whole dataset through Google driver: https://bit.ly/LaSOTAll
* Download each category through Google driver: https://bit.ly/LaSOTEach
* Download the whole dataset through Baidu Pan: https://pan.baidu.com/s/1UbcQIU-Fpps7Jqq4WHRRkA
* Download each category through Baidu Pan: https://pan.baidu.com/s/1xFANiqkBHytE7stMOLUpLQ

In order to download the tracking results, please directly use the following link (including toolkit and complete results):
* Download the toolkit and complete tracking results: http://vision.cs.stonybrook.edu/~lasot/LaSOT_Evaluation_Toolkit.zip


## Usage
* Download the repository, unzip it to your computer
* Download <a href="http://vision.cs.stonybrook.edu/~lasot/lasot_tracking_results.zip">tracking result</a>, unzip it to folder `tracking_results/` (if this is not working, use the above link)
* Run `run_tracker_performance_evaluation.m` in Matlab

## Notes
In the file `run_tracker_performance_evaluation.m`, you can
* change `evaluation_dataset_type` (line 25) for evaluation on all 1,400 sequences or 280 testing sequences
* change `norm_dst` (line 28) for precision or normalized precision plots

In the file `utils/plot_draw_save.m`
* change the plotting settings to get the appropriate plots

## Citation
If you use LaSOT and this evaluation toolkit for you researches, please consider citing our paper:
* <a href="https://arxiv.org/abs/2009.03465">LaSOT: A High-quality Large-scale Single Object Tracking Benchmark</a> <br>
H. Fan*, H. Bai*, L. Lin, F. Yang, P. Chu, G. Deng, S. Yu, Harshit, M. Huang, J Liu, Y. Xu, C. Liao, L Yuan, and H. Ling <br>
*arXiv:2009.03465*, 2020.
* <a href="https://arxiv.org/pdf/1809.07845.pdf">LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking</a> <br> 
H. Fan*, L. Lin*, F. Yang*, P. Chu*, G. Deng, S. Yu, H. Bai, Y. Xu, C. Liao, and H. Ling <br> 
In *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2019.

## Contact
If you have any questions on <a href="http://vision.cs.stonybrook.edu/~lasot/">LaSOT</a>, please feel free to contact Heng Fan at hefan@cs.stonybrook.edu.
