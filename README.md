# cvui-py-two-knob-trackbar
cvui-py-two-knob-trackbarはPython版のcvuiをベースとして、上限下限の2つの値を指定可能なトラックバーをお試しで実装したものです。

cvui-two-knob-trackbar is a experimental implementation of a trackbar based on cvui that allows you to specify two values, upper and lower limits.

![jbl0m-01yhb](https://user-images.githubusercontent.com/37477845/76235541-94c3b580-626e-11ea-803b-aa9e82aea324.gif)


# Requirement
 
* OpenCV 3.4.2(or later)

# How to use
```python
trackbar_value1 = [25.0]
trackbar_value2 = [75.0]

cvui.trackbar2(cvuiframe, 30, 30, 400, trackbar_value1, trackbar_value2, 0., 100.)
```

# Usage
 
サンプルの実行方法は以下です。

Here's how to run the sample.
 
```bash
python sample.py
```

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)

# License

cvui-double-knob-trackbar is under [MIT license](LICENSE.md).

# cvui License

The original part of cvui is distributed under the MIT license.

I pay tribute to his wonderful work.

Copyright (c) 2016 Fernando Bevilacqua. Licensed under the [MIT license](LICENSE.md).

# Reference
https://github.com/Dovyski/cvui
