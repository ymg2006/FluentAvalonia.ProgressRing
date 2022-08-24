# FluentAvalonia.ProgressRing
Templated Control library which adds new customizable WinUI progress ring for FluentAvalonia Package
Usage:

Download package from nuget and reference.

```
<!-- in App.axaml -->
<!-- Define xmlns:sty="using:FluentAvalonia.Styling" -->

<Application.Styles>
  <sty:FluentAvaloniaTheme />
  <StyleInclude Source="avares://FluentAvalonia.ProgressRing/Styling/Controls/ProgressRing.axaml" />
</Application.Styles>
```

Examlpe:
```
<!-- Define xmlns:ui="using:FluentAvalonia.UI.Controls" -->

<StackPanel>
  <Border Padding="20">
    <ui:ProgressRing StartAngle="90" EndAngle="270" Value="50" Foreground="Red" BorderThickness="5" Width="100" Height="100" />
  </Border>
  <Border Padding="20">
    <ui:ProgressRing IsIndeterminate="True" BorderThickness="10" Width="100" Height="100" />
  </Border>
</StackPanel>
```
Output:

![Light](https://github.com/ymg2006/FluentAvalonia.ProgressRing/blob/main/Preview/Light.gif)
![Dark](https://github.com/ymg2006/FluentAvalonia.ProgressRing/blob/main/Preview/Dark.gif)

Seems that there is a glitch in output but its only a gif repetition, the control's animation is smooth.
