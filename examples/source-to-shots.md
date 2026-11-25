# 完整示例：退回的信

本例使用一段原创练习素材，只验证各阶段如何交接。成片目标 12 秒、16:9、真人写实；未指定生成工具，所有图片均为文本方案、待生成。本例把「信被退回」作为信息落点，不猜收件人的身份、退回的原因或后续决定。

## 从原文到剧本

> 晚上，林岚打开楼道里的信箱。她取出自己几天前寄出的那封信。信封上盖着「退回」的红章。她没拆，把信放进了外套口袋。

| 原作锚点 | 保留内容 | 可拍处理 |
|---|---|---|
| SRC01，句 1 | 晚上、林岚、楼道信箱 | 她在画面中打开信箱；场景中不增加邻居 |
| SRC02，句 2–3 | 先取出自己的信，再揭示退回 | 信封近景露出短暂可辨的寄件人「林岚」和退回章；台词不解释退回原因 |
| SRC03，句 4 | 没有拆信，放进口袋 | 红章看清后再回到人物动作，停在信完全收起 |

### SC01｜内景｜公寓楼道｜夜

林岚打开信箱的侧开小门。她用右手从箱内抽出一个米色信封。信封没有拆开。寄件人是林岚。封面上方盖着红色的「退回」章。

她看着信封，停一下。她把没拆的信塞进外套右侧口袋。

**改编说明：** 寄件人字样用于视觉转译「自己寄出的」，不补写收件信息；等待一拍用于让观众认出红章。外套、信封颜色、楼道布局为可换的美术设计，不是原文事实。没有新增人物、对白或事件。

## 分场与逐镜调度

`SC01 / SRC01–03`：内景、夜、`LOC01/v01` 公寓楼道；`CHR01/v01` 林岚开箱取信、识别退回、收信。`PROP01/v01` 从信箱内到右手再到右侧口袋，全程密封。固定走廊一侧拍摄：从走廊南端朝北看，绿色信箱排在画面左，灰楼梯在远处居中，右墙的钨丝壁灯从画面右侧照亮她。林岚在画面右侧，朝左看向信箱。全段无对白，落在她完成收信，不先解读她的情绪。

| 镜头 / 成片时间 | 目的与运动 | 首帧 → 动作 → 尾帧 | 连续性与剪接 |
|---|---|---|---|
| SC01-SH01 / 00–04s，4 秒 | 交代空间与取信，固定中广景 | 0s 林岚在画面右侧，手靠近左侧信箱 → 约 1s 左手拉开侧门，右手把信抽出 → 4s 右手把未拆信封持在胸前，她低头朝画面左下看。无人出入画 | 信箱门留在打开的位置，壁灯主光从右来。切向她所看的信封近景，红章此时尚不可读 |
| SC01-SH02 / 04–07s，3 秒 | 揭示退回，轻推以突出印记 | 0s 右手持信，封面朝同侧机位 → 0–1.5s 轻推 → 1.5–3s 保持画面，让顶部红章和寄件人可读。信封密封，无人出入画 | 折痕、邮票和红章位置一致。保留右手高度和右侧暖光，切回相同持信位置 |
| SC01-SH03 / 07–12s，5 秒 | 让收信动作成为落点，固定中近景 | 0s 林岚在画面偏右，右手持信、视线低垂 → 0–1s 停一拍 → 1–4s 将信塞进右侧口袋 → 4–5s 信封完全没入口袋，她留在画面内 | 左侧可见打开的信箱门，右侧灯光和外套一致。信保持密封 |

## 资源清单与图像提示词

`CHR01/v01`、`LOC01/v01` 与 `PROP01/v01` 先审，分镜首帧使用这些经确认的版本。没有双帧需求，因此只列三张首帧及其提示词；每镜的目标末帧仍写进视频计划。

