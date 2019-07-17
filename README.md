# Bad-Practices-to-avoid-while-writing-a-report

Here are a few bad practices we must avoid while writing a report:

Avoid any spelling and grammatical errors/mistakes.
Do not flood the report with too many irrelevant statistics.
Do not write the report from a hacker's perspective as you cannot expect the reader to understand hacking concepts.
Do not use screenshots in which the details are not clearly visible. To solve this issue, take multiple small screenshots of the same page instead of taking an extremely big screenshot.
Never stretch images/screenshots that you are using in the report. Stretching the images/screenshots will make them distorted. So, if you want to make an image bigger, you can stretch it from the bottom right corner but not too much.
Don't include and explain all the steps you did to get to the hack. In the report include the steps like initial payload that acts as a PoC (like showing the database name/version) and then show what all data you extracted (like usernames and passwords etc.). The steps followed in the middle are hacker centric and are not required in the report.

# IMPORTANT
# 1
 Many pentesters clearly don't know the difference between Observation and Business Impact. Observation contains steps followed to find the vulnerability and Business Impact contains what could happen in case of a black hat hacker. So when producing a report you need to clearly mention what is the business impact of the vulnerability you found and Observation.

# 2
While curating a VAPT report, a security expert must avoid any grammatical errors and mistakes and also should not include too many irrelevant statistics for the readers.

# 3
Whenever you are submitting a VAPT report make sure that you submit references like OWASP, security focus or wiki, etc. so that the developer who is working on the patch can check the references and understand the impact of the vulnerability in the real world.

# 4
 Even though mentioning each step you did is a good thing to show in the report, you need to avoid submitting a very lengthy and boring observation. Because when a developer is reading the observation or POC he need to understand easily what and how the vulnerability occurs.
 
 # 5
 Following are some of the pro tips you need to consider when producing a report. Use a good theme, add video PoCs for complicated attacks, highlight key areas with red boxes in a screenshot to make it easier for the reader to understand, add complete HTTP requests for the attack so that the reader can replicate the bug easily using Burp suite, etc.
