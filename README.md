# arsinavustin
<Window x:Class="WpfApplication1.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:WpfApplication1"
        mc:Ignorable="d"
        Title="MainWindow" Height="350" Width="525">
    <Grid Margin="-3,0,3,0">
        <Canvas HorizontalAlignment="Left" Height="177" Margin="10,19,0,0" VerticalAlignment="Top" Width="183">
            <StackPanel Height="100" Canvas.Left="36" Canvas.Top="44" Width="100"/>
        </Canvas>
        <StackPanel HorizontalAlignment="Left" Height="128" Margin="21,19,0,0" VerticalAlignment="Top" Width="100" Panel.ZIndex="1">
            <GroupBox x:Name="groupBox" Header="Colors" HorizontalAlignment="Left" Margin="21,19,0,0" VerticalAlignment="Top" RenderTransformOrigin="-1.521,-2.89"/>
            <RadioButton x:Name="radioButton" Content="Red" HorizontalAlignment="Left" VerticalAlignment="Top" RenderTransformOrigin="-2.771,-2.213" Checked="radioButton_Checked"/>
            <RadioButton x:Name="radioButton_Copy" Content="Blue" HorizontalAlignment="Left" VerticalAlignment="Top" RenderTransformOrigin="-2.771,-2.213" Checked="radioButton_Copy_Checked"/>
            <RadioButton x:Name="radioButton_Copy1" Content="Black" HorizontalAlignment="Left" VerticalAlignment="Top" RenderTransformOrigin="-2.771,-2.213" Height="20" Checked="radioButton_Copy1_Checked"/>
        </StackPanel>
        <StackPanel HorizontalAlignment="Left" Height="100" Margin="21,139,0,0" VerticalAlignment="Top" Width="100" Panel.ZIndex="1">
            <GroupBox x:Name="groupBox_Copy" Header="Sizes" HorizontalAlignment="Left"  VerticalAlignment="Top" RenderTransformOrigin="-1.521,-2.89"/>
            <RadioButton x:Name="radioButton1_Copy" Content="Medium" HorizontalAlignment="Left" VerticalAlignment="Top" Checked="radioButton1_Copy_Checked"/>
            <RadioButton x:Name="radioButton1_Copy1" Content="Large" HorizontalAlignment="Left" VerticalAlignment="Top" Checked="radioButton1_Copy1_Checked"/>
            <RadioButton x:Name="radioButton1" Content="Small" HorizontalAlignment="Left"  VerticalAlignment="Top" Checked="radioButton1_Checked"/>
