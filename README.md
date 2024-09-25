
### About

This is a custom control library for WPF.

### Photo

![alt text](https://raw.githubusercontent.com/MlemCode/public_photos/refs/heads/main/SlimControls.PNG "Title")
### Dependencies

**.NET Framework 4.5.2+**

### Installation

You can install **SlimControls** via NuGet:

```bash
Install-Package SlimControls -Version 1.0.0
```

### Usage

```cs
<Window
    ...
    xmlns:slim="clr-namespace:SlimControls;assembly=SlimControls">
    <Grid>
        <StackPanel>
            <slim:STextBox Width="200" Text="Normal"/>
            <slim:STextBox Width="200" Text="0" Type="Number"/>
            <slim:SButton Width="80" Content="Button" Type="Primary" />
        </StackPanel>
    </Grid>
</Window>
```

### License
This project is licensed under the MIT License - see the LICENSE file for details.


