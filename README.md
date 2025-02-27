<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/189013940/24.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T828690)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->

# WPF AutoSuggestEdit - Use Data Grid with InfiniteAsyncSource as Editor Drop-down

This example embeds [GridControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.GridControl) with [InfiniteAsyncSource](https://docs.devexpress.com/WPF/10803/controls-and-libraries/data-grid/binding-to-data/binding-to-any-data-source-with-virtual-sources) into the drop-down control of [AutoSuggestEdit](https://docs.devexpress.com/WPF/DevExpress.Xpf.Editors.AutoSuggestEdit):

![AutoSuggestEdit InfiniteAsyncSource](./i/AutoSuggestEdit_InfiniteAsyncSource.gif)

Convert text entered by a user to filter criteria and assign it to the [FixedFilter](https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataControlBase.FixedFilter) property to filter **GridControl** items. The conversion is implemented in the **GetFilter** method, and you can change this method according to your needs.

## Files to Review

* [MainWindow.xaml](./CS/MainWindow.xaml)
* [MainWindow.xaml.cs](./CS/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/MainWindow.xaml.vb))

## Documentation

* [AutoSuggestEdit](https://docs.devexpress.com/WPF/DevExpress.Xpf.Editors.AutoSuggestEdit)
* [Bind the WPF Data Grid to any Data Source with Virtual Sources](https://docs.devexpress.com/WPF/10803/controls-and-libraries/data-grid/bind-to-data/bind-to-any-data-source-with-virtual-sources)

## More Examples

* [How to Populate WPF AutoSuggestEdit Asynchronously](https://github.com/DevExpress-Examples/out-of-maintenance-How-to-populate-AutoSuggestEdit-asynchronously)
* [WPF Data Grid - Use AutoSuggestEditSettings](https://github.com/DevExpress-Examples/wpf-data-grid-use-autosuggesteditsettings)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-autosuggestedit-use-grid-with-infiniteasyncsource-as-drop-down&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-autosuggestedit-use-grid-with-infiniteasyncsource-as-drop-down&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
