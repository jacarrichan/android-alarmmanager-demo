This demo application demonstrates how to set an alarm using the Android AlarmManager service.

In this example, we set an alarm that goes off five seconds after being launched.  The alarming activity then plays the default alarm on the device.

To read a blog post about this demo, [check it out here](http://nerdwin15.com/2013/04/android-creating-an-alarm-with-alarmmanager/).

```
这个应用在小米 'MIUI-JXDCNBA9.0'和魅族 “flyme OS 2.5.2(A12328)”上工作不正常，原因是定制系统对原生Android有修改，使得AlarmManager工作不正常
表现为AlarmManager指向的PendingIntent不能在指定时间唤醒


```
