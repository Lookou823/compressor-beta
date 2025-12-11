# Compressor Beta

> ⚠️ **重要说明**：这是 [compressorjs](https://github.com/fengyuanchen/compressorjs) 的 Beta 测试版本，基于增强版本进行进一步开发。本版本用于新功能的测试和开发，**并非稳定版本**。

## 📋 项目来源

- **原项目**：[compressorjs](https://github.com/fengyuanchen/compressorjs) by [Chen Fengyuan](https://chenfengyuan.com/)
- **增强版本**：[Lookou823/compressorjs](https://github.com/Lookou823/compressorjs)
- **Beta 版本**：[Lookou823/compressor-beta](https://github.com/Lookou823/compressor-beta)（当前仓库）
- **原项目许可证**：MIT License

## ✨ Beta 版本特性

- 基于增强版本的所有功能
- 新功能的实验性开发
- 性能优化和改进测试
- 为未来版本准备的新特性

## 🚧 开发状态

这是一个 Beta 测试版本，主要用于：
- 新功能开发和测试
- 性能优化实验
- 社区反馈收集
- 稳定性测试

## 📦 安装

**注意：这是测试版本，建议仅在开发环境中使用**

```shell
# 从 GitHub 直接安装
npm install git+https://github.com/Lookou823/compressor-beta.git

# 或克隆仓库
git clone https://github.com/Lookou823/compressor-beta.git
```

## 🔧 使用方法

使用方法与原版 compressorjs 相同：

```js
import Compressor from 'compressor-beta';

document.getElementById('file').addEventListener('change', (e) => {
  const file = e.target.files[0];

  if (!file) {
    return;
  }

  new Compressor(file, {
    quality: 0.6,
    success(result) {
      // 处理压缩后的图片
      console.log('压缩成功:', result);
    },
    error(err) {
      console.log('压缩失败:', err.message);
    },
  });
});
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来帮助改进这个 Beta 版本。

## 📄 许可证

[MIT](https://opensource.org/licenses/MIT)

- Copyright 2018-present [Chen Fengyuan](https://chenfengyuan.com/) (原项目作者)
- Copyright 2024-present [Lookou823](https://github.com/Lookou823) (Beta 版本维护者)

本项目基于 [compressorjs](https://github.com/fengyuanchen/compressorjs) 进行修改和增强。