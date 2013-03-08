# How would a programmer approach privacy policy?

## Intro

<!-- Introduction: the deficit of privacy frameworks: goal oriented poicymaking -->
As a philosophical topic, privacy is relatively new and the extent to which it is a fundamental human right has generated serious debate over the past few centuries. Informed by these debates are three theoretical frameworks utilized by policymakers for tackling information privacy issues: fair information practices principles, harms, and contextual integrity. All three are appealing in some important ways, but ultimately the harms framework emerges as the most adept foundation for making responsive public policy.

<!-- The Fair Information Practices Principles (FIPPS) give us the important notion of informed consent, that privacy should only be surrendered if the individual is able to choose to disclose information about him or her self. Another, contextual integrity, rests on the idea that appropriate privacy public policy should be informed by the social norms of what is considered appropriate information flow and handling in different contexts. The harm framework is most intriguing if only for its seemingly simple premise: data usage should only be restricted when it hurts. It obviously gets more complicated than that, particularly when scaled out to entire societies, but all policy decisions should revert back to what harms are done, to whom, and is it substantially larger than the good derived to society? What the harm framework—and indeed the other frameworks too—lacks is a mechanism for determining how to actually make policy, that is, how to _prevent_ harm rather than react to it.  -->

<!-- this paper will fill this void giving a way for making normative policy around the harms framework. -->
The following aruges for a way forward for making policy around the harm framework borrowing concepts from software development as a theoretical foundation. The first section argues that other frameworks, particulary the conventional Fair Information Practices Principles and the persuasive Contextual Integrity, are inadequate public policy guides because they focus on the means of privacy rather than the ends of achieving a desired public policy outcomes. The final section outlines a mechanism  revolving around the harm framework championed by Posner, Cate, MacCarthy and others that involves a combination of corrective tort action, and small pieces of legislation directed at specific public policy outcomes. This agile public policymaking system is the way forward for information privacy, especially as these issues become more complicated.

## Philosophical foundations of the information privacy debate

<!-- Bentham -->
While there is no shortage of philosophies about human privacy, there are three whose works were particularly relevant to contemporary discussions of information privacy both over the Internet and offline. The hard utilitarian view of Jeremy Bentham, the more tempered one of John Stuart Mill, and the Immanuel Kant's libertarianism have significant value to the conversation about privacy rights and policy in the information economy.

Jeremy Bentham's utilitarian view of privacy as one economic preference out of many informed his famous advocacy for the panopticon prison. In his view, the rights of the prisoners to go about their lives in their cells privately outweighed the value of a more efficient prison system, and so a prison system based on total surveillence was considered the better option. Bentham's brutal utilitarianism saw rights and laws as human creations, tools for evaluating the sum of total happieness in society. Any laws created or decisions made should go to improve that value.

<!-- Kant -->
Bentham stood in contrast to other philosophers like Immanuel Kant who took a friendlier view toward human rights and privacy in particular. Privacy, for Kant, was one among many rights that deserved protection. An individual's right to privacy was part and parcel of his or her human dignity. Invading privacy was akin to any other assualt that reduces one huamn over another. Kant's theory was famously flawed for not providing a means of differentiating what was a right and not.

<!-- Mill -->
If Kant and Bentham were opposed, John Stuart Mill offered some middle ground. Mill was a utilitarian less focused on happienss as he was on progress of humankind. Progress, Mill argued, does not always make every individual or group happy, nor should it, but he also recognized that it _could_ do harm. The government's job, then, was to intervene when societal progess turned into societal harm. Privacy was ultimately a good thing to protect because of the variance and experimentation it encouraged. Echoing Bentham's notion that privacy can affect an individual's behavior, Mill recognized that a lack of it could impinge an individual's ability to experiment with radical ideas and a lack of experimentation in society would ultimately harm it. Thus, privacy, while maybe not a right, was certainly worth protecting. For Mill, intrusions into individual privacy are done at the risk of inhibiting that individual's ability to contribute to society in meaningful ways.

