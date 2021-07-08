# RadioButton

RadioButton is the Class that describe the control which can be checked, but not cleared by a user.


## Create 

To create a RadioButton, follow these steps:

1. Create RadioButton in XAML:

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
            <comp:Button Text="Button" WidthSpecification="-1" HeightSpecification="-1"/>
        </comp:ContentPage.Content>

    </comp:ContentPage>

    ```
## Related Information

- Dependencies
  -   Tizen 6 and Higher 