| 资源 | 需要上传的输入 | 可复制提示词 |
|---|---|---|
| CHR01/v01，联排三视图 | 暂无；后续补角度用已确认正面 | Photoreal live-action full-body turnaround of the same East Asian woman in her early thirties, oval face, dark brown chin-length bob with a left part, natural skin texture, charcoal wool coat with slanted pockets, dark trousers and flat black shoes. Straight front, strict right profile and straight rear. Match scale, eye-level camera and ground line. Relaxed stance, soft even studio light, plain gray background. Natural eyes and facial proportions, no illustration or beauty filtering. |
| LOC01/v01，定场图 | 剧本与方位说明 | Photoreal live-action wide establishing still from the south end of a narrow apartment corridor, looking north at night. Worn dark-green metal mailboxes on the camera-left wall near the foreground, a single warm tungsten sconce on the camera-right wall opposite them, gray concrete stairwell centered at the far end. Beige plaster, worn gray tile, realistic scale and shadows cast leftward from the right wall. Empty corridor, 16:9. |
| PROP01/v01，信封校样 | 已确认文案；有正式字样时用其作为参考 | Photoreal prop reference of a sealed cream paper envelope with a small crease at the lower-left front corner, a stamp at upper right, red rectangular Chinese return stamp reading 「退回」 near upper center, and a small sender line reading 「寄件人：林岚」 near lower center. Plain neutral background, flat-on front view, even lighting. Keep lettering distinct; do not add a recipient's name. |
| SC01-SH01/START | CHR01/v01、LOC01/v01 | Photoreal eye-level medium-wide corridor still from the south looking north. Dark-green mailboxes at frame left. The same short-haired woman in her charcoal wool coat stands frame right facing them, left hand just below a closed mailbox door. Right-wall tungsten light, gray stairs in the distance, no visible envelope, 16:9. |
| SC01-SH02/START | CHR01/v01、LOC01/v01、PROP01/v01 | Photoreal close-up from the corridor side of the same woman's right hand holding the sealed cream envelope at chest height. Its approved front markings face the camera: lower-left crease, postage upper right, red return stamp above the sender line, dark charcoal sleeve, warm key light from frame right and muted green mailbox blur behind. 16:9. |
| SC01-SH03/START | CHR01/v01、LOC01/v01、PROP01/v01 | Photoreal eye-level medium close-up of the same woman frame right, eyes lowered toward the cream envelope in her right hand at chest height. Her charcoal coat's right pocket is in the lower frame. The same open dark-green mailbox door is visible left, warm side light from frame right, 16:9. |

先核对信封中文字。字样不准时，锁一张校正后的道具图作为参考，仍不稳定则在剪辑中把准确字样跟踪叠合到信封画面上。不要依赖生成模型按指令自动改对文字。

## 逐镜视频提示词

**生成设置：** 三镜分别用同编号的 `START` 图；目标片段分别为 4、3、5 秒，成片使用秒数同上，16:9。若工具只允许更长的片段，按图中动作的实际停点剪到目标秒数，必要时重做，不用无关镜头补时。信箱轻响、纸摩擦及楼道底噪在剪辑中处理。

**SC01-SH01**

```text
Begin exactly from the supplied medium-wide frame. Locked camera. The short-haired woman on frame right swings open the hinged green mailbox door with her left hand, draws a sealed cream envelope with her right hand, then holds it at chest height and looks down at it. The front markings are not legible at this distance. Maintain her natural face, charcoal coat, right-side tungsten light, fixed corridor geometry and framing. End with her gaze lowered, the mailbox door still open and the sealed envelope in her right hand. Single continuous shot, no cuts.
```

**SC01-SH02**

```text
Begin with the supplied right-hand close-up. Slowly dolly straight toward the sealed envelope for the first half, then hold so the existing red return stamp and sender line can be read. The woman's hand stays at chest height, with only natural settling. Preserve the approved envelope markings, paper crease and warm light from frame right. End with the return stamp and sender line both in focus; no text changes, no cuts.
```

**SC01-SH03**

```text
Begin exactly from the supplied medium close-up. Locked camera. The same woman looks down at the envelope for one beat, then slowly slides it, unopened, into her charcoal coat's right pocket with her right hand. Show the whole movement and hold after the envelope is fully inside. Keep her facial features, coat, open mailbox door, screen position and right-side warm light unchanged. She remains in frame. Single continuous shot, no cuts.
```
