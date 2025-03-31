
<script>
"use strict";

!function() {
  var t = window.driftt = window.drift = window.driftt || [];
  if (!t.init) {
    if (t.invoked) return void (window.console && console.error && console.error("Drift snippet included twice."));
    t.invoked = !0, t.methods = [ "identify", "config", "track", "reset", "debug", "show", "ping", "page", "hide", "off", "on" ], 
    t.factory = function(e) {
      return function() {
        var n = Array.prototype.slice.call(arguments);
        return n.unshift(e), t.push(n), t;
      };
    }, t.methods.forEach(function(e) {
      t[e] = t.factory(e);
    }), t.load = function(t) {
      var e = 3e5, n = Math.ceil(new Date() / e) * e, o = document.createElement("script");
      o.type = "text/javascript", o.async = !0, o.crossorigin = "anonymous", o.src = "https://js.driftt.com/include/" + n + "/" + t + ".js";
      var i = document.getElementsByTagName("script")[0];
      i.parentNode.insertBefore(o, i);
    };
  }
}();
drift.SNIPPET_VERSION = '0.3.1';
drift.load('f2buym3z69yw');
</script>
## About Me 

My name is Akshit Ahuja , I am a 4th year undergrad student from Guru Nanak Dev Engineering College ,who have some keen interest in traveling and writing code. I had completed my high school from Saint Thomas Senior Secondary School Ludhiana. 


## Work Experience 

1. Technical Content Writing Intern :- Content writing is not considered as a good job in India but I have a keen interest in documenting the stuff ,for me my blogs are the way to document the stuff which I have read or learned. In end of december 2020  i started my TCW intern at geeksforgeeks and my [1st article](https://www.geeksforgeeks.org/send-direct-message-on-instagram-using-selenium-in-python/) was about browser automation. I wrote about 10 [articles](https://auth.geeksforgeeks.org/user/UnworthyProgrammer/articles) in my internship and geeksforgeeks paid me approx 300 Rs for each article this was my 1st earning as a geek and I was quite excited about it.

2. Software Developer Intern :- This Intern was a life changing experience for me I learned a lot during this period. My intership started from mid of june 2021 and ended at end of september 2021. During this period I worked in the versatile atmosphere where things changed every week. I developed a microservice which acts as a wrap up for tally erp tool, also I worked on writing some ETLs.    

## Projects

1. Attendance Calculator :- This Project was based on real life problem, in our college we have 75% Attendance criteria if you don't maintain 75% attendance in particular subject then you can be detained in that subject. In our college teachers mark the attendance on moodle. Many students use to calculate how many lectures they have to attend or how many lectures they can  leave , this was routine for most of the students but the thing was that they were doing this task manually, their was the scope of automation so I developed a simple django website which take the login credentials of moodle from the user and then scrap his attendance of all subjects and calculate how many lectures he/she have to attend or how many lectures he/she can leave.

2. URL Shortner :- This project was developed by me when I started learning node.js , it was a full fledge project with authentication, autherization, registeration. So the basic work flow for the project is you have to signup to the portal after that you can login to the portal and create short urls. This project is different from the normal url shortner, if you create a short url from this project then it will look like base_url/your_user_name/short_code the difference from normal url shortner is that your short url will always have your user name. The other feature of this url shortner is that you can add password protection to your short url.

3. Fest Registeration API :- This API was developed for my college Tech Fest , Approx 10 days was left for the fest and the organisers asked to develop a website for the fest. Team decided we will develop the frontend and backend separately. I choose to work on the backend and developed simple API which provides the functonlity of creating event , Registering in particular event , sending mails to the particpants, Admin functionalities , organiser functionalities.


## My Social Links 

1. [github](https://github.com/aksh45)
2. [linkedin](https://www.linkedin.com/in/akshit-ahuja-11715616b/)
3. [personal_blog](https://techsyapa.blogspot.com)
4. [tech_blog](https://auth.geeksforgeeks.org/user/UnworthyProgrammer/articles)
5. [Instagram](https://instagram.com/aksh45.in)
6. [hackerrank](https://www.hackerrank.com/ahujaakshit20)
7. [Quasarz](https://quasarz.io/akshit)


## Note 

If you have some free lancing task for me then feel free to contact me at [ahujaakshit20@gmail.com](mailto:ahujaakshit20@gmail.com) 
