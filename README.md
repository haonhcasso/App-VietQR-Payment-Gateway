# VietQR Payment Gateway Demo

VietQR Payment Gateway Example build using flutter

Screenshots :

![alt text](https://res.cloudinary.com/taskmanagereaglob123/image/upload/v1641463776/ezgif-5-12eaf0219b_1_jgbidx.gif "Webview 1")



## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.io/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.io/docs/cookbook)

For help getting started with Flutter, view our 
[online documentation](https://flutter.io/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.

This project using plugin [flutter_webview_plugin](https://pub.dartlang.org/packages/flutter_webview_plugin).

```
Widget buildWebview(){
    return WebviewScaffold(
        url: "https://www.google.com",
        appBar: new AppBar(
        title: new Text("Widget webview"),
        ),
    )
}
```
