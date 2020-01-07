# TC_tracker_python
这是TC_tracker的python复现版本，原文地址:[TC_tracker](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w3/Tang_Single-Camera_and_Inter-Camera_CVPR_2018_paper.pdf)

<div align="center">
  <img src="TC_TRACKER/demo.gif" width="400px" />
  <p>Example outputs.</p>
</div>


## 运行方法
Call the main script.
```bash
python main.py
```

## 注意事项
其中的高斯回归函数参数设置与原版的matlab程序稍有不同，导致最后的跟踪MOTP有少许误差
