# TabView

TabView is a class which contains a TabBar and TabContent.
TabView adds TabButtons and Views to TabBar and TabContent in TabView by <see cref="TabView.AddTab"/>.
TabView removes TabButtons and Views from TabBar and TabContent in TabView by <see cref="TabView.RemoveTab"/>.
TabView selects a view from the TabContent according to the selected TabButton in the TabBar.


## Create 

To create a TabView, follow these steps:

1. Create TabView in XAML:

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
            <comp:TabView WidthSpecification="-1" HeightSpecification="-1"/>
        </comp:ContentPage.Content>

    </comp:ContentPage>

    ```
## Related Information

- Dependencies
  -   Tizen 9 and Higher 
