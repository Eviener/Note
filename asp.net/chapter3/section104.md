# Xamarin 图片

## 1、图片显示

```markup
<AbsoluteLayout>
    <Image x:Name="TempIDCard" WidthRequest="717" HeightRequest="230">
        <Image.GestureRecognizers>
            <TapGestureRecognizer Tapped="PinchIdCard" NumberOfTapsRequired="1"/>
        </Image.GestureRecognizers>
    </Image>
</AbsoluteLayout>
```

## 2、Resources图片

加入的图片需要设置属性，生成操作--嵌入的资源

![](<../../.gitbook/assets/image (2) (1).png>)
