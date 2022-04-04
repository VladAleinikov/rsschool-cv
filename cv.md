# **Vladislav Aleynikov** #
***
 ## **Contacts** ## 
***
* **Location:** Mogilev, Belarus
* **Phone:** +375 44 795-31-34
* **Email:** vlad.a.aleynikov@gmail.com
* **GitHub:** [VladAleinikov](https://github.com/VladAleinikov)

 ## **About me** ## 
***
I have good interpersonal skills, am an excellent team worker and very willing to learn and develop new skills.
I am reliable and dependable and often seek new responsibilities within a wide range of employment areas.

 ## **Skils** ## 
***
* HTML
* CSS/SASS
* JS
* JQuery
* React (Basic)
* C# (Basic)

 ## **Code example** ## 
***
```
function formatDuration(seconds) {
      let year = Math.floor(seconds / (60 * 60 * 24 * 365))
      let day = Math.floor((seconds - year * (60 * 60 * 24 * 365)) / (60 * 60 * 24));
      let hour = Math.floor((seconds - year * (60 * 60 * 24 * 365) - day * (60 * 60 * 24)) / (60 * 60))
      let min = Math.floor((seconds - year * (60 * 60 * 24 * 365) - day * (60 * 60 * 24) - hour*(60 * 60)) / 60)
      let sec = ((seconds - year * (60 * 60 * 24 * 365) - day * (60 * 60 * 24) - hour*(60 * 60)) - min * 60)
      let duration = "";
      if (year != 0)
            duration += year == 1 ?
                  `${year} year` :
                  `${year} years`;
      if (day != 0) {
            if (year != 0 && hour == 0 && min == 0 && sec == 0)
                  duration += " and ";
            else if (year != 0)
                  duration += ", ";
            duration += day == 1 ?
                  `${day} day` :
                  `${day} days`;
      }
      if (hour != 0){
            if ((year != 0 || day != 0) && min == 0 && sec == 0)
                  duration += " and ";
            else if (year != 0 || day != 0)
                  duration += ", ";
            duration += hour == 1 ?
                  `${hour} hour` :
                  `${hour} hours`;
      }
      if (min != 0) {
            if ((year != 0 || day != 0 || hour != 0) && sec == 0)
                  duration += " and ";
            else if (year != 0 || day != 0 || hour != 0)
                  duration += ", ";
            duration += min == 1 ?
                  `${min} minute` :
                  `${min} minutes`;
      }
      if (sec != 0) {
            if (year != 0 || day != 0 || hour != 0 || min != 0)
                  duration += " and ";
            duration += sec == 1 ?
                  `${sec} second` :
                  `${sec} seconds`;
      }
            
      return (duration == "") ?
            "now" :
            duration;
}
```
 ## **Experience** ## 
***
 ## **Education** ## 
***
* **University:** Belarusian Rusian University

 ## **English** ## 
***
**B1**