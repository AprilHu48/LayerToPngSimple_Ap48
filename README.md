# LayerToPngSimple_Ap48
通过切片创建层，导出png素材，以及json的布局信息

把脚本拷到PS安装目录中的以下位置：
\ Adob​​e Photoshop CS6（64位）\ Presets \ Scripts \ LayersToPNG.jsx
重新打开ps在文件／脚本／LayersToPNG可以找到它的位置

使用方式：
1、保证psd文件在一个独立的文件夹方便文件的管理
2、psd文件保证切图完整、命名正确
3、在ps菜单栏 文件／脚本／LayersToPNG 导出

注意事项：
1.文件-导出-存储为web格式-预设选png-24，存储-设置(选其它)-文件命名只保留一号位为文档名称，这样用插件导出的图片才会按照层命名；
2.layerstopng Padding需要设置为0，否则裁切图片像素和json数据有偏差

