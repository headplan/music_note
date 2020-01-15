# Fruity Slicer

**Fruity Slicer - **切片器 . 使用节拍检测将波形文件切成小块 , 并使它们可从钢琴卷或控制器独立播放 . 如果波形文件包含切片/区域数据则不检测节拍 , 自动使用切片数据 . Fruity Slicer提供回放 , 切片的重新排序以及针对鼓循环而优化的时间拉伸功能 . 常见的鬼畜的音频效果就可以使用Fruity Slicer切出来 .

![](/assets/fruityslicer.png)

Fruity slicer采样器插入后是空的 , 没有声音 , 需要手动加载采样 . 可以从浏览器中直接拖曳到Fruity slicer采样器的面板上读取 , 不仅可以读取波形采样文件 , 还支持直接读取 , 语音合成器的预设文件 , 以及其他一些格式的文件 .

![](/assets/fruityslicer %281%29.png)

**左键和右键单击**上部窗口\(Slice Properties\)和下部窗口\(Slice Preview\)可以访问更多功能 . 比如 , 为了**更好地控制切片** , 可以在"Slice Properties"窗口中单击鼠标左键并将其拖动到Sampler Channel或其他.wav兼容位置 . 在Slice Properties中还可以设置1和2 , 表示切片在钢琴卷中的名称以及位置\(根音\) , 可以在钢琴卷中编辑各种新的切片方式 .

### Function Buttons功能按钮

**BPM / BEATS控件** - 设置原始循环的BPM\(速度\)和节拍数\(长度\) . 如果loop中有这些信息数据 , 会自动设置为对应的值 . 否则Slicer会尝试猜测Loop的速度和长度\(循环越长 , 检测的准确性越低\) .

**切片采样按钮\(Sample\)**

* Load sample - 加载采样 . 支持的格式有\(\*.wav, Recycle \*.rex / \*.rcy / \*.rx2, etc.\) . **注** : 如果采样已经包含切片标记 , 将使用标记 . .mp3文件不能包含切片标记 , 只有.wav文件可以 . 
* Save Original sample - 保存原始采样 , 不包含切片信息 . 
* Save Processed sample - 保存处理采样 , 保存带有切片信息的采样 . 

**节拍切片器按钮\(Slicing\)**

* **Use Sample Built-In Slicing** - 使用样本内置切片 . 使用从样本加载的切片 . 这一般是最佳的选择 . 
* **Dull / Medium / Sharp Auto-slicing** - 使用切片阈值的三个预定义值 , 对Loop进行自动切片的三个选项 . 分别为粗糙/普通/精细 . 
* **1/6, 1/4, 1/3 beat ... Beat** - 不去自动检测 , 直接对采用进行量化的切片 . 
* **No Slicing** - 整个Loop被视为单个切片 . 
* **Zero cross check slices** - 零交叉检查切片 . 如果在播放切片时听到咔嗒/啪嗒声 . 则可以在将Loop与上述任何选项一起切片后调用此选项 , 会将切片标记对齐到最近的零交叉处 . 

**编辑\(Edit\)**





