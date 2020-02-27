## 说明

主要是参考了mp4的格式文档，简易实现了一下获取视频时长

导入这个包，然后调用`GetMP4Duration`方法即可，只需要实现了 `io.ReaderAt` 接口即可

```
// GetMP4Duration 获取视频时长，以秒计
func GetMP4Duration(reader io.ReaderAt) (lengthOfTime uint32, err error)
```