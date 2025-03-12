# PaperJS DevTools

## 项目初始化

本项目使用 Vite + React + [@crxjs/vite-plugin](https://crxjs.dev/vite-plugin/getting-started/react/create-project) 作为脚手架。

## 安装方法

### 开发模式安装

1. 克隆此仓库

   ```
   git clone https://github.com/Allen7D/paperjs-devtools.git
   cd paperjs-devtools
   ```

2. 安装依赖

   ```
   yarn install
   ```

3. 构建扩展

   ```
   yarn build
   ```

4. 在 Chrome 浏览器中加载扩展
   - 打开 Chrome 浏览器，访问 `chrome://extensions/`
   - 开启"开发者模式"
   - 点击"加载已解压的扩展程序"
   - 选择项目的 `dist` 目录
