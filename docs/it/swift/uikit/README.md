# UIKit

[[toc]]

## 基础组件

### UIButton

:::details 点击查看代码
```swift
let cameraButton = UIButton()

func initSubViews() {
    cameraButton.setTitle("Camera", for: .normal)
    cameraButton.setTitleColor(UIColor.white, for: .normal)
    cameraButton.backgroundColor = UIColor.orange
    cameraButton.addTarget(self, action: #selector(cameraButtonClick), for: .touchUpInside)
    self.view.addSubview(cameraButton)
}

@objc func cameraButtonClick() {
    print("Button click!")
}
```
:::

## 学习资源

[Swift 基础教程](https://itisjoe.gitbooks.io/swiftgo/content/ch1/ch1.html)