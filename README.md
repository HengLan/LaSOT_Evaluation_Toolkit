## UPDATE: A new challenging subset is added!

We released a newly collected extension subset of 15 categories with 150 videos (very challenging!!!) for one-shot evaluation of tracking algorithms. Check the description in this <a href="https://arxiv.org/abs/2009.03465">paper</a>. More details including the data, complete evaluation toolkit and results of 48 trackers are available at this <a href="http://vision.cs.stonybrook.edu/~lasot/">project</a>.

## LaSOT_Evaluation_Toolkit

This toolkit is utilized for evaluating trackers' performance on a large-scale benchmark LaSOT (http://vision.cs.stonybrook.edu/~lasot/).



## Notification (Downloading dataset and tracking results)

There is a problem with the data sever. Please use the following links to download dataset:}

* Download the whole dataset in conference version through Google driver: [link](https://drive.google.com/file/d/1nTvmKZSieCLASL1C0XkeWSDqlyS80fLz/view?usp=share_link)
* Download each category in conference version through Google driver: [link](https://drive.google.com/drive/folders/1tBn9KzCqiyY98Yvm8vpvn12w_LDhr5_B?usp=share_link)
* Download the test subset only in conference version through Google driver: [link](https://drive.google.com/file/d/1UvhAGVRHr3loPCBe3_QNzT7-NBXIU-z1/view?usp=share_link)
* Download the new extension in journal version through Google driver: [link](https://drive.google.com/file/d/1QFBJJKfoGoPiDVFPNWs4fYFMVW7jYtaQ/view?usp=share_link)
* Download each category of the new extension in journal version through Google driver: [link](https://drive.google.com/drive/folders/1aQApha4Q1aiBz7MRP13Ljz1k9K4cQD7g?usp=share_link)

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
*International Journal of Computer Vision (IJCV)*, 129: 439–461, 2021..
* <a href="https://arxiv.org/pdf/1809.07845.pdf">LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking</a> <br> 
H. Fan*, L. Lin*, F. Yang*, P. Chu*, G. Deng, S. Yu, H. Bai, Y. Xu, C. Liao, and H. Ling <br> 
In *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2019.

## Contact
If you have any questions on <a href="http://vision.cs.stonybrook.edu/~lasot/">LaSOT</a>, please feel free to contact Heng Fan at heng.fan@unt.edu.
