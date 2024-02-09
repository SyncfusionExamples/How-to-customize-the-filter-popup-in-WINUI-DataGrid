# How to customize the filter popup in WINUI DataGrid

In [WINUI - DataGrid](https://help.syncfusion.com/cr/winui/Syncfusion.UI.Xaml.DataGrid.SfDataGrid.html) (SfDataGrid), You can customize the appearance of filter popup by overriding the style of [GridFilterControl](https://help.syncfusion.com/cr/winui/Syncfusion.UI.Xaml.DataGrid.GridFilterControl.html).

 
 ```xaml
<Style x:Key="GridFilterControlStyle" TargetType="dataGrid:GridFilterControl">
    <Setter Property="Template">
        <Setter.Value>
            <ControlTemplate TargetType="dataGrid:GridFilterControl">
                ..............
                ..............
                ..............
            </ControlTemplate>
        </Setter.Value>
    </Setter>
</Style>
 ```