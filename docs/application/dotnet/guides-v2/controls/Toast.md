# Toast

Use a toast to provide simple messages when the user does not need to make an additional action or confirmation.
Unlike other popups, a toast only has the body field as it is just used for providing simple feedback to user actions.
A toast will automatically disappear after a certain time.

## Create 

To create a Toast, follow these steps:

1. Create Toast in XAML:

    ```xaml
    <?xml version="1.0" encoding="UTF-8" ?>
    <comp:ContentPage x:Class="NUIXamlTemplate.XamlPage"
      xmlns="http://tizen.org/Tizen.NUI/2018/XAML"
      xmlns:base="clr-namespace:Tizen.NUI.BaseComponents;assembly=Tizen.NUI"
      xmlns:comp="clr-namespace:Tizen.NUI.Components;assembly=Tizen.NUI.Components"
      xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
           WidthSpecification="-1"
           HeightSpecification="-1"
           BackgroundColor="White"
           PositionUsesPivotPoint="True"
           ParentOrigin="Center"
           PivotPoint="Center">

        <comp:ContentPage.Content>
            <comp:Toast WidthSpecification="-1" HeightSpecification="-1"/>
        </comp:ContentPage.Content>

    </comp:ContentPage>

    ```
## Related Information

- Dependencies
  -   Tizen 6 and Higher  
