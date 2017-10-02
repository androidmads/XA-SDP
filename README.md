# XA-SDP
Scalable-DP Binding for Xamarin.Android

It provides a new size unit - sdp (scalable dp). This size unit scales with the screen size. It can help Android developers with supporting multiple screens.

## How to download
you can download with Nuget Package Manager
```csharp
Install-Package SDP -Version 1.0.0
```
## How to Use
In your .axml file use as like in the following
```xml
<TextView android:id="@+id/give_us_a_review_landmine_text_2"
          android:layout_width="match_parent"
          android:layout_height="wrap_content"
          android:gravity="center"
          android:text="★★★★★"
          android:textColor="#747474"
          android:textSize="@dimen/_22sdp"
          android:textStyle="bold" />
```
Here, **sdp** is a size unit and use like here **@dimen/_22sdp**
