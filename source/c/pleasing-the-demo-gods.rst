Pleasing the Demo Gods
=======================

.. image:: /_static/the-climate-reality-project-Hb6uWq0i4MI-unsplash.jpg
   :alt: Delivering Technical pitches

Guest post by `Prasanjit Singh <https://www.linkedin.com/in/prasanjit-singh/>`_

    *You are worried over missing your flight and you are stuck in a traffic jam. You notice that all the other lanes are moving but yours, so you change your lane, and alas! the cars in your new lane come to a halt while the lane that you just left starts moving!*

"*Anything that can go wrong will go wrong!*" - enter the exasperating world of `Murphy's law <https://en.wikipedia.org/wiki/Murphy%27s_law>`_
. And it has spared not even the greats. We all know about the legendary "`Blue Screen of Death <https://en.wikipedia.org/wiki/Blue_screen_of_death>`_
" that Bill Gates had when demonstrating Windows 98 operating system at the now-defunct tech conference `Comdex <https://en.wikipedia.org/wiki/COMDEX>`_.

A more recent demo goof up featured Elon Musk when his live debut of Tesla’s Cyber-truck didn’t go to plan and electric vehicle’s bulletproof glass shattered when he was trying to demonstrate just the opposite.

Demo's failing has been a recurring theme. Things have failed when they matter most and demo's fail when the stakes are high! 

So is there a higher power up there drawing the puppet strings or is it simply probabilistic mathematics? Whatever the case, there are certain pointers which when followed, reverse the Murphy's law to "*Everything that can work, will work!*". 

Using Air-gapped Environments
****
Technical demonstrations depict the first impression of your product or service to your potential customers and there are going to be moments it doesn’t work as planned. There can be variables like external libraries not getting downloaded, network is slow and so on. So trying to keep the environment as contained and air-gapped as can be is better. However, with the technology at hand today one can prepare a tight presentation with minimum chances of failure. One of the ways is to containerize images and have it in the same system where you are going to demonstrate it. This allows all the dependent libraries to be available at your disposal and can run in an air-gapped environment. And by using containers, if anything goes wrong it can be re-initiated back in minutes.

Staying away from Surprises
****
It's better to keep things simple for a demo. And when the demo is going well, it is always tempting to go a step further and show something more. But it is advisable to never exercise any capability in your demo that you have not tried out beforehand - no matter how simple. Our failures and mostly the these results of these temptations. Another thing to keep in mind is to avoid any new additions to the demo code right before the event. There should be a code-freeze a couple of days beforehand, followed by time-bound rehearsals.


Rehearsing with Timelines
****
Setup a script with the timeline of events that define your demonstration. And practice each part of your demo with a stop-watch. That will allow you to stay on-course and avoid surprises. Also, it helps you to judge how much time the script execution and other transactions take when you are demonstrating. Parts where script execution takes time, should be covered with you explaining whats going on under the hood. That keeps the audience engaged and offers an illusion of speed.


Turning it Around
****
In Bill Gates' famous `Blue Screen of Death` demo he had humorously quipped "Thats why we did't ship it yet!" 
In spite of all precautions there still would be some odd block somewhere, handling these goof-ups well is a key to a successful demonstration. And that's where humour and honesty comes handy.

Stay calm and collected, not falling apart and acknowledge that once a while something might go wrong, and that you are equipped to resolve issues like these.

Having a Contingency Plan
****
Even with all the precautions things might not go according to the script. Always have a plan B for these cases. Try to foresee what might most likely go wrong and have redundancy. For example, this can be a spare system with the demo setup, an alternate docker-compose stack setup for your demo or even a recorded version of your demonstration which can be played out in the worst of cases.


That folks, is the *abracadabra* to please the Demo Gods!


Photo by `Alejandro Escamilla <https://unsplash.com/@alejandroescamilla?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText>`_, `Felipe Furtado <https://unsplash.com/@furtado?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText>`_ on `Unsplash <https://unsplash.com/collections/3502336/consulting?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText>`_
