## Setting up prepaid reload business

- posted by: [user3663854](https://stackexchange.com/users/4506704/user3663854) on 2015-11-26
- tagged: `tech-company`
- score: 1

<p>I'm interested to research on setting up a prepaid reload business similar as below site:</p>

<p><a href="http://www.smsreloadsystem.com/smsreloadsystem.html" rel="nofollow">http://www.smsreloadsystem.com/smsreloadsystem.html</a></p>

<p>From above site, it seems that there are</p>

<ol>
<li>PC </li>
<li>GSM Modem </li>
<li>Eload SIM card</li>
</ol>

<p>I'm not familiar with any prepaid reload solution, but I am coming from a hardware and software design background. As $$$ is constrained, I need to make sure that should I proceed to do RnD, I'm heading to the right direction.</p>

<p>From the system referred, I assume the GSM modem will have many port to put multiple SIM card? The SIM card is specific and special for each carrier provider, means I have to register a number from each carrier and deposit a certain amount of credit to it. Lets say I want to support for 10 provider, I register 10 different number with each. Then, I register another number so as to act as a point of contact@middleman to my system. People will send SMS to this number with different command eg. 0123456789.M10 where {targetReloadHp}.{providerSuffix}{Amount}). Then, either:</p>

<p><strong>A)</strong> Upon receiving it, the GSM modem will send the command to PC, PC will check balance from Eload SIM card and if credit is enough PC analyze the command and instruct 1 of the 10 SIM card to transfer balance to target Hp...</p>

<p><strong>B)</strong> Upon receiving it, send the command to Eload SIM card. Eload SIM card analyze the command and check the credit balance, and then if credit sufficient send back the command to PC and PC will analyze the command and instruct 1 of the 10 SIM card to transfer balance to target Hp</p>

<p>Not sure whether a) or b). If b), seems that I need to write firmware and bootloader for Eload? </p>

<p>Is this the correct flow?</p>

<p>a) or b) or the whole concept is wrong altogether? Are there any reference design? Are there any communication protocol that I need to follow? For example, I saw  ETSI GSM 07.05 mentioned in below site. But if I dont use phone, it means it doesnt apply to my case since I'm using GSM modem?</p>

<p><a href="http://www.nowsms.com/faq/what-is-a-gsm-modem" rel="nofollow">http://www.nowsms.com/faq/what-is-a-gsm-modem</a></p>


## No Answers

There were no answers to this question.


---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
