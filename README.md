# 孟塞尔色立体三维查看器 (Munsell 3D Viewer)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen)](https://fisherv2023.github.io/munsell-3d-viewer/)

一个基于 Three.js 的交互式3D网页应用，用于可视化孟塞尔色立体。用户可以在三维空间中自由探索色相（Hue）、明度（Value）和彩度（Chroma）之间的关系。

An interactive 3D web application built with Three.js to visualize the Munsell color solid. It allows users to explore the relationships between hue, value, and chroma in a three-dimensional space.

---

![项目截图](screenshot.png) 


## 🎨 在线演示 / Live Demo

**[点击这里在线体验 / Click here for Live Demo »](https://fisherv2023.github.io/munsell-3d-viewer/)**

## ✨ 功能特性 / Features

-   **交互式3D视图**: 使用鼠标可以自由旋转、平移和缩放色立体模型。<br>
    *Interactive 3D View*: Freely rotate, pan, and zoom the color solid model with your mouse.

-   **准确的色彩表示**: 将孟塞尔系统中的色相、明度和彩度以三维坐标的形式（圆柱坐标系）精确地呈现在空间中。<br>
    *Accurate Color Representation*: Precisely renders hue, value, and chroma from the Munsell system into 3D cylindrical coordinates.

-   **渐变中性轴**: 中心轴以从黑到白的平滑渐变展示了明度（Value）的变化，作为视觉参考。<br>
    *Gradient Neutral Axis*: The central axis displays a smooth black-to-white gradient, visually representing the Value scale as a reference.

-   **深色主题**: 采用深灰色背景，以减少环境色对颜色感知的干扰，让色彩本身更加突出。<br>
    *Dark Theme*: Utilizes a dark gray background to minimize ambient color interference and make the colors stand out.

-   **纯客户端渲染**: 无需后端服务，完全在浏览器中运行，部署简单。<br>
    *Pure Client-Side Rendering*: Runs entirely in the browser with no backend required, making deployment simple.

-   **响应式设计**: 自动适应不同大小的浏览器窗口。<br>
    *Responsive Design*: Automatically adapts to different browser window sizes.

## 🛠️ 技术栈 / Technology Stack

-   HTML5
-   CSS3
-   JavaScript (ES Modules)
-   Three.js

## 🚀 如何在本地运行 / Getting Started

由于项目使用了 ES Modules，你不能直接通过 `file://` 协议在浏览器中打开 `index.html` 文件。你需要一个本地的 Web 服务器来运行它。
<br>
*Because this project uses ES Modules, you cannot open `index.html` directly in the browser via the `file://` protocol. You need a local web server to run it.*

1.  **克隆仓库 / Clone the repository**
    ```bash
    git clone https://github.com/fisherv2023/munsell-3d-viewer.git
    ```

2.  **进入项目目录 / Navigate to the project directory**
    ```bash
    cd munsell-3d-viewer
    ```

3.  **启动本地服务器 / Start a local server** (Choose one method)

    *   **使用 Python / Using Python**:
        (如果你的电脑安装了 Python 3 / If you have Python 3 installed)
        ```bash
        python -m http.server
        ```

    *   **使用 Node.js / Using Node.js**:
        (如果你安装了 Node.js / If you have Node.js installed)
        ```bash
        npx http-server
        ```

    *   **使用 VS Code 插件 / Using a VS Code Extension**:
        安装 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 插件，然后右键点击 `index.html` 并选择 "Open with Live Server"。
        <br>
        *Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension, then right-click on `index.html` and select "Open with Live Server".*

4.  **在浏览器中打开 / Open in your browser**
    访问服务器提供的地址（通常是 `http://localhost:8000`）。
    <br>
    *Visit the address provided by the server (usually `http://localhost:8000`).*

## 🤝 贡献 / Contributing

欢迎任何形式的贡献！如果你有任何建议或发现 Bug，请随时提交 [Issue](https://github.com/fisherv2023/munsell-3d-viewer/issues)。
<br>
*Contributions of any kind are welcome! If you have any suggestions or find a bug, please feel free to open an [Issue](https://github.com/fisherv2023/munsell-3d-viewer/issues).*

## 📜 开源协议 / License

本项目采用 [MIT License](./LICENSE) 开源协议。
<br>
*This project is licensed under the MIT License.*

## ❤️ 致谢 / Acknowledgments

本项目由 **沈阳艺贝少儿美术教育** 开发。<br>
*Developed by Shenyang Yibei Children's Art Education.*
