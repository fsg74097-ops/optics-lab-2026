# 第三方资源与开发辅助说明

作品：光学实验室。版本日期：2026-10-21。本说明列明从交付代码、资源和本轮工作可核实的事实，不代替学生原创贡献证明。

## 代码与资产

| 资源 | 来源及许可 | 用途与处理 |
|---|---|---|
| 原网站源码及随仓资源 | https://github.com/banddidonunomarisa741-hub/university-optics-lab ，基线 95710c16f9a486faf226b5412c17d6ee08d2409a；仓库 MIT | 作为修订基础；保留 LICENSE。许可标识不等于逐项原创性已获独立认证 |
| Three.js r160 | https://github.com/mrdoob/three.js/tree/r160 ，MIT | 本地 vendor/three.min.js 用于实时三维；保留 THREE-LICENSE.txt |
| PptxGenJS 4.0.1 | https://github.com/gitbrent/PptxGenJS/tree/v4.0.1 ，MIT | 原教学幻灯片生成器的开发依赖，网页运行不需要；保留 package-lock.json 及 PPTXGENJS-LICENSE.txt，未打包 node_modules |
| 四组装置渲染及 Blender 工程 | 来自上述原仓库 assets/renders/、blender/；沿用仓库许可标识 | 本轮原样保留，固定图用于装置说明，不随滑块改变；没有独立认证原资产创作过程 |
| 原教学 PPT、PDF、剖面图 | 来自上述原仓库 teaching/、output/playwright/ | 保留为既有教学资源，修订 teaching-guide.md；本轮未制作新的参赛 PPT |
| 参赛截图 | 修订后网站的 Chrome 实际截图 | 8 张，未用生成式图像替代界面 |
| Noto Sans SC | https://github.com/notofonts/noto-cjk ，SIL Open Font License 1.1 | 本轮说明 PDF 嵌入字体子集；附 OFL 许可；网页仍调用设备系统字体，不分发 Windows 字体文件 |

## 理论引用

公式依据和参考入口见各模块“模型与来源”。主要来源：

- OpenStax University Physics Volume 3：https://openstax.org/books/university-physics-volume-3/pages/1-introduction
- MIT OpenCourseWare Optics 2.71：https://ocw.mit.edu/courses/2-71-optics-spring-2009/resources/lecture-notes/
- MIT 8.03SC Wave Plates：https://ocw.mit.edu/courses/8-03sc-physics-iii-vibrations-and-waves-fall-2016/resources/mit8_03scf16_lec18/
- NIST DLMF Bessel Functions：https://dlmf.nist.gov/10.2

这些是科学关系的参考来源，不是对外部图文整页复制或重新授权的声明。仅提供链接；没有把外部教材 PDF、图片或视频打入本次网站 ZIP。

## 工具与 AI 辅助

本轮使用 OpenAI Codex 辅助阅读代码、分析公式、修改 JavaScript/CSS 与讲解、编写和运行自动检查、采集真实截图、编排说明材料。AI 参与了实际编码和文档撰写，不应填报“未使用 AI”。未使用生成式图像制作本次截图。

可核实的人工输入为指定网站、参赛用途、核验和修改任务、材料范围及沿用作品名。原项目创作分工、学生此前完成内容、AI 使用比例没有可靠记录，本说明不虚构人员分工、原创比例或学生独立创作声明。报名系统的学生贡献与人工处理情况应依据实际事实填写。

验证和文档生成使用 Node.js、Chrome、Playwright、Python、ReportLab、Pillow、pypdf 与 Poppler；这些工具程序未随网站分发。Blender 清单中的版本与渲染信息来自原项目，本轮未重新生成 Blender 资源。字体许可及依赖许可与资源说明一并保留。
