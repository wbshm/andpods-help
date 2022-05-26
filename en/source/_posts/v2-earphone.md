--
title: Headset - Description
date: 2022-05-12 17:55:20
tags:
---

## Headphones - Interface
{% asset_img erji.jpg 240 503.72 image %}


### Switching headphones
> If you have more than one headset, you can switch the current headset manually

### More functions
* Add headset: pair a new headset model
* Change name: rename the headset name through the system's Bluetooth settings
* Remove headset: you can remove the headset that has been paired, you need to re-pair to continue to use the software's functions after removal

### Headset model
* Intelligent identification model
    * Recommended to use automatic identification of headset model
    * Different headset models support different functions, headset model selection may not be able to display the power

* Manual model change
    * If the current headset model is determined. You can manually select

{% asset_img xinghao.jpg 240 503.72 image %}


### Auto pop-up window
{% asset_img tc.jpg 240 503.72 image %}
* Connect to automatic popups
    > When this feature is enabled, a pop-up window will appear whenever the headset and phone are automatically connected.
* Duration of pop-up window
    > Set the duration of the pop-up window
* Pop-up window in lock screen
    > You can switch whether to display pop-up windows in the lock screen
* Pop-up window in landscape
    > switchable whether to display pop-ups in landscape mode
    > Suggest users who play games can turn off the horizontal pop-up window to avoid affecting the game experience

### In-ear detection
* Putting on and taking off the headset will automatically trigger the corresponding function (play/pause)
* Due to hardware incompatibility, there will be a delay of about 2~5s in the in-ear check, there is no good solution yet
* Common problem: [Unable to in-ear check](/2020/07/09/normal/# In-ear detection failure)

### Audio control
* Trigger the corresponding function by touching the earphone regularly.
* Touch position
{% asset_img chumoweizhi.jpg 240 279.57 image %}
* Two taps: Touch the specified position two times in a row to trigger the function (play/pause, previous song, next song, voice assistant)
* Four taps: Touch the specified position four times in a row to trigger the function (play/pause, previous song, next song, voice assistant)


### Key replacement
* Set pressure-sensitive control, you can replace the default function with voice wake-up

### Left and right power interchange (high imitation only)
* The Bluetooth protocol of high imitation is different from the genuine one, there may be a situation that the power of left and right ears are swapped
* If the left and right ears are swapped, you can adjust the normal display by turning on the settings

### Find location
* The app will record the geographical location of the last time you used the headset to help you find the headset
* If the headset is nearby, you can try to connect the headset and play the sound to help locate the headset
* If the value is missing the headset all the time, you can try to turn off the left channel/right channel to assist in confirmation
{% asset_img chazhaoerji.jpg 240 503.72 image %}

#### Nearby headset
> This feature uses Bluetooth signal ranging to achieve
    
* There are a few things to keep in mind when using it.
    * Due to the limitation of Bluetooth signal strength and penetration ability, the distance may be limited to 10 meters, and is susceptible to environmental interference
    * The headset needs to be in use: remove the headset, and the headset has power before the Bluetooth signal will be issued
* How to use.
    * The list shows the nearby eligible headsets, you can choose to track your headset
    * If the headset is far away, you can walk around to get closer to the headset
    * If the headset has been paired, you can try to connect the headset to play the sound when you are close to the headset, to help you determine the location of the headset
{% asset_img fujinerji.jpg 240 503.72 image %}
#### Special Notes.
* Playback sound will adjust the sound to the maximum and play, please do not play while wearing the operation
* We do not upload the data to the cloud because it involves sensitive private information (geolocation) of the user. The data only exists locally. (operations such as reinstalling apps, changing devices, etc. will result in data loss)

### Backend resident settings
> This is a necessary setting for the stable operation of the app
* The system may clean up the application background, resulting in the failure of pop-up windows, power display and other application functions, you can set it accordingly to avoid the system killing the background
* [Background resident program](/2020/12/22/normal-permanent/# background resident settings)