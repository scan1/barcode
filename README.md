# scan
## 扫描二维码/条形码
### 依赖方式
> 项目build.gradle 中添加
> 
> maven {url'https://github.com/scan1/barcode/raw/master'}
> 
> app build.gradle 中添加依赖： compile 'com.scm:scan:1.0.5'

### 调用方式
> 调用：startActivityForResult(this,CaptureActivity.class)
> 
> onActivityResult(int requestCode, int resultCode, Intent data)中获得扫描结果：String result = data.getStringExtra(CaptureActivity.RESULT_STRING);
