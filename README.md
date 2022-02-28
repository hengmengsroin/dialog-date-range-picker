## dialog_date_range_picker

Shows a full screen modal dialog containing a Material Design date range picker.

## how to use

```
void showCustomRangePicker() async {
    var res = await showTCRDateRangePicker(
      context: context,
      // selectRange: CustomDateTimeRange(start: DateTime.now(), end: DateTime.now().add(Duration(days: 6))),
      selectRange: CustomDateTimeRange(),
      validRange: CustomDateTimeRange(start: DateTime(2021, 1), end: DateTime(2022, 7)),
    );
    print('res = $res');
  }
```

## Images

![img](https://github.com/hengmengsroin/dialog-date-range-picker/blob/main/res/date_range_picker.jpg)
