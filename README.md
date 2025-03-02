[comment]: <> (# ssl_e2vid)

<h1 align="center"> ssl_e2vid (中文注释版~仅供个人学习记录用)
</h1>

[comment]: <> ( <h2 align="center">PAPER</h2>)
  <h3 align="center">
  <a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Paredes-Valles_Back_to_Event_Basics_Self-Supervised_Learning_of_Image_Reconstruction_for_CVPR_2021_paper.pdf" target="_blank">Paper</a>
  | <a href="https://github.com/tudelft/ssl_e2vid" target="_blank">Original Github Page</a>
  | <a href="https://kwanwaipang.github.io/Awesome-Event-based-Contrast-Maximization/" target="_blank">Blog for CM</a>
  </h3>
  <div align="center"></div>

<!-- rm -rf .git -->

* 训练代码为`python train_reconstruction.py`
* 训练optical flow network代码为 `python train_flow.py`对应的参数文件为`configs/train_flow.yml`
* 测试光流估算的代码为 `python eval_flow.py <path_to_model_dir>`
* 测试图像重建的代码为 `python eval_reconstruction.py <path_to_model_dir>`

* 同样的采用[MLflow](https://mlflow.org/)来管理实验
* [Event Contrast Maximization Library](https://github.com/TimoStoff/events_contrast_maximization)