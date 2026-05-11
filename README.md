# 端到端咨询公开课宣传页 - 部署指南

## 文件夹结构
```
deploy-e2e/
├── index.html      # 主页面
├── images/         # 讲师图片
│   ├── 陈立云.png
│   ├── 金国华.png
│   └── 詹老师.png
└── pdfs/           # 课程大纲PDF
    ├── 001流程规划与落地.pdf
    ├── 002流程设计与优化.pdf
    ├── 003流程绩效管理.pdf
    ├── IT 架构规划.pdf
    ├── AI+流程管理.pdf
    ├── 11月上海站大纲.pdf
    ├── 5月上海站课程大纲.pdf
    ├── 变革项目管理.pdf
    ├── 流程绩效实战.pdf
    ├── 流程型组织建设.pdf
    ├── 流程战略规划.pdf
    ├── 流程战略规划.pdf
    ├── 流程优化实战.pdf
    ├── 流程战略规划.pdf
    ├── 流程型组织建设.pdf
    ├── 流程设计实战.pdf
    ├── 流程审计实战.pdf
    ├── 流程绩效实战.pdf
    ├── 流程战略规划.pdf
    ├── 卓越运营管理.pdf
    ├── 数字化转型规划.pdf
    ├── 基于流程的战略解码.pdf
    └── 流程绩效实战.pdf
```

## 部署方式

### 方式一：GitHub Pages（推荐）

1. 登录 GitHub，创建新仓库 `e2e-public`
2. 将 `deploy-e2e` 文件夹内容全部上传
3. 进入仓库 Settings → Pages
4. Source 选择 `Deploy from a branch`，Branch 选择 `main`，Folder 选择 `/ (root)`
5. 等待部署完成，访问 `https://你的用户名.github.io/e2e-public/`

### 方式二：Netlify Drop

1. 访问 https://app.netlify.com/drop
2. 直接拖拽 `deploy-e2e` 文件夹到页面
3. 自动生成临时链接，可绑定自定义域名

### 方式三：阿里云/腾讯云OSS

1. 创建OSS Bucket，设置为静态网站托管
2. 上传 `deploy-e2e` 文件夹内容
3. 配置自定义域名

## 部署后链接

部署完成后请告诉我，我帮你更新链接。

## 更新内容

如需更新页面内容：
1. 修改 `index.html`
2. 重新上传到对应平台
