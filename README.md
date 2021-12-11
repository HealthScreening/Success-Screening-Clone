# Success-Screening-Clone

A HTML copy of the "success" page upon completing a health screening. This is to be used for demonstration purposes
only.

# How to Use

The assets file is required to make the `page.html` file work. However, you _can_ download the repo for offline use, as
everything is 100% dynamic and controlled by parameters. You can download a copy of the repository by
clicking [this link](https://github.com/HealthScreening/Success-Screening-Clone/archive/refs/heads/main.zip).

## Parameters

* `type`: This is the type of screening being loaded. Must be one of `guest`, `employee`, or `student`.
* `name`: The **full** name of the person the screening is for. Spaces must either be URL-encoded or replaced with `+`.
* `date`: The date the screening was completed. Must be in the
  format `<weekday>, <month name> <D/DD>, <YYYY>, <hour-12>:<MM> <AM/PM>`. Spaces must either be URL-encoded or replaced
  with `+`. Example format: `Wednesday, December 8, 2021 7:15 AM`

A full request to this URL might look like this:
`file://C:\Users\User\Desktop\Success-Screening-Clone-main\page.html?type=guest&name=John+Doe&date=Wednesday,+December+8,+2021+7:15+AM`

**Note:** Replace `C:\Users\User\Desktop\Success-Screening-Clone-main\page.html` with wherever you saved the folder from
the download above. On MacOS/Linux, the path might be `/Users/User/Desktop/Success-Screening-Clone-main/page.html`.