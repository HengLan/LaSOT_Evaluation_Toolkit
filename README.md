## UPDATE: A new challenging subset is added!

We released a newly collected extension subset of 15 categories with 150 videos (very challenging!!!) for one-shot evaluation of tracking algorithms. Check the description in this <a href="https://arxiv.org/abs/2009.03465">paper</a>. More details including the data, complete evaluation toolkit and results of 48 trackers are available at this <a href="http://vision.cs.stonybrook.edu/~lasot/">project</a>.

## LaSOT_Evaluation_Toolkit

This toolkit is utilized for evaluating trackers' performance on a large-scale benchmark LaSOT (http://vision.cs.stonybrook.edu/~lasot/).



## Notification (Downloading dataset and tracking results)

Please use the following links to download dataset (OneDrive is recommended):

#### Download LaSOT in the conference version

* Download the whole dataset in conference version through OneDriver: [link](https://1drv.ms/u/s!Akt_zO4y_u6DgoQsxl9ixr5Y393qWA?e=7yTwjc) or Google Drive: [part-1](https://drive.google.com/file/d/1wnKcCuGxRTSPDnYcAB162juy_Qphbb14/view?usp=share_link) [part-2](https://drive.google.com/file/d/1OANces8uLc2gAOFLGh4MaOqXUTrmZ77v/view?usp=share_link) [part-3](https://drive.google.com/file/d/17LiijVbwUkAqgbCaj-W_33KbuX9RsYxy/view?usp=share_link)

* Download each category in conference version through OneDriver: [link](https://1drv.ms/f/s!Akt_zO4y_u6DgoNSoMJrfnVwveDjhA?e=PBeyuD)

#### Download LaSOT-extension in the journal version

* Download the new extension in journal version through OneDriver: [link](https://1drv.ms/u/s!Akt_zO4y_u6DgoQrvo5h48AC15l67A?e=Zo6PWx)
* Download each category of the new extension in journal version through OneDriver: [link](https://1drv.ms/f/s!Akt_zO4y_u6DgoQZH_aGsNh2f6x6Dg?e=sldyAx)

In order to download the tracking results, please directly use the following link (including toolkit and complete results):
* Download the toolkit and complete tracking results: [link (Google Drive)](https://drive.google.com/file/d/14gbxoSCe31qho1IV6pXx5LI-nzpDechR/view?usp=share_link)


## Usage
* Download the repository, unzip it to your computer
* Download <a href="https://drive.google.com/file/d/14gbxoSCe31qho1IV6pXx5LI-nzpDechR/view?usp=share_link">tracking result</a>, unzip it to folder `tracking_results/` (if this is not working, use the above link)
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
*International Journal of Computer Vision (IJCV)*, 129: 439–461, 2021.
* <a href="https://arxiv.org/pdf/1809.07845.pdf">LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking</a> <br> 
H. Fan*, L. Lin*, F. Yang*, P. Chu*, G. Deng, S. Yu, H. Bai, Y. Xu, C. Liao, and H. Ling <br> 
In *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2019.

## Contact
If you have any questions on <a href="http://vision.cs.stonybrook.edu/~lasot/">LaSOT</a>, please feel free to contact Heng Fan at heng.fan@unt.edu.
