# MOL-SZU 课题组网站

面向 GitHub Pages 的静态学术网站。中文为主，保留英文论文题目与项目名称。

## 网站内容

- 研究方向：多目标与动态优化、大模型驱动的算法设计、自进化与开放式进化。
- 四个公开项目：DMOP、SoM-EMOA、HSS-MEoH、Multi-objective NCA。
- 六篇论文选辑。
- 尚可（Ke Shang）简介、照片，以及两位博士生、四位硕士生。
- 招生专业、研究方向及学术联系邮箱。

## 发布至 GitHub Pages

目标仓库为 `MOL-SZU/MOL-SZU.github.io`；发布完成后的预期地址是 https://mol-szu.github.io/ 。该地址在成功部署前不代表已上线。

网站源码已上传到本仓库根目录。

1. 打开 Settings → Pages，查看当前仓库与账号的 Pages 可用性提示。
2. 在 Build and deployment 下选择 `Deploy from a branch`；Branch 选择 `main`，目录选择 `/ (root)`，保存。
3. 等待 Pages 部署完成，以 Settings → Pages 显示的地址为准。

仓库创建时为 Private；上传源码不会更改仓库可见性，也不会自动开启 Pages。若设置页面提示当前方案不支持此仓库的 Pages，请按 GitHub 提示调整可见性或方案。部署配置由仓库管理员在设置中完成。

## 本地查看与维护

解压后直接用浏览器打开 `index.html`，无需安装依赖。

- 修改正文、成员、论文和项目：编辑 `index.html`。
- 修改颜色、间距及响应式布局：编辑 `styles.css`。
- 替换个人照片：更新 `ke-shang.jpg`。
- 站点图标：`favicon.svg`。
- `.nojekyll` 用于关闭 Jekyll 处理；它可能被文件管理器隐藏，本网站即使按普通静态内容处理也不依赖任何下划线目录。

页面不调用外部字体、统计服务或 GitHub API，没有 API 密钥或构建依赖。公开项目采用已核实的快照，增加项目后需要更新正文。

## 内容来源与范围

资料核对日期：2026-09-10。

- 教师简介、照片、研究兴趣、论文书目信息、奖项、学生名单与招生信息： https://ai.szu.edu.cn/info/1075/1318.htm
- GitHub 组织： https://github.com/MOL-SZU
- DMOP： https://github.com/MOL-SZU/DMOP/blob/main/README.md
- SoM-EMOA： https://github.com/MOL-SZU/SoM-EMOA/blob/main/README.md
- HSS-MEoH： https://github.com/MOL-SZU/HSS-MEoH/blob/main/README.md
- NCA： https://github.com/MOL-SZU/Pareto-Optimal-Neural-Cellular-Automata-Guided-by-Foundation-Models/blob/main/README.md

课题组名称暂沿用用户提供的 GitHub 组织名 MOL-SZU，不推测英文全称。学生姓名与年级严格采用学校个人主页；未从论文作者名单推测团队成员。论文选辑不是完整发表列表；年份依照学校个人主页记载。首页 Pareto 图是概念示意，不是实验结果。照片采用用户指定个人主页中的原图。

## 验证范围

已检查 HTML 解析、内部锚点、资源引用、唯一 ID、照片文件解码及发布文件结构。包含移动端布局规则、键盘焦点、跳转正文链接与减少动态效果设置。本轮未进行浏览器截图测试；未执行 GitHub Pages 线上验证。
