# GyScanner
[![](https://jitpack.io/v/glWinter/GyScanner.svg)](https://jitpack.io/#glWinter/GyScanner)

## 使用方式

1. 引入jitpack
```sh
maven { url 'https://jitpack.io' }
```
2. 引入GyScanner
```sh
implementation 'androidx.appcompat:appcompat:1.6.1'
```
3. 在布局文件中使用Scanner
```
<com.glwinter.GyScanner.ScannerView
  android:id="@+id/scanner"
  app:frame_position = "center"
  android:layout_width="match_parent"
  android:layout_height="match_parent"/>
```
### 属性说明

| 属性 | 描述 |
| --- | --- |
| scan_box_position | 扫描框位置 |
| scan_box_color | 扫描框颜色 |
| mask_color | 遮罩颜色 |

4. 代码使用
```java

```
