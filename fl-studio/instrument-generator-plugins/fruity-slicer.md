# Fruity Slicer

**Fruity Slicer - **切片器 . 使用节拍检测将波形文件切成小块 , 并使它们可从钢琴卷或控制器独立播放 . 如果波形文件包含切片/区域数据则不检测节拍 , 自动使用切片数据 . Fruity Slicer提供回放 , 切片的重新排序以及针对鼓循环而优化的时间拉伸功能 . 常见的鬼畜的音频效果就可以使用Fruity Slicer切出来 .

![](/assets/fruityslicer.png)

Fruity slicer采样器插入后是空的 , 没有声音 , 需要手动加载采样 . 可以从浏览器中直接拖曳到Fruity slicer采样器的面板上读取 , 不仅可以读取波形采样文件 , 还支持直接读取 , 语音合成器的预设文件 , 以及其他一些格式的文件 .

![](/assets/fruityslicer %281%29.png)

**左键和右键单击**上部窗口\(Slice Properties\)和下部窗口\(Slice Preview\)可以访问更多功能 . 比如 , 为了**更好地控制切片** , 可以在"Slice Properties"窗口中单击鼠标左键并将其拖动到Sampler Channel或其他.wav兼容位置 . 在Slice Properties中还可以设置1和2 , 表示切片在钢琴卷中的名称以及位置\(根音\) , 可以在钢琴卷中编辑各种新的切片方式 .

### Function Buttons功能按钮

**BPM / BEATS控件** - 设置原始循环的BPM\(速度\)和节拍数\(长度\) . 如果loop中有这些信息数据 , 会自动设置为对应的值 . 否则Slicer会尝试猜测Loop的速度和长度\(循环越长 , 检测的准确性越低\) .

**打开并切片采样按钮\(Sample\)**

* Load sample - 加载采样
* Save Original sample - 保存原始采样 , 不包含切片信息 . 
* Save Processed sample - 保存处理采样 , 保存带有切片信息的采样 . 



