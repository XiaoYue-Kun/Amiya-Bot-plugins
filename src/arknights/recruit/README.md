- 普通查询
    - 发送 `兔兔公招生存防护`
- 图片识别
    - 发送 `兔兔公招` 同时附带图片
    - 发送 `兔兔公招` 后，再发送图片
- 直接发送 `与游戏公招界面相似的图片`，可跳过以上步骤。若无法识别请按上述步骤操作。

### 配置

图像识别需要额外支持。

> CQ-Http

如果你使用的是 CQ-Http 适配器，直接使用即可。

> 百度智能云

如果不是 CQ-Http 适配器，在 resource/plugins/baiduCloud.yaml 内填写 `百度智能云配置` 开启图像识别

```yaml
enable: true
appId: 21*****7
apiKey: MM************GnL5
secretKey: XR*********************U7UM
```

使用 CQ-Http 适配器也可以同时开启 `百度智能云`，会优先使用百度 OCR。
