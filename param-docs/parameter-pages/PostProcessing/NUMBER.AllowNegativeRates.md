# Parameter `AllowNegativeRates`
Default Value: `false`

Allow a meter to count backwards (decreasing values).

!!! Note
    This is unusual (it means there is a negative rate) and not wanted in most cases!

!!! Note
    If you edit the config file manually, you must prefix this parameter with `<NUMBER>` followed by a dot (eg. `main.AllowNegativeRates`). The reason is that this parameter is specific for each `<NUMBER>` (`<NUMBER>` is the name of the number sequence defined in the ROI's).
