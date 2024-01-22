# Getting Started with the .NET MAUI BadgeView Control
The [.NET MAUI Badge View](https://www.syncfusion.com/maui-controls/maui-badge-view?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples) is a notification control that is used to notify users of new or unread messages, notifications, or status information. This article explains the steps required to configure the .NET MAUI Badge View control for .NET MAUI Badge Notifications and customize its elements.

### Adding the .NET MAUI BadgeView
**Step 1:** Add the NuGet to the project and add the namespace as shown in the following code sample:

**[XAML]**
```
xmlns:badge="clr-namespace:Syncfusion.Maui.Core;assembly=Syncfusion.Maui.Core"
```
**[C#]**
```
    using Syncfusion.Maui.Core;
```

**Step 2:** Set the BadgeView control to content in `ContentPage.`
```
<badge:SfBadgeView >        
</badge:SfBadgeView>
```
**[C#]**
``` 
SfBadgeView sfBadgeView = new SfBadgeView();
this.Content = sfBadgeView
```

**Step 3:** Adding a content

An Image, button, or label or any view can be added to the Badge View using the Content property.

```
<badge:SfBadgeView HorizontalOptions="Center" VerticalOptions="Center" BadgeText="20">
        <badge:SfBadgeView.Content>
            <Button Text="Primary" WidthRequest="120"  HeightRequest="60"/>
        </badge:SfBadgeView.Content>
</badge:SfBadgeView>
```

## Project pre-requisites

Make sure that you have the compatible versions of Visual Studio with .NET MAUI workloads and .NET SDK version in your machine before starting to work on this project. Refer to [System Requirements for .NET MAUI](https://help.syncfusion.com/maui/system-requirements).

## How to run this application?

To run this application, you need to first clone the getting-started-with-the-dotnet-maui-badge-view repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing a path too long exception when building this example project, close Visual Studio rename the repository to short, and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.

## Features and Benefits

### Position
Change and move badges to the left, right, top, bottom, bottom-left, bottom-right, top-left, or top-right position on the content as needed.

### Type
Eight predefined contextual color variants are available for badges, including primary, secondary, warning, error, and more.

### Alignment 
Align badges to their content in start, end, and center modes.

### Icon
The .NET MAUI Badge View control provides predefined notification symbols such as available, busy, away, delete, and more.

### Customization
Customize the MAUI Badge View control’s background color, text color, and font styles easily.

## Related links
[Learn More about .NET MAUI Badge View](https://www.syncfusion.com/maui-controls/maui-badge-view?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)

[Download Free Trial](https://www.syncfusion.com/downloads/maui?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)

[Pricing](https://www.syncfusion.com/sales/teamlicense?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)

[Documentation](https://help.syncfusion.com/maui/badge-view/getting-started?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)

[View Demos](https://github.com/SyncfusionExamples/getting-started-with-the-dotnet-maui-badge-view-control?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)

[Community Forums](https://www.syncfusion.com/forums/maui?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)

[Suggest a feature or report a bug](https://www.syncfusion.com/feedback/maui?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)

[Online example](https://github.com/syncfusion/maui-demos/tree/master/MAUI/BadgeView/SampleBrowser.Maui.BadgeView/Samples/BadgeView?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)

## About Syncfusion .NET MAUI Controls

Syncfusion's [.NET MAUI UI Controls](https://www.syncfusion.com/maui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples) library is the only suite that you will ever need to build an application since it contains over 40 high-performance, lightweight, modular, and responsive UI Controls in a single package. In addition to Radial Gauge, we provide popular .NET MAUI Controls such as [DataGrid](https://www.syncfusion.com/maui-controls/maui-datagrid?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)[Charts](https://www.syncfusion.com/maui-controls/maui-cartesian-charts?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [Scheduler](https://www.syncfusion.com/maui-controls/maui-scheduler?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [ListView](https://www.syncfusion.com/maui-controls/maui-listview?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), and [Excel Library](https://www.syncfusion.com/document-processing/excel-framework/maui?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples).

### About Syncfusion
Founded in 2001 and headquartered in Research Triangle Park, N.C., Syncfusion has more than 29,000 customers and more than 1 million users, including large financial institutions, Fortune 500 companies, and global IT consultancies.

Today, we provide 1800+ components and frameworks for web ([Blazor](https://www.syncfusion.com/blazor-components?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [ASP.NET Core](https://www.syncfusion.com/aspnet-core-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [ASP.NET MVC](https://www.syncfusion.com/aspnet-mvc-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [ASP.NET WebForms](https://www.syncfusion.com/jquery/aspnet-webforms-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [JavaScript](https://www.syncfusion.com/javascript-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [Angular](https://www.syncfusion.com/angular-components?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [React](https://www.syncfusion.com/react-components?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [Vue](https://www.syncfusion.com/vue-components?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), and [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)), mobile ([Xamarin](https://www.syncfusion.com/xamarin-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [UWP](https://www.syncfusion.com/uwp-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [JavaScript](https://www.syncfusion.com/javascript-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), and [.NET MAUI](https://www.syncfusion.com/maui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)), and desktop development ([WinForms](https://www.syncfusion.com/winforms-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [WPF](https://www.syncfusion.com/wpf-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [WinUI](https://www.syncfusion.com/winui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples),[UWP](https://www.syncfusion.com/uwp-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples), and [.NET MAUI](https://www.syncfusion.com/maui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples)). We provide ready-to-deploy enterprise software for dashboards, reports, data integration, and big data processing. Many customers have saved millions in licensing fees by deploying our software.

<hr style="height:0.3px;border:none;color:lightgrey;background-color:lightgrey;" />

<p align="center">
<a href="mailto:sales@syncfusion.com?Subject=Syncfusion .NET MAUI Badge View - GitHub" target="_top">sales@syncfusion.com</a> | <a href="https://www.syncfusion.com?utm_source=github&utm_medium=listing&utm_campaign=maui-badge-view-github-samples">www.syncfusion.com</a> | Toll Free: 1-888-9 DOTNET <br>
</p>