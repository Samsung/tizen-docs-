# TabButtonGroup

TabButtonGroup class is used to group together a set of TabButton controls.
It enables a user to select exclusively single TabButton of a group.

## Create 

To create a TabButtonGroup, follow these steps:

1. Create TabButtonGroup in XAML:

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
            <comp:TabButtonGroup />
        </comp:ContentPage.Content>

    </comp:ContentPage>

    ```
## Related Information

- Dependencies
  -   Tizen 9 and Higher 
