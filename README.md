# Alarm-Clock-Using-HTML-CSS-and-JavaScript.

I've created a fully functional alarm clock web application with the following features:

### Key Features:
1. **Real-time clock display** that shows the current time and date
2. **Set multiple alarms** using the time input
3. **Enable/disable alarms** without deleting them
4. **Delete alarms** you no longer need
5. **Audio alert** when an alarm goes off
6. **Visual indication** with a pulsing animation when an alarm is ringing
7. **Auto-stop** functionality that silences the alarm after one minute

### How to Use:
1. The current time and date are displayed at the top
2. Set a new alarm using the time picker and "Set Alarm" button
3. Manage your alarms in the list below
4. When an alarm goes off, press "Stop Alarm" to silence it

### Technical Details:
- The clock updates every second using JavaScript's `setInterval`
- Alarms are stored in an array and checked against the current time
- The interface uses a responsive design with a gradient background
- Visual feedback is provided through CSS animations and color changes

This implementation works in any modern browser and doesn't require any external dependencies or libraries beyond the included alarm sound.
