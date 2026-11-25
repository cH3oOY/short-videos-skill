# Camera Movement Library

## 机头旋转

| 术语 | 技术含义 | 常见用途 | Prompt 片段 |
|---|---|---|---|
| Pan left/right | 摄影机位置不变，水平旋转 | 扫视、寻找、跟随横向动作 | `slow pan right, 45 degrees, settles on the second subject` |
| Tilt up/down | 摄影机位置不变，垂直旋转 | 揭示高度、从细节到脸部 | `tilt up from the boots to the face` |
| Roll / Dutch angle | 绕镜头轴线旋转，地平线倾斜 | 不安、失衡、梦境 | `subtle 12-degree clockwise roll` |
| Whip pan | 高速水平旋转，形成运动模糊 | 动作转场、速度、惊讶 | `fast whip pan left, motion blur hides the transition` |

## 摄影机位移

| 术语 | 技术含义 | 常见用途 | Prompt 片段 |
|---|---|---|---|
| Dolly in / push-in | 沿镜头轴线靠近主体 | 亲密、紧张、心理深入 | `slow dolly in, 1.5 meters over 4 seconds` |
| Dolly out / pull-back | 沿镜头轴线远离主体 | 孤独、揭示环境、失控 | `steady dolly backward, revealing the empty room` |
| Tracking / follow | 沿主体运动方向跟拍 | 沉浸、陪伴、动作连续 | `smooth tracking shot following behind the runner` |
| Truck left/right | 横向平移，镜头可保持朝向 | 展示空间关系和视差 | `truck left 3 meters, keep the subject in profile` |
| Pedestal up/down | 摄影机整体垂直升降 | 从人群升起、展示层次 | `pedestal up 1.5 meters, horizon stays level` |
| Crane / jib | 机械臂升降并可配合俯仰 | 史诗、结束段落、尺度展示 | `crane up and tilt down to reveal the city` |
| Arc | 围绕主体做部分圆周移动 | 立体展示、关系变化 | `90-degree arc around the subject, constant radius` |
| Orbit | 围绕主体大幅环绕 | 仪式感、炫技、环境揭示 | `slow 180-degree orbit, subject remains centered` |
| Aerial / drone | 高空或无人机移动 | 建立空间、尺度、地理关系 | `drone rises above the valley` |
| FPV fly-through | 第一视角高速穿越 | 极限、沉浸、速度 | `FPV camera flies through the archway` |

## 光学和焦点

| 术语 | 技术含义 | 注意 |
|---|---|---|
| Zoom in/out | 只改变焦距，摄影机不移动 | 不要误写成 dolly |
| Dolly zoom / Vertigo shot | dolly 与 zoom 反向同步 | 主体近似等大，背景透视伸缩 |
| Rack focus | 焦点从前景切到后景或反向 | 是焦点变化，不是摄影机运动 |
| Crash zoom | 快速变焦 | 强调发现、震惊或喜剧效果 |

## 希区柯克式 Dolly Zoom

不要只写“希区柯克风格”。具体写法：

```text
The subject remains approximately the same size in frame while the camera dollies forward 2 meters and the lens zooms out from a 50mm feel to a 28mm feel over 3 seconds. The background stretches dramatically, conveying vertigo and psychological disorientation.
```

## 稳定方式

- `locked-off tripod, zero camera movement`：静止观察、压抑、等待
- `subtle handheld micro-shake`：纪录感、紧迫感，保持主体可读
- `steadicam follow`：流畅长镜头、人物陪伴
- `gimbal-smooth movement`：广告、产品、现代感
- `shoulder-mounted camera, organic sway`：强烈人体运动感

## 避免混淆

- pan ≠ truck：pan 是原地转头，truck 是横向移动
- tilt ≠ pedestal：tilt 是上下转头，pedestal 是整体升降
- zoom ≠ dolly：zoom 改变焦距，dolly 改变机位
- orbit ≠ pan：orbit 围绕主体移动，pan 只旋转镜头
- rack focus ≠ camera move：rack focus 只改变焦点
