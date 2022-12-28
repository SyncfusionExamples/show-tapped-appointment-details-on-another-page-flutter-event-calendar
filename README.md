# How to show the tapped appointment details on another page in the Flutter Calendar

A quick-start example to help you to show the tapped appointment details on another page in the Flutter Calendar.

By using the [MaterialPageRoute](https://api.flutter.dev/flutter/material/MaterialPageRoute-class.html) of the [Navigator](https://api.flutter.dev/flutter/widgets/Navigator-class.html), the Flutter Event Calendar allows you to display the appointment data in the navigation page.
Using the Flutter event calendar's [onTap](https://pub.dev/documentation/syncfusion_flutter_calendar/latest/calendar/SfCalendar/onTap.html) callback, get the [targetElement](https://pub.dev/documentation/syncfusion_flutter_calendar/latest/calendar/CalendarElement-class.html) of the calendar and navigate to the required page containing the appointment.

You can show the appointment details (subject, startTime, and endTime) in the second page by retrieving them from the constructor's parameter.

![NavigationPage](https://user-images.githubusercontent.com/46158936/204770908-99526e27-50ce-4da6-812f-e88dc41701a7.gif)

## Requirements to run the demo
* [VS Code](https://code.visualstudio.com/download)
* [Flutter SDK v1.22+](https://flutter.dev/docs/development/tools/sdk/overview)
* [For more development tools](https://flutter.dev/docs/development/tools/devtools/overview)

## How to run this application
To run this application, you need to first clone or download the ‘create a flutter maps widget in 10 minutes’ repository and open it in your preferred IDE. Then, build and run your project to view the output.

## Further help
For more help, check the [Syncfusion Flutter documentation](https://help.syncfusion.com/flutter/introduction/overview),
 [Flutter documentation](https://flutter.dev/docs/get-started/install).
