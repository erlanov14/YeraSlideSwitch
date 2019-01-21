# YeraSlideSwitch
An iOS Smart slide switch
![](https://github.com/Jucuzzi/YeraSlideSwitch/blob/master/Preview.jpg)
## How to use
### Just add the following code where you need to use it
```c
let slideSwitch = YeraSlideSwitch.init(frame: CGRect.init(x: 100, y: 200, width: UIScreen.main.bounds.size.width - 200, height: (UIScreen.main.bounds.size.width - 200)*2))
slideSwitch.backgroundColor = UIColor.clear
self.view.addSubview(slideSwitch)
slideSwitch.setOnWithAnimate()
```
### How to get the status of the switch
```c
slideSwitch.isOn()
```
### How to turn on/off switch without animation
```c
slideSwitch.setOn()
slideSwitch.setOff()
```
### How to turn on/off switch with animation
```c
slideSwitch.setOnWithAnimate()
slideSwitch.setOffWithAnimate()
```
## Requirements
iOS8.0 and above
## About the use of the control background
The switch in the homekit is large, up and down, moving elegantly and accurately judged. It is very suitable for a single switch with only one single page. It is impressive.

If you have any questions, please let me know

email：erlanov14@gmail.com

