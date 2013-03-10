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

<!-- Where FIPPS came from and what they are -->
In 1973 the Department of Health, Education, and Welfare called upon Congress to adopt a "Code of fair information practices" with five specific directions in which information should be handled. These have since become known as the Fair Information Practices Principles (FIPPs) of information privacy as they have replicated through the United STates and the world as standards for privacy policy (Cate, 2006). The five original principles were:

1. A database's existence should not be secret (transparency).
2. An individual should have some means of finding out what information about him or her is in a database (accessability).
3. Information collected for one purpose should not be used for another without the individual's consent (transparency).
4. A person should be able to amend information about him or her contained in the database (correctability).
5. The organization or person who owns the database must assue the database's reliability (quality and security) (Cate, 2006).

<!-- Which FIPPS? -->
These five were adopted into law by the Federal Privacy Act of 1974 to protect individuals from potentially harmful collection and use of information about them in federal databases. Eventually these basic concepts would, in some form, make their way into other US regulations (notably the FTC), the OECD the EU Data Protection Directive, and APEC's framework. Each agency adopting this framework has enumerated the exact language differently, some (the EU and OECD) more restrictive than others (the FTC), leading legal scholar Fred Cate to ask "which FIPPS" should we follow (Cate, 2006)?

<!-- Where it works well. -->
Though Cate argues that FIPPs have entirely failed, they have done us some good. FIPPS works as a way of thinking about privacy and the values at stake when making public policy. The basic principle of transparency in data transactions speaks to a more deeply seeded value that there is a trust relationship in the disclosure of information between the one sending and the other receiving it. Similarly with the final principle, that information should be secure in storage. The desired public policy outcome is that in exchange for disclosing data to a third party, the individual will be given a fair idea of who has access to them, and for what ends.

<!-- Where do FIPPS run afoul -->
The problem with FIPPs is that the mechanisms required to implement any kind of policy enforcing these principles is unwieldly. Instead of the desired public policy outcome, FIPPs-based policies result in meandering agreements, dozens of pages long written by corporate attorneys that individuals are supposed read before using the service. These jargon-laden policies almost always go un-read (fewer than 1% of users read privacy policies (Cate, 2006)). The opportunity cost for reading them is simply too high. McDonald and Cranor found the total cost to the American economy if everyone were to actually read the privacy policies of the websites they visit "on the order of $781 billion" and that number did not include time to make an informed decision about whether to accept of reject the policy and how it stood compared with other websites and services. If nobody is reading the statements to which they are agreeing, the FIPPs are not accomplishing their public policy goals. In fact, they may be doing more harm than good. 

