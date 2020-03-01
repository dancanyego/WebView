# WebView
An Android App to demonstrate web Application As a client Application.

You can Change the adress at Main Activity   private var url="https://www.theotherguyske.org/" And Change it to yours

The WebView class is an extension of Android's View class that allows you to display web pages as a part of your activity layout. It does not include any features of a fully developed web browser, such as navigation controls or an address bar. All that WebView does, by default, is show a web page.

A common scenario in which using WebView is helpful is when you want to provide information in your app that you might need to update, such as an end-user agreement or a user guide. Within your Android app, you can create an Activity that contains a WebView, then use that to display your document that's hosted online.

 Adding a WebViewto your app in the layout we Add 
 
<WebView
    android:id="@+id/webview"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
/>

Then We Load the web page in the WebView, use loadUrl() through the following line 

val myWebView: WebView = findViewById(R.id.webview)
myWebView.loadUrl("http://www.example.com")

for more info check out https://developer.android.com/guide/webapps/webview
