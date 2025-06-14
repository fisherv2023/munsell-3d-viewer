# 孟塞尔色立体三维查看器 (Munsell 3D Viewer)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen)](https://fisherv2023.github.io/munsell-3d-viewer/)

一个基于 Three.js 的交互式3D网页应用，用于可视化孟塞尔色立体。用户可以在三维空间中自由探索色相（Hue）、明度（Value）和彩度（Chroma）之间的关系。

An interactive 3D web application built with Three.js to visualize the Munsell color solid. It allows users to explore the relationships between hue, value, and chroma in a three-dimensional space.

---

![项目截图](screenshot.png) 

## 🎨 在线演示 (Live Demo)

**[点击这里在线体验 »](https://fisherv2023.github.io/munsell-3d-viewer/)**

## ✨ 功能特性 (Features)

-   **交互式3D视图**: 使用鼠标可以自由旋转、平移和缩放色立体模型。
-   **准确的色彩表示**: 将孟塞尔系统中的色相、明度和彩度以三维坐标的形式（圆柱坐标系）精确地呈现在空间中。
-   **渐变中性轴**: 中心轴以从黑到白的平滑渐变展示了明度（Value）的变化，作为视觉参考。
-   **深色主题**: 采用深灰色背景，以减少环境色对颜色感知的干扰，让色彩本身更加突出。
-   **纯客户端渲染**: 无需后端服务，完全在浏览器中运行，部署简单。
-   **响应式设计**: 自动适应不同大小的浏览器窗口。

## 🛠️ 技术栈 (Technology Stack)

-   **HTML5**
-   **CSS3**
-   **JavaScript (ES Modules)**
-   **Three.js**: 核心的3D渲染库。

## 🚀 如何在本地运行 (Getting Started)

由于项目使用了 ES Modules，你不能直接通过 `file://` 协议在浏览器中打开 `index.html` 文件。你需要一个本地的 Web 服务器来运行它。

1.  **克隆仓库**
    ```bash
    git clone https://github.com/fisherv2023/munsell-3d-viewer.git
    ```

2.  **进入项目目录**
    ```bash
    cd munsell-3d-viewer
    ```

3.  **启动本地服务器** (任选一种方式)

    *   **使用 Python (推荐)**:
        如果你的电脑安装了 Python 3，请运行：
        ```bash
        python -m http.server
        ```

    *   **使用 Node.js**:
        如果你安装了 Node.js，可以安装并使用 `http-server`：
        ```bash
        npx http-server
        ```

    *   **使用 VS Code 插件**:
        如果你使用 Visual Studio Code，可以安装 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 插件，然后右键点击 `index.html` 并选择 "Open with Live Server"。

4.  **在浏览器中打开**
    打开你的浏览器并访问服务器提供的地址（通常是 `http://localhost:8000`）。

## 🤝 贡献 (Contributing)

欢迎任何形式的贡献！如果你有任何建议或发现 Bug，请随时提交 [Issue](https://github.com/fisherv2023/munsell-3d-viewer/issues)。

## 📜 开源协议 (License)

本项目采用 [MIT License](./LICENSE) 开源协议。

## ❤️ 致谢 (Acknowledgments)

本项目由 **沈阳艺贝少儿美术教育** (Shenyang Yibei Children's Art Education) 开发。