The Consumerist and many others recently [reported a stunt](http://consumerist.com/2010/04/16/read-fine-print-or-gamestation-may-own-your-soul/) carried out by GameStation wherein by agreeing to the terms of use, the UK-based online game retailer "owned the immortal souls" of its customers (Consumerist, 2013). While this is obviously a ruse and the terms of service is a separate legal agreement from the privacy policy, in this case 7500 people were harmed by a public policy mechanism that also relied on a [long and complicated legal agreement consumers were supposed to read but did not](http://www.measuringusability.com/blog/eula.php) (Sauro, 2011). It is not hard to imagine an organization doing something similar to the privacy policies nobody is reading.

<!-- What about Contextual Integrity -->
## What's the Scenario?

Another flaw of FIPPS was seemingly answered by Helen Nissenbaum with her theory of contextual integrity (CI): there are some privacy problems for which none of the many-enumerated FIPPS apply. Consent, for example, is not required for credit monitoring companies to collect, aggregate and process data about consumers. If it were, the only people who would consent would be those with good credit and the system would break down. Nissenbaum's argument was that in situations like this, the right to privacy has different social norms attached to it. There is economic incentive to being forced into the system for society (fewer bad loans being issued) and to the individuals (potentially better rates and access to credit when it is needed). Privacy, for Nissenbaum, is one social norm out of many that is both specific to and dependent on the context in which it exists. Our right to privacy, to the extent we have one, is malleable and consistent with the expectations we have of other individuals in society.

<!-- Where CI falls down -->
The goal of a contextual integrity framework is to allow for different kinds of public policy for different privacy scenarios rather than a way of thinking about privacy rights for all situations. Healthcare, for example, is far more heavily regulated through the Healthcare Information and Privacy Protection Act (HIPPA) than the credit companies are when it comes to sensitive personal information. A website like Patients Like Me, unlike a physician, is not subject to HIPPA and individuals openly share information about their medical conditions with complete strangers. Both are venues for individuals to seek information and advice on treatment of chronic and terminal illnesses. In the doctor's office the individuals can rest assured that those handling their information will handle it in a clearly defined way and risk their careers for a HIPPA violation. Online the same people are subject to a [privacy policy](http://patientslikeme.com/about/privacy) prepared by the company that expressly states its intentions to share sensitive medical information with other individuals, violating that agreement has no consequence other than (possible) banishment from the site. The CI framework says we should apply the same policy based on the social norms of the context. That is fine, except when there exists more than one set of behaviors, as we do here.

<!-- Where do we go, then, with CI? -->
Would Nissenbaum like us to repeal HIPPA to bring hospitals into compliance with Patients Like Me, or the other way around? The former would threaten to stability and integrity of the medical industry; the latter would take away a fundamental principle to the website: that sharing is open and free. Perhaps online health advice is a new context that should allow this kind of open sharing, but even if Nissenbaum were to cede that information shared in a doctor's office is a different context than information shared on a patient support webiste, CI still runs into difficulties. If they are different simply because one is online, what does that mean for electronic medical records, or Internet enabled video-conferencing with doctors? Under which context should those data be subject? There is not a clear answer for this real public policy issue under the contextual integrity framework.

<!-- We go to harms...not Harms, bwahahahahahahahahahahahaha -->
## The end of the grand undertaking

The most compelling idea we can derive from Nissenbaum is a more basic idea that one privacy solution may not fit every privacy problem. There is a desire in Congress and other policyaking bodies (noably the European Union) to make policy in grand undertakings.Since 1995, for example, we have had one privacy policy regulating every electronic data use in the European Union regardless of who is using it or to what ends, and it seems we will continue to as Brussels attempts to revise this eighteen year-old policy with anothe broad stroke attempt at public policy.

<!-- Even in the US -->
This is less true in United States where we have many laws for different privacy problems, but it is clear that even those laws are not working. One need look no further than the failure of existing policies to know that a change is needed. Former Federal Trade Commission Director Tim Muris remarked on the failures of Graham-Leach-Bliley which he said killed "acres of trees…to produce a blizzard of barely comprehensible privacy notices" in the banking and financial services industry (Muris, 2001). These are exactly the same kind of notices that Cate highlighted five years later. "This is a statute only lawyers could love," Muris continued, "we can do better" (2001).

The problem is that Congress, though to a lesser extent than the EU, still seeks "grand undertaking" legislation—a one-to-many solution for privacy problems. Muris hinted at this in his 2001 address to the Privacy 2001 Conference in Cleveland. Regarding the need for a conprehensive online privacy act, where a lack of consensus over how to proceed along with the other related data collection practices and the lack of data about possible negative externalities from such legislation led him to the conclusion that it was "too soon to conclude that we can fashion workable legislation to accomplish the goals" of protecting online consumers. Moreover, there were existing laws that gave agencies like the FTC an immense, underultilized toolkit for privacy education, enforcement, rule modification, and prosecution. If we were to make new legislation, we should exhaust other options first, and have a clear idea of what it should do and how it should work.

## Where to go from here

<!-- FIPPS and CI are both flawed, Harms is the way forward. -->
Where to start that investigation is a tricky proposition. The FIPPs are already failing, so starting there seems counterproductive. And Nissenbaum's framework is unpredictable, and seems fraught with potential to create conflicting and confusing policy. A third way forward is the harms framework introduced earlier, sometimes also called the economic framework (especially by Posner, 1978). The balance of this paper will argue the harms framework, when paired with an agile policymaking structure, is able to overcome its own shortcomings and serve as a better guide for privacy than either FIPPS or Contextual Integrity.

<!-- A framework for understanding when to say no, or yes, to use of personal data based on potential or actual consequences of its use -->
The harms framework traces its roots back to the personal privacy theories of John Stuart Mill. Mill believed privacy was an important thing to protect because it was what allowed individuals to experiment with new ideas, new ways of living and laws interfering with that right should be made only to prevent harm from befalling individuals (Mill, _Liberty_).

Mill was particularly concerned with the adverse affects of government intervention on progress, and this view has had incredible staying power. Judge Richard Posner took a similar view calling privacy an economic problem (as it was indeed an economic interest) in 1978 when he anticipated the continued importance of information to industry. The problem is that information based industries demand disclosure of private information.

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