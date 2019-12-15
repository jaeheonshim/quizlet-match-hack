# Quizlet Match Hack
A very short piece of code that will freeze the time for quizlet match games.

Do you want to be the best at Quizlet match out of all of your friends? Well then this is for you. All you have to do is copy and paste two lines of code in the javascript console, and there you have it! Instant best Quizlet score.

Here is the code:

	document.getElementsByClassName("UIButton UIButton--hero")[0].click();
	setTimeout(function(){for(var F = setTimeout(";"), i = 0; i < F; i++) clearTimeout(i)}, 5100); //Change 5100
	
And... That's it! To use this code, first go to this part of the Quizlet match:
![Quizlet Match Main](https://raw.githubusercontent.com/jaeheonshim/quizlet-match-hack/master/quizlet.png  "Make Everything Disappear!") 

Then, right click and press inspect element. Go into the console tab, and paste the above code in there. After you do that, change the 5100 to when you want the timer to stop in milliseconds. For example, if you set it to 1000, you would get a best time of 1 second. **Note that you can't set it any lower than 500 milliseconds, or 0.5 seconds.**
Press ENTER, and the timer will stop at your desired time! However, you'll still have to answer the questions, but can do so at your leisure. Enjoy!

If you found this code snippet helpful to you and you are interested in computer programming, I would appreciate it if you could visit my [personal blog](https://jaeheonshim.com). I spend lots of time and effort writing the articles on it, and I would be very happy if I knew it gets attention on the internet. 

Jaeheon Shim