Modern information privacy frameworks can be found in penumbrae of these three philosopher's ideas about personal privacy and the extent to which it should be protected. In the Fair Information Pracitce Principles and Contextual Integrity we see the influence of Kant's concern for individual rights and liberties, but we also see some notion of the utilitarian caution against overreaching regulation.

<!-- What are the FIPPs and what are they good for? -->
## FIPPS: The Well-Intentioned Enumeration

In 1973 the Department of Health, Education, and Welfare called upon Congress to adopt a "Code of fair information practices" with five specific directions in which information should be handled. These have since become known as the Fair Information Practices Principles (FIPPs) of information privacy as they have replicated through the United STates and the world as standards for privacy policy (Cate, 2006). The five original principles were:

1. A database's existence should not be secret (transparency).
2. An individual should have some means of finding out what information about him or her is in a database (accessability).
3. Information collected for one purpose should not be used for another without the individual's consent (transparency).
4. A person should be able to amend information about him or her contained in the database (correctability).
5. The organization or person who owns the database must assue the database's reliability (quality and security) (Cate, 2006).

These five were adopted into law by the Federal Privacy Act of 1974 to protect individuals from potentially harmful information contained in federal databases.

FIPPS work well in settings like HIPPA where doctors and patients have an undersigned agreement about who should have access to sensitive medical information and for what purposes it can be used. The patient is given the opportunity to read the policy before seeing the doctor, and, presumably, is able to make an informed decision about signing the privacy statement.

<!-- Where do FIPPS run afoul -->
FIPPS run aground when applied to the wrong kind of scenario. In online services involving personal data collection, FIPPS policies result in long, meandering agreements written by corporate attorneys that individuals are supposed read before using the service. Some of these can reach upward of 8,000 words. These policies are laden with jargon and almost always go un-read (fewer than 1% of users read privacy policies). The opportunity cost for reading them is simply too high. McDonald and Cranor found the total cost to the American economy if everyone were to actually read the privacy policies of the websites they visit "on the order of $781 billion" and that number did not include time to make an informed decision about whether to accept of reject the policy and how it stood compared with other websites and services. If nobody is reading the statements to which they are agreeing, the FIP framework is not accomplishing any favorable public policy. In fact, it may be doing more harm than good.

<!-- What about Contextual Integrity -->
## What's the Scenario?

Another flaw of FIPPS was seemingly answered by Helen Nissenbaum with her theory of contextual integrity (CI): there are some privacy problems for which none of the five to eight FIPPS apply. Consent, for example, is not required for credit monitoring companies to collect, aggregate and process data about consumers. If it were, the only people who would consent would be those with good credit and the system would break down. Nissenbaum's argument was that in situations like this, the right to privacy has different social norms attached to it. There is economic incentive to being forced into the system for society (fewer bad loans being issued) and to the individuals (potentially better rates and access to credit when it is needed). Privacy, for Nissenbaum, is one social norm out of many that is both specific to and dependent on the context in which it exists. Our right to privacy, to the extent we have one, is malleable and consistent with the expectations we have of other individuals in society.

<!-- Where CI falls down -->
The goal of a contextual integrity framework is to allow for different kinds of public policy for different privacy scenarios rather than a way of thinking about privacy rights for all situations. Healthcare, for example, is far more heavily regulated through the Healthcare Information and Privacy Protection Act (HIPPA) than the credit companies are when it comes to sensitive personal information. A website like Patients Like Me, unlike a physician, is not subject to HIPPA and individuals openly share information about their medical conditions with complete strangers. Both are venues for individuals to seek information and advice on treatment of chronic and terminal illnesses. In the doctor's office the individuals can rest assured that those handling their information will handle it in a clearly defined way and risk their careers for a HIPPA violation. Online the same people are subject to a [privacy policy](http://patientslikeme.com/about/privacy) prepared by the company that expressly states its intentions to share sensitive medical information with other individuals, violating that agreement has no consequence other than (possible) banishment from the site. The CI framework says we should apply the same policy based on the social norms of the context. That is fine, except when there exists more than one set of behaviors, as we do here.

