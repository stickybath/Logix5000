# RSLogix5000 Useful code #

Useful utility code to be used in Rockwell RSLogix 5000 programs.

---
## SecondsToTime ##


This add-on takes a DINT of seconds and converts it to a human-readable formatted string displaying Hours, Minutes, and Seconds.

### Usage - ###
 Input Parameters -
 - RawSeconds (DINT)

 Output Parameters - 
 -  Time (STRING)

 Usage - 
  - ![Screenshot of Usage](images/SecondsToTime_1.PNG "Screenshot of Usage")
  ---

## DayOfWeek ##


This add-on takes a Day, Month, and Year DINT and converts it to a Day of Week DINT.
This should replace all code that relies on the day of week being entered manually seperate from the time/date.


### Usage - ###
 Input Parameters -
 - Imp_Year (DINT)
 - Imp_Month (DINT)
 - Imp_Day (DINT)

 Output Parameters - 
 -  Out_DayOfWeek (DINT) 
 - - 0=Sun, 1=Mon, 2=Tue, 3=Wed, 4=Thu, 5=Fri, 6=Sat

 Usage - 
  - ![Screenshot of Usage](images/DayOfWeek_1.PNG "Screenshot of Usage")
  ---