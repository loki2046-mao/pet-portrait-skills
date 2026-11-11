# 独立 LOMO 抓拍提示词

先区分新动物与照片个体，再写自然瞬间和成像。个体证据优先于动作多样性。不要使用 luxury fashion model、advertising campaign、aloof editorial composure 作为正向目标。

## 新动物创作

```text
Create ONE independent SQUARE 1:1 photorealistic candid photograph of a newly imagined [SPECIES / BREED]. This is a new fictional individual, not a reconstruction of a specific user's animal. Design unspecified individual traits consistently.

Capture an unguarded fraction of a second with a beloved animal: [SPECIES-APPROPRIATE ACTION AND PRECISE PHASE], with naturally matching [VISIBLE EYE STATE], [MOUTH OR BEAK STATE], [EARS OR OTHER APPLICABLE STRUCTURES] and [BODY POSITION]. The moment should feel affectionate, spontaneous and worth keeping as a happy personal memory. Use real animal behavior and natural proportions, not a human facial performance. Do not give a bird mammal lips, turn wings/paws/hooves into hands, or impose cat/dog anatomy on another species.

Photograph from [VIEWPOINT / CROP], with [GAZE TARGET IF APPLICABLE]. Keep the expression and action readable. Depict only anatomy appropriate to this species, with believable fur, feathers or other natural surface. No human torso. Use [CLOTHES / ZERO TO TWO SPECIES-APPROPRIATE ACCESSORIES] in [SIMPLE LIVED-IN SETTING]; clothing fits the actual animal and is incidental to the moment.
```

## 用户照片中的具体个体

实际查看原照并读 `photo-identity.md` 后填写观察内容。这个模式不沿用新创作模板中的自由动作/视角；输入照片的可见范围优先。

```text
Edit the supplied IDENTITY photograph(s) of this particular animal. Image roles: [IDENTITY AND ANGLE IMAGE IDS]; [STYLE-ONLY IMAGE IDS, IF ANY]. Preserve the observed individual, not merely its breed.

Observed evidence: [SUPPORTED VIEW, HEAD/BODY ORIENTATION AND CROP]; [VISIBLE SILHOUETTE, PROPORTIONS, EYES/NOSE/MUZZLE/BEAK/EARS]; [VISIBLE MARKING LOCATIONS AND BOUNDARIES, ASYMMETRIES AND DISTINCTIVE FEATURES]. Use image-relative labels unless anatomical left/right is certain. Unknown or unverified: [OPPOSITE SIDE / HIDDEN EYE COLOR / BODY / PAWS / TAIL / MOUTH INTERIOR / OTHER SPECIFIC GAPS].

Keep [EVIDENCED CAMERA VIEW AND VISIBLE EXTENT]. Capture [EXISTING OBSERVED EXPRESSION OR A SMALL SUPPORTED GESTURE THAT DOES NOT EXPOSE UNKNOWN DETAILS], with [EVIDENCED EYE/MOUTH/BEAK/HEAD STATES]. Do not force a new pose, angle, over-shoulder turn or four different actions. A closed-mouth reference does not establish this individual's tongue, gums, teeth or missing-tooth pattern: keep the mouth closed unless suitable identity evidence supports the requested new mouth detail. Do not infer the unseen side or anatomy from species/breed norms.

Do not horizontally flip, mirror/symmetrize markings, erase distinctive features, reveal unknown regions, or import anatomy from a style reference. Do not outpaint unobserved body parts for an outfit or wider frame. A collar or scarf may fit the observed neck without an invented torso. Make square framing through supported cropping or background extension only.

Change only [LIGHT / BACKGROUND / OUTFIT WITHIN OBSERVED GEOMETRY / FILM TREATMENT / SPECIFIC SUPPORTED MICRO-EXPRESSION]. Keep [FEATURES AND EXISTING WARDROBE TO RETAIN]. Preserve the source expression when a new one would require unseen details. Convey an affectionate, intimate remembered moment through camera light, soft rendering and grain rather than unsupported anatomy. Identity evidence takes priority over action variety, preferred view and batch variation.
```

若用户只有单侧闭嘴照却要正面哈欠，简短说明证据缺口并继续给同侧闭嘴的保守方案；不反复补图，不静默捏造。用户明确允许推测时，另行标注推测部分，不能称为忠实复原。工具未实现原像素保留就不承诺像素锁定。

## 两种输入均可附加的成像语言

```text
Tactile LOMO / lo-fi instant-film aesthetics: pronounced fine organic photochemical grain, soft small-camera optics, gently faded muted color, [RESTRAINED DIRECT FLASH WITH AMBIENT LIGHT OR CANDID NATURAL LIGHT], and one small appropriate imperfection such as [SLIGHT FOCUS SOFTNESS / SUPPORTED MOTION TRACE / SPONTANEOUS FRAMING]. Keep natural individual fur/feather color, visible marking boundaries and the emotional gesture legible. No uniform digital noise or blanket fog.

Photograph the animal as a familiar companion in an affectionate fleeting moment, with intimate camera light and gentle analog imperfections. The result feels lovable and personal, without model composure, a staged fashion pose or advertising-campaign atmosphere. Expensive clothing, if present, is incidental.

Deliver a full square image with appropriate room for the evidenced face, ears/beak and action. No text, logos, watermark, collage, date stamp or white instant-photo border unless requested. No CGI, plush toy, exaggerated eyes, human grimace, fake grin, anatomy errors, HDR or heavy sepia wash.
```

## 使用质感参照

```text
Use [IMAGE IDS] for STYLE ONLY: analog color, grain, soft focus and material realism. Do not copy the reference animal's identity, head tilt, expression, clothes or room. The permitted moment and view of a specific animal come from its identity photographs; a style-only yawn reference is not evidence of this animal's teeth or tongue.
```

## 可选微表情片段

只在新动物创作，或个体照片已有相应证据时选用；每张选一个物种适用的主瞬间。不因下列片段好看就强制覆盖个体约束。

- 眨眼（有相应眼睑的动物、只改可见眼）：`Caught halfway through a natural blink of the visible eye, relaxed mouth and ordinary eye proportions; not a deliberate human wink. Preserve the supported view and all visible markings.`
- 嘴部不对称（适用哺乳类且结构有依据）：`A tiny fleeting asymmetry from natural lip and muzzle-fur position, with a relaxed animal mouth; no human smirk or distorted jaw.`
- 舌尖（适用物种，个体编辑需口部依据）：`A small natural tongue tip briefly visible, relaxed mouth, no forced grin; retain the evidenced mouth anatomy.`
- 哈欠（适用物种，个体编辑需张嘴依据）：`Halfway through a sleepy natural yawn, eyes softly closed or narrowed, species-appropriate mouth anatomy consistent with the identity references, relaxed posture; not a scream or snarl.`
- 闭嘴停顿（单图保守选择）：`Keep the source closed-mouth or closed-beak expression and supported angle. Let the tiny pause feel intimate and endearing through soft camera light, gentle framing and tactile grain, without adding hidden mouth detail.`

新动物系列先分配不同主瞬间；具体个体系列只在已知范围内变化。若证据不足，保留角度和表情，通过光线、背景、衣料与成像变化完成请求数量，不凑四种新动作。
