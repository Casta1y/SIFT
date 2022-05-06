# SIFT
- cv2, 4.5.5
- python, 3.9.7
- 使用opencv提供的sift函数建立两幅图像间的特征点匹配。
- 在OpenCV4.4.0及以上版本中调用cv2.xfeatures2d.SIFT_create()，会提示没有方法。这是因为SIFT的专利已于 2020 年 3 月 6 日到期。现在可以在OpenCV的免费库中调用。OpenCV 的分布式构建现在包含自 4.4.0 版以来的 SIFT，可通过 Python 中的 **cv2.SIFT_create()** 访问。