<!-- Where do we go, then, with CI? -->
Would Nissenbaum like us to repeal HIPPA to bring hospitals into compliance with Patients Like Me, or the other way around? The former would threaten to stability and integrity of the medical industry; the latter would take away a fundamental principle to the website: that sharing is open and free. Perhaps online health advice is a new context that should allow this kind of open sharing, but even if Nissenbaum were to cede that information shared in a doctor's office is a different context than information shared on a patient support webiste, CI still runs into difficulties. If they are different simply because one is online, what does that mean for electronic medical records, or Internet enabled video-conferencing with doctors? Under which context should those data be subject? There is not a clear answer for this real public policy issue under the contextual integrity framework.

<!-- We go to harms...not Harms, bwahahahahahahahahahahahaha -->
## Do no harm

The most compelling idea we can derive from Nissenbaum is a more basic idea that one privacy solution may not fit every privacy problem. There is a desire in Congress and other policyaking bodies (noably the European Union) to make policy in grand undertakings.Since 1995, for example, we have had one privacy policy regulating every electronic data use in the European Union regardless of who is using it or to what ends. 

<!-- Even in the US -->
This is less true in United States where we have many laws for different privacy problems. But all too often Congress's goal seems to be solving as many problems with one piece of legislation as possible. This has occasionally backfired, especially when different policy arenas conflict as happened with the Cyber Intelligence Sharing and Protection Act (CISPA), recently called the "Privacy-Invading Cybersecurity Spying Bill" by the Electronic Frontier Foundation and garnered 300,000 signatures in a petition to stop it. There were good things CISPA sought to accomplish, including much needed tools to combat cyber crime and attacks, but Internet advocates saw the proposed legislation as an overly broad approach that would threaten the very foundation of the Internet. The first time CISPA was proposed it failed to gain any support in the Senate after a presidential veto threat triggered by online activist petitions. The problem was Congress's attempt to take on the related but different arenas of national security _qua_ cybersecurity, privacy and intellectual property infringement.

<!-- FIPPS and CI are both flawed, Harms is the way forward. -->
Both FIPPS and Nissenbaum's Contextual Integrity have two problems that make them ineffective public policy. The former is too myopic to be effective and is instead expensive and does not achieve meaningful public policy goals. The latter is unpredictable, and, if Nissenbaum's purity is to remain as our policymaking guide, threatens some basic tenets of the knowledge economy: open and robust flow of data. A third way forward is the harms framework introduced earlier, sometimes also called the economic framework (esp. Posner 1978). The balance of this paper will argue the harms framework, when paired with an agile policymaking structure, is able to overcome its own shortcomings and serve as a better guide for privacy than either FIPPS or Contextual Integrity.

<!-- A framework for understanding when to say no, or yes, to use of personal data based on potential or actual consequences of its use -->
The harms framework champoined by Posner, MacCarthy, Cate and many others 

<!-- The dicey situation of preventing harm balanced against the First Amendment and other rights granted by the Constitution. Privacy not being one of them. -->

<!-- Harms typically shows up more in courts, especially tort cases, than in legislation. How do you legislate against harm when your goal is to legislate on privacy? -->

## Object Oreinted Policymaking (OOP)

<!-- What is OOP in programming? What is it in policymaking? -->

### Government as a Platform (GAAP), O'Riley

### Algorithmic regulation

### Agile Policymaking

<!-- Properties of Agile Programming -->

<!-- * Individuals and interactions over processes and tools
* Working software over comprehensive documentation
* Responding to change over following a plan
* Customer collaboration over contract negotiation -->

<!-- Translated to policy...-->

<!-- 
* Citizens and public policy goals over special interests and tax incentives?
* Working policy over single undertaking
* Responding to change over following an _x_-point plan 1⁄2
* Citizen collaboration over citizen appeasement -->

<!-- Applied to Privacy -->

<!-- What are the public policy goals? -->

<!-- What -->