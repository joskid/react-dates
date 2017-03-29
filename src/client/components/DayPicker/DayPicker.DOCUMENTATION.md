### Synopsis

DayPicker is a styled to OpusCapita defaults [react-day-picker](https://github.com/gpbl/react-day-picker)

* [Props Reference](http://react-day-picker.js.org/APIProps.html)
* [Methods Reference](http://react-day-picker.js.org/APIMethods.html)

### Props Reference

| Name                           | Type                    | Description                                                                                                                                                                                                         |
| ------------------------------ | :---------------------- | -----------------------------------------------------------                                                                                                                                                         |
| className                      | string                  | Default HTML behavior                                                                                                                                                                                               |
| dayPickerRef                   | func                    | Callback with default react ref behavior, but returns [react-day-picker](http://react-day-picker.js.org/) element. Useful if you want call some [methods](http://react-day-picker.js.org/APIMethods.html) |
| pickerClassName                | string                  | Class name passed to react day picker                                                                                                                                                                               |
| onChange                       | func                    | Callback fired when new date selected `date => {}`                                                                                                                                                                  |

***

See react-day-picker [props reference](http://react-day-picker.js.org/APIProps.html) if you need more customization

### Methods reference

See react-day-picker [methods reference](http://react-day-picker.js.org/APIMethods.html)

### Code Example

```
<DayPicker
  onChange={ day => console.log(day) }
/>
```

### Component Name

DayPicker

### License

Licensed by © 2017 OpusCapita
