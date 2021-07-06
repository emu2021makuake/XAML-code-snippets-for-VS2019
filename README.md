# XAML-code-snippets-for-VS2019
XAML code snippets for Visual Studio 2019.

You can enter it with a shortcut like Emmet.

## Installation procedure

1. Select `Tools` - `Code Snippets Manager` from the menu.

![01](https://user-images.githubusercontent.com/81235941/121006282-b3935d80-c7cb-11eb-8bc4-896477fa4fb4.png)

2. Select the `Import` button.

![02](https://user-images.githubusercontent.com/81235941/121006316-bbeb9880-c7cb-11eb-813e-4bf854c785bc.png)

3. Select the `Xammet.snippet` file you downloaded and click the `Open` button.

![03](https://user-images.githubusercontent.com/81235941/121095506-69da5f80-c82b-11eb-8cd9-ab208c831756.png)

4. Select the `Finish` button.

![04](https://user-images.githubusercontent.com/81235941/121006375-c9088780-c7cb-11eb-8b4f-6d3fac64073a.png)

## Usage

Enter the shortcut command and type `Tab`.

![05](https://user-images.githubusercontent.com/81235941/121008126-9c556f80-c7cd-11eb-86c9-e191dc442005.png)

![06](https://user-images.githubusercontent.com/81235941/121008159-a5ded780-c7cd-11eb-9460-5788201b1d9d.png)

## List of snippets

| Shortcut      | Insert code                                                  | Description                      |
| ------------- | ------------------------------------------------------------ | -------------------------------- |
| `btn`         | `<Button Content="Button" Margin="5" />`                     | Button                           |
| `btn#`        | `<Button x:Name="btn1" Content="Button" Margin="5" />`       | Button with name                 |
| `check`       | `<CheckBox Content="CheckBox" IsChecked="True" Margin="5" />` | CheckBox                         |
| `check#`      | `<CheckBox x:Name="check1" Content="CheckBox" IsChecked="True" Margin="5" />` | CheckBox with name               |
| `radio`       | `<RadioButton Content="RadioButton" IsChecked="True" Margin="5" />` | RadioButton                      |
| `radio#`      | `<RadioButton x:Name="radio1" Content="RadioButton" IsChecked="True" Margin="5" />` | RadioButton with name            |
| `lbl`         | `<Label Content="Label" Margin="5" />`                       | Label                            |
| `tblk`        | `<TextBlock Text="TextBlock" Margin="5" />`                  | TextBlock                        |
| `tbx`         | `<TextBox Text="TextBox" Margin="5" />`                      | TextBox                          |
| `tbx#`        | `<TextBox x:Name="txt1" Text="TextBox" Margin="5" />`        | TextBox with name                |
| `lbl+tbx`     | `<Label Content="Item Name1" Margin="5,5,5,0" Padding="0" />`<br />`<TextBox Text="Item Value1" Margin="5,0,5,5" />`        | Label and TextBox|
| `tblk+tbx`    | `<TextBlock Text="Item Name1" Margin="5,5,5,0" />`<br />`<TextBox Text="Item Value1" Margin="5,0,5,5" />`        | TextBlock and TextBox|
| `list`        | `<ListBox ItemsSource="{}" SelectedIndex="0" Margin="5" />`  | ListBox                          |
| `list#`       | `<ListBox x:Name="list1" ItemsSource="{}" SelectedIndex="0" Margin="5" />` | ListBox with name                |
| `list>li`     | `<ListBox SelectedIndex="0" Margin="5">`<br/>`    <ListBoxItem Content="item1" />`<br/>`</ListBox>` | ListBox containing ListBoxItem   |
| `combo`       | `<ComboBox ItemsSource="{}" SelectedIndex="0" Margin="5" />` | ComboBox                         |
| `combo#`      | `<ComboBox x:Name="combo1" ItemsSource="{}" SelectedIndex="0" Margin="5" />` | ComboBox with name               |
| `combo>ci`    | `<ComboBox SelectedIndex="0" Margin="5">`<br/>`    <ComboBoxItem Content="item1" />`<br/>`</ComboBox>` | ComboBox containing ComboBoxItem |
| `border`      | `<Border BorderBrush="Black" BorderThickness="1" Height="100" Width="100" />` | Border               |
| `rect`        | `<Rectangle Fill="LightGray" Height="100" Width="100" Stroke="Black" />`      | Rectangle            |
| `img`         | `<Image Source="image1.png" />`                              | Image                            |
| `rds`         | `<Grid.RowDefinitions></Grid.RowDefinitions>`                | Grid RowDefinitions              |
| `cds`         | `<Grid.ColumnDefinitions></Grid.ColumnDefinitions>`          | Grid ColumnDefinitions           |
| `grid`        | `<Grid></Grid>`                                              | Grid                             |
| `stack`       | `<StackPanel></StackPanel>`                                  | StackPanel                       |
| `stackh`      | `<StackPanel Orientation="Horizontal"></StackPanel>`         | Horizontal StackPanel            |
| `wrap`        | `<WrapPanel></WrapPanel>`                                    | WrapPanel                        |
| `dock`        | `<DockPanel></DockPanel>`                                    | DockPanel                        |
| `stack>btn*3` | `<StackPanel>`<br />`    <Button Content="Button1" Margin="5,5,5,0" />`<br />`    <Button Content="Button2" Margin="5,5,5,0" />`<br />`    <Button Content="Button3" Margin="5,5,5,0" />`<br />`</StackPanel>` | StackPanel containing 3 Buttons  |
| `stackh>btn*3` | `<StackPanel Orientation="Horizontal">`<br />`    <Button Content="Button1" Margin="5,5,0,5" />`<br />`    <Button Content="Button2" Margin="5,5,0,5" />`<br />`    <Button Content="Button3" Margin="5,5,0,5" />`<br />`</StackPanel>` | Horizontal StackPanel containing 3 Buttons  |
| `rds>rd*2`    | `<Grid.RowDefinitions>`<br />`        <RowDefinition Height="1*" />`<br />`        <RowDefinition Height="1*" />`<br />`</Grid.RowDefinitions>` | 2 rows Grid                      |
| `rds>rd*3`    | `<Grid.RowDefinitions>`<br />`        <RowDefinition Height="1*" />`<br />`        <RowDefinition Height="1*" />`<br />`        <RowDefinition Height="1*" />`<br />`</Grid.RowDefinitions>` | 3 rows Grid                      |
| `cds>cd*2`    | `<Grid.ColumnDefinitions>`<br />`        <ColumnDefinition Width="1*" />`<br />`        <ColumnDefinition Width="1*" />`<br />`</Grid.ColumnDefinitions>` | 2 columns Grid                   |
| `cds>cd*3`    | `<Grid.ColumnDefinitions>`<br />`        <ColumnDefinition Width="1*" />`<br />`        <ColumnDefinition Width="1*" />`<br />`        <ColumnDefinition Width="1*" />`<br />`</Grid.ColumnDefinitions>` | 3 columns Grid                   |
| `style`       | `<Style TargetType="Button"></Style>`           | Style                            |
| `style#`      | `<Style x:Key="key1" TargetType="Button"></Style>`           | Style with key                   |
| `winres`   | `<Window.Resources></Window.Resources>`  | Window Resources   |
| `pgres`   | `<Page.Resources></Page.Resources>`  | Page Resources   |
| `ucres`   | `<UserControl.Resources></UserControl.Resources>`  | UserControl Resources   |

## FYR Visual Studio 2019 default snippets

| Shortcut  | Insert code                                                  | Description                          |
| --------- | ------------------------------------------------------------ | ------------------------------------ |
| `#region` | `<!--#region NewRegion -->`<br/>`<!--#endregion-->`          | Collapsible XAML regions             |
| `ddc`     | `d:DataContext="{d:DesignInstance Type=local:MyViewModel, IsDesignTimeCreatable=True}"` | DataContext attribute at design time |
| `rd`      | `<RowDefinition Height="1*" />`                              | Grid row definition                  |
| `cd`      | `<ColumnDefinition Width="1*" />`                            | Grid column definition               |
| `set`     | `<Setter Property="Background" Value="Red" />`               | Setter                               |
| `tag`     | `<Grid></Grid>`                                              | Any tag                              |
