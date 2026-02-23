# EPICS Studio 网站设计规范
# EPICS Studio Website Design Specification

> 项目: www.epics.studio  
> 客户: Kirk Johnson (Eco-Efficiency)  
> 日期: 2026-02-22  
> 状态: 设计规范文档

---

## 1. 品牌色彩系统 / Brand Color System

### 主色 (Primary Colors)
| 用途 | 颜色名称 | HEX代码 |
|------|----------|---------|
| 主色 | 浅蓝/绿 | #4ECDC4 / #45B7AA |
| 背景 | 白色 | #FFFFFF |
| 文字 | 深灰 | #333333 |

### 次色 (Secondary Colors)
| 用途 | 颜色名称 | HEX代码 |
|------|----------|---------|
| 次色 | 深蓝/深绿 | #2C3E50 / #1A5F4A |
| 强调色 | 青色 | #00B894 |
| 边框 | 浅灰 | #E0E0E0 |

---

## 2. 字体系统 / Typography

### 主字体 (Primary Font)
- **字体名称**: Roboto
- **用途**: 标题、导航、强调文字
- **字重**: 
  - 标题: 700 (Bold)
  - 正文: 400 (Regular)

### 次字体 (Secondary Font)
- **字体名称**: Open Sans
- **用途**: 正文、描述文字
- **字重**: 400 (Regular)

### 字号规范
| 元素 | 字号 | 行高 |
|------|------|------|
| 主标题 (H1) | 48px | 1.2 |
| 副标题 (H2) | 32px | 1.3 |
| 小标题 (H3) | 24px | 1.4 |
| 正文 | 16px | 1.6 |
| 按钮文字 | 14px | 1.2 |

---

## 3. Logo使用规范 / Logo Guidelines

### Logo组合
```
[Logo] | [ENSPIRE POTENTIAL IMMERSIVE CLEANTECH STUDIO]
```

- Logo与文字之间用**竖线分隔**
- 竖线颜色: 与主色一致
- 文字字体: Roboto Bold

### 尺寸规范
- Logo图片宽度: 200-300px
- 整体高度: 60-80px

---

## 4. 页面结构 / Page Structure

### 顶部区域 (Header)
- [x] Logo组合
- [ ] 导航菜单 (可选)

### 主内容区 (Main Content)

#### Section 1: 标题区
- 主标题: "Enspire Potential: Immersive Cleantech Studio (EPICS)"
- 副标题: 项目描述

#### Section 2: 介绍段落
- 关于EPICS的详细介绍
- 参考V5 PDF内容

#### Section 3: Modules介绍
- 模块内容介绍
- 相关图片

#### Section 4: 视频区域
- 保留现有EPICS Video

#### Section 5: 注册表单
- "Register to Attend 2026 EPICS Sessions"

#### Section 6: 联系表单
- 姓名、邮箱、附件上传

### 底部区域 (Footer)
- Logo阵列:
  - Enspire (彩色)
  - NRCan (带文字)
  - BOMA Canada (带竖线分隔)

---

## 5. 布局规范 / Layout

### 常用间距
- 区块间距: 60px
- 内边距: 40px (桌面) / 20px (移动)
- 元素间距: 20px

### 响应式断点
| 设备 | 宽度 |
|------|------|
| 桌面 | > 1024px |
| 平板 | 768px - 1024px |
| 手机 | < 768px |

### 容器宽度
- 最大宽度: 1200px
- 居中显示

---

## 6. 需要删除的元素
- 红色传单图片
- 黄色传单图片

---

## 7. 所需素材清单

### 需要上传的图片
| 文件名 | 用途 |
|--------|------|
| EPICS Logo Website.png | 页头Logo |
| V5 Website Items 3 and 6.png | 介绍段落配图 |
| Enspire Logo | 底部Logo |
| NRCan Logo | 底部Logo |
| BOMA Canada Logo | 底部Logo |

### 需要确认的内容
- V4 Item 6b (待定内容)
- Modules具体文案

---

## 8. 验收标准

- [ ] 颜色符合品牌规范
- [ ] 字体正确加载 (Roboto + Open Sans)
- [ ] Logo位置正确，有竖线分隔
- [ ] 介绍段落已添加
- [ ] 红黄图片已删除
- [ ] Modules区域已添加
- [ ] 视频区域保留
- [ ] 底部Logo正确排列
- [ ] 移动端响应正常

---

## 9. 参考文件

- Enspire-Brand-Guide_FINL0410.pdf (品牌指南)
- V5 Website Items 3 and 6.pdf (内容参考)
- Epics_web page examples.pdf (示例)

---

*本文档由贾维斯生成 - 2026-02-22*
