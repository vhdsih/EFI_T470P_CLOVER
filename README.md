# EFI_T470P_CLOVER



new update at 20210129：

update clover to r5119, update kext, tested on 10.15.7.



============ 分割线 ============

#### T470P黑苹果EFI文件，10.15.1安装测试通过<br/>
- 机型：Lenovo T470p 20J6A01ACD，CPU：Intel i7 7700HQ，核显：HD 630<br/>
- 加装了M.2 2242 SSD 512GB 建兴T11<br/>
- 加装了三星8G内存<br/>

#### 2017-12-03更新：<br/>
- 显卡驱动正常<br/>
- 声卡驱动正常，声音调节正常<br/>
- 触摸板设置正常<br/>
- 亮度调节正常<br/>

#### 2018-05-23更新：<br/>
- 更新clover<br/>
- 更新声卡驱动<br/>

#### 2018-06-10更新：<br/>
- 更新各种kext驱动到最新版本<br/>

#### 2018-10-28更新：<br/>
- 更新clover<br/>
- 更新各种驱动到最新版本<br/>
- 更新支持mojave 10.14<br/>

#### 2019-03-27更新：<br/>
- 更新clover到4907<br/>
- 更新各种驱动到最新版本（主要是Lilu和WhateverGreen）<br/>
- 更新支持mojave 10.14.3、10.14.4<br/>

#### 2019-04-22更新：<br/>
- 更新clover到4920<br/>
- 更新各种驱动到最新版本<br/>
- 解决颜色过渡不平滑及水波纹花屏问题，仿冒skylake 1916<br/>
- 解决连接外部hdmi的kp问题，hdmi最好是启动后再外接，但外接hdmi后内屏黑屏（见issues）。请自行修改机型为14,1。<br/>

#### 2019-04-23更新：<br/>
- 解决睡眠后立即自动唤醒问题<br/>

#### 2019-05-18更新：<br/>
- 更新clover到4928<br/>
- 更新各种驱动到最新版本<br/>
- 更新支持mojave 10.14.5<br/>
- 完善变频<br/>
- 解决外接hdmi显示器，导致内屏黑屏问题。方法是仿冒kabylake 5916，并设置机型14,2。<br/>

#### 2019-05-25更新：<br/>
- 更新clover到4934<br/>
- 更新各种驱动到最新版本<br/>

#### 2019-06-09更新：<br/>
- 更新Clover到4959<br/>
- 更新Lilu、WhateverGreen等各种驱动到最新版本<br/>
- 更新支持Catalina 10.15 Beta1<br/>

#### 2019-07-07更新：<br/>
- 更新Clover到4979<br/>
- 更新Lilu、WhateverGreen等各种驱动到最新版本<br/>
- 更新支持Catalina 10.15 Beta3(19A501i)<br/>

#### 2019-11-23更新：<br/>
- 更新Clover到5098<br/>
- 更新Lilu、WhateverGreen等各种驱动到最新版本<br/>
- 更新支持Catalina 10.15.1<br/>

#### 2020-11-29更新：<br/>
- 更新Clover<br/>
- 更新Lilu、WhateverGreen等各种驱动到最新版本<br/>
- 提供两种核显设置方案，如下：<br/>
- config-14,1,1916.plist：默认方案，机型14,1，仿冒1916，存在HEVC硬解失败问题，HDMI音频可能失效问题；<br/>
- config-14,3,591B.plist：备选方案，机型14,3，设置591B，存在启动台和Safari的背景色带（颜色过渡不平滑）问题；<br/>
- 以上两种方案自行选择<br/>
