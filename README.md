
# TraceTogether Reverse Engineering and Teardown

![](img/token_open.png)

## Introduction
This repository documents the reverse engineering and teardown of the TraceTogether app, the token, as other things such as the SafeEntry Gateway.

The original BlueTrace specification, as well as the TraceTogether Token Technical Writeup has also been uploaded for easier reference.

Slides for my 37C3 talk have also been uploaded here.

## How to navigate
Electronics - Contains pictures of the TraceTogether Tokens, SafeEntry Gateways, and recreated schematics for the tokens.

## Why are you doing this?
Digital contact tracing systems could be an effective tool in managing future epidemics and disease outbreaks; this technology however, can expose a lot of personal information about us - who we have been with, where have we gone, etc. People are naturally concerned about how this information would be collected, stored and used, especially if a centralized contact tracing system is implemented.

I think that the public should have the right to know how this tech works, what is inside the tokens and *especially what is inside the SafeEntry Gateways.* I personally opine that getting hackers to go for a "teardown session", knowing that they can only give assessments based on the hardware presented to them, splashing their assessments on press releases and on the news, **and then introducing a brand new component to the system (i.e SafeEntry Gateway) months later, is disingenuous at best.**

I thus consider it a duty of hackers everywhere to inspect such systems, and present their findings to the public responsibly.

Tech can be used to do a lot of good in this world, including in use cases such as epidemiology, and while building technology can be fun, as hackers and technologists, we need to understand how else our technology can be used by different actors such as governments, and having the ability to think in terms of policy design and policy analysis is important even for hackers.

Here's a few questions for you to ponder:

- Why is the possibility of abuse of the system a factor in determining using a centralized system over a decentralized one? Don’t systems using Exposure Notification or DP-3T protocols require a key from health authorities to even upload contact tracing information? Why a top-down governance approach?

- Bluetrace whitepaper admits “it is possible to implement the BlueTrace protocol and have automated notification of probable close contacts”, but dismisses the idea due to bias; who writes the algorithms to begin with, and don’t the systemic biases of a centralized organization affect how humans work?

- SafeEntry Gateways are linked to specific locations (such as mall entrances). Given that this effectively combines the SafeEntry and TraceTogether systems together, wouldn't this then create location datapoints that could be used to track a person’s movements, which may invalidate bunnie et al’s assessments? 

- The public was promised that TraceTogether data would be used only for contact tracing – it was revealed that the Criminal Procedure Code allows police officers to use TraceTogether data for criminal investigations and overrides TraceTogether’s privacy policies.  While the government has provided its reasoning on the basis of compromise in the name of public safety and security in stopping specific types of crimes, this does not guarantee reliable calibration of the safeguarding of actual public interest. Who has the mandate and discretion to reliably determine the calibration – especially given that institutional trust has already been broken via the government’s previous opacity in its breach of confidentiality? How will the government deal with potential instances of miscalibration and/or abuse by institutions, departments, agencies or actors in public or civil service?

- Are there proper counters to prevent departments from intentionally or accidentally sharing our data and information with other agencies, or employers, or even governments? How might these drive or reshape our consumer habits cyclically?

- Overall, these risk the blurring of lines between the public and private realm and corresponding duties, particularly but not exclusively in situations that involve information asymmetries and opacity combined with political lobbying, patronage, clientelism, and other risks of corrupt practices. Are there measures to address potential conflicts of interest? Given that corruption is a difficult matter to solve, far-reaching in its consequences, and global in its scope (e.g. Panama Papers), are there feasible measures to address incentives and disincentives related to these conflicts of interest?

