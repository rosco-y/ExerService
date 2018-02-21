# ExerService
Alarm Clock to Remind Users to Exercise on Regular Intervals.
--
## DESCRIPTION
The ExerService application is intended to work like an alarm clock that reminds the user to take short exersize breaks during the day.  For Example, the alarm would be triggered using data describing the events in the following exercise list:

---
# Exercise List
1. After the first hour, the user is reminded to do *n* pushups-ups.
1. After the second hour, the user is reminded to do *n* sit-ups.
1. After the third hour, the user is reminded to plank for *n* minutes.
1. After the fourth hour, the user is reminded to do something with his dumb bells.
1. After the fifth hour, The cycles continues at the beginning of the exercize list.

---
* ExerService is user configurable with a provided GUI:
  1. Alarm Intervals.
  1. Exersize Types.
  1. Exersize Amounts (i.e., "10" pushups)
* ExerService runs when the user logs in.
* ExerService uses mysql, or an ini file for configuration settings.
* ExerService runs in the background, so that the only regular interaction with the user is in response to prompts to exercise.
* A GUI is provided to configure the service.
