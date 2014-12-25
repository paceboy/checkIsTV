checkIsTV
=========

区分设备是pad，phone和tv。优先通过webview ua来判断，如果仍然无法判断，使用adb prop读取系统属性 ，判断是否有hdmi属性来区分tv和非tv。
