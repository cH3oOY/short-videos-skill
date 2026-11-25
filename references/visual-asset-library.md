# 真人写实视觉资源库

## 先清点，再定稿

按确认剧本和镜头表汇总主要人物、重复地点、关键道具、换装和状态变化。先制作并确认人物与场景基准图，再用它们出分镜图。已有经用户确认的参考就复用，不用文字重新抽象出一个不同的人或房间。

| 资源 ID / 版本 | 要交付的图 | 视觉锚点与允许变化 | 输入参考 | 被哪些场/镜使用 | 状态 |
|---|---|---|---|---|---|
| CHR01/v01 | 正面、侧面、背面；需要时补脸部近照 | 脸、体态、服装、配饰；表情随剧情变 | 参考图或已核对的外观描述 | 场/镜 ID | 待生成 / 待审 / 已确认 |
| LOC01/v01 | 定场全景；需要时补反向广角和平面示意 | 门窗、相对方位、材料；光线按时段版本 | 原文设定、空间示意 | 场/镜 ID | 同上 |
| PROP01/v01 | 关键道具参考图（如需） | 形状、材质、独特痕迹；开合等状态按剧本变 | 原作或角色参考 | 场/镜 ID | 同上 |
| SC01-SH01/START | 分镜首帧；有明确终点时另制 END | 构图、表演姿态、视线、道具与场景 | 同批已确认角色 / 地点 / 道具图 | 单一镜头 | 同上 |

状态变化不必总换图。剧情换装、明显天气或昼夜转换可衍生新版本；短时拿起道具、湿衣或站位变化记在该镜的入/出状态里。发现确认素材彼此冲突时，列出冲突并以原作与用户确认的优先项为准，先修基准再重做依赖它的图。

## 主要人物三视图

先确定可用的人物信息：年龄段、脸形及辨识特征、身高体态、发型、服装与左右不对称配饰。原作未描述的造型可以设计，标注为提案。以同一人和同一身服装制作 **全身正面、严格侧面（注明哪一侧）、全身背面**。三图用等高相机、相同画面尺度、站/脚基线、自然中性站姿和中性光，四肢不遮挡关键部位；不要分别随机抽样。若联排出图混脸，先确认正面，再用正面和已通过的侧面做后续角度，保持裁切与光线。需要跨镜识别五官时补一张真人近照。如有不对称特征而三视图遮挡另一侧，可补另一侧，不镜像冒充。

```text
Photoreal live-action full-body turnaround of the same {character appearance}. Preserve {face shape, distinctive features, hair and body proportions}, wearing {exact outfit, footwear and accessory sides}. Three views: straight front, strict {left or right} profile, straight rear. Same relaxed neutral stance, same camera height, same subject scale and ground line, neutral seamless studio backdrop and soft even lighting. Natural human facial proportions, skin texture, realistic fabric and fit. No illustration, cartoon proportions, beauty filtering or wardrobe variation. {Single view only if generated separately; use the approved face/body reference and render this camera angle.}
```

## 场景定场图

固定 `LOC` 的平面关系：入口、出口、窗、关键物、可供人物行动的区域、主光来源与入射方向。用场景平面或文字示意明确哪一侧，必要时补一张反向广角检查不可见面。定场图按一个明确机位生成，不把对侧信息挤在同一个画面。基础空间图不加无关人物；若叙事需要人物展示尺度，另制有人定场图。

```text
Photoreal live-action location establishing frame of {place, era, time and weather}, seen from {camera position, height and heading}. Stable layout: {entrance, windows, furniture and paths described relative to this camera and the approved floor plan}. {Material and wear details}. {Light source, direction and color}, physically plausible shadows and scale. Preserve the approved layout and fixed objects. {Frame boundaries and aspect ratio}. No unrelated people or added architecture.
```

## 分镜图与关键帧

每张图描述一个确切时点，只写该帧看得见的姿态和物体状态。按镜头卡选择首帧；需要精确终点、构图变化或双关键帧输入时，再出尾帧。首尾使用同一角色、场景与光线参考，保留叙事需要的变化。切到不同机位的下一镜，不能直接把上一镜尾帧当下一镜首帧；按新机位生成，再比对道具、视线、动作相位与画面方向。

```text
Photoreal live-action still. {Framing, camera position, heading and lens feel}. At this exact instant, {actor's visible identity, pose, eyeline, screen position and prop in which hand}. {Visible set landmarks, staging and light direction}, matched to the attached approved character, set and prop references. {Depth of field and material detail}. Preserve identity, wardrobe, placed props and the locked set geometry. Natural human face and skin. No collage, subtitles or added people.
```

## 出图交付与验收

- 逐项输出编号、版本、应上传的参考、画幅、可复制提示词及期望验收点。用户要求实际出图且有可用工具时，先制作人物与场景基准图，再制作分镜图。用户要求交付文件时，将素材整理为角色、场景和分镜三组，附资源索引、提示词与实际图片位置。可用 `CHR01-v01-front.png`、`LOC01-v01-establishing.png`、`SC01-SH01-start.png` 命名。基准图待审时，下游图标为草案。只有文本输出时，图像状态写「待生成」。
- 以参考约束正向描述为主；只有目标工具确认有负向栏时才把必要排除项另列，不假设存在参考权重、种子或多个输入槽。
- 逐项检查：正侧背是不是同一人，配饰和持物有没有左右互换；定场中门窗与主光是否吻合；分镜首尾是否保持尺度、出入画方向与剧情要求的动作相位。锁定通过的版本，优先更换出错项而不是重新抽整批。
