---
title: "Why don't you deduct to donate more?"
# permalink: /research/032024Why-dont-you-deduct.md
excerpt: 'Anecdotal evidence suggests very low rates of tax deduction for in-person donations in the field. Teaming up with a large Austrian charitable organization, we analyze their historical data and persistently document this phenomenon. To examine the reasons for this negligence of tax incentives, we first implement a representative online survey to collect beliefs on the moral perception of deduction and reasons for which people may be hesitant to deduct. The survey suggests social image concerns and a lack of information for the majority of the population as main drivers. Building on this, we run both an online and a field experiment to study the role of procedural information and social image in more detail. Our results suggest that a mere lack of information on how to deduct one’s donations cannot explain the low rates of deduction for field donations. Similarly, providing people with second-order beliefs on the moral perception of deducting did not induce a higher deduction propensity.'
# date: 2024-03-01
# venue: 'GitHub Journal of Bugs'
# paperurl: # 
# citation: #
---

#### <span style="font-size: 1.5em;">Background</span>
In 2017 Austria passed a tax-reform which shifted the administrative burden of tax deducting from the donors to the charitable organizations. An average person donating to the Austrian carol singers (Sternsingen) could reclaim 40% of the donation at a time cost of less than 1 minute. Despite this, only 0.5% of the field donors make use of tax-deduction.

#### <span style="font-size: 1.5em;">Step 0: measuring the effect of the tax reform</span>
1. Analysis of our several Austrian charities reveals that the tax-reform had little to no effect:
![Share of deductors among eligible donors](/projects/charity/Effect_tax_reform_donation_vol.png)
*Figure 1: Revenues of charities, eligible vs inelible for tax-deduction.*
2. Our partner charity has 3 sources of revenue: donations through bank-transfers, website, in-field-donations. For the first two deduction propensity is above 50%
3. Using tick-lists in the field, we measured the the-field deduction propensity to be around 0.54%, two orders of magnitude smaller than those of the other two sources.

#### <span style="font-size: 1.5em;">Step I: Representative survey (n=314)</span>
Using a representative Austrian sample we conducted a survey to uncover people's attitudes towards tax-deducting. 
Results:
- Information
    1. Only 40% of the responders are fully informed about the steps of tax-deducting.
    2. 57% of the responders think lack of information to be a main driver of low tax-deduction rates.
- Social image concerns
    1. 88% of the responders think tax deducting is morally acceptable, while only 64% of them believe that others find it also morally acceptable. This difference of 20 percentage points points towards social image concerns as a potential driver.
- Cost-benefit considerations
    1. Responders believe on average it would take around 11 minutes to tax-deduct donations, while in practice this is less than a minute.
    2. 24% of the responders suggest cost-benefit considerations as a potential driver.

#### <span style="font-size: 1.5em;">Step II: Online experiment</span>
In our online experiment (n=483), we simulate an economy. Participants are grouped into 20 people. They solve tasks to earn credits which are then taxed at a 30% rate. Participants are allowed to use their credits to donate to a charity of their choice from a list of 9 charities, 3 of which are eligible for deduction. Those who donate to eligible charities are later asked whether they would like to go through the deduction process. The effort and time required for this process is obfuscated in the control group. 

There are three treatments that differ only in the description of the game. In the control treatment, the description includes hints at a possibility of tax-deduction. In the information treatment, participants are told which charities are eligible and how the deduction process works. In the morality treatment on top of the information received in the information treatment, participants are told that 88% of responders to a recent survey find it morally acceptable to tax-deduct donations.


**Key findings**:
1. Deduction rate among donors is very high. This is very similar to the deduction rate of those who donate through the charitable organization's website.
2. Treatments have no effect on the deduction propensity.
![Share of deductors among eligible donors](/projects/charity/online_pic_1.png)
3. Morality treatment leads to higher donations in both margins.
![Share of deductors among eligible donors](/projects/charity/online_pic_2.png)
![Share of deductors among eligible donors](/projects/charity/online_pic_3.png)



#### <span style="font-size: 1.5em;">Step III: Field experiment</span>
Our field experiment took place in Gleisdorf Austria from November 23 till January 5. In the first week of December, we treated 6728 adresses. In the last week of december and first week of January, carol singers visited the households. They sang their songs and solicited donations. The identities of those who asked to tax-deduct were communicated to us via the charity organization.

Treatment included a flyer text in the form of an article in the bi-monthly issue of the parish journal. In Control, possibility of tax-deduction was mentioned. In the Information treatment, the process of tax-deduction was explained. Finally, in the Morality treatment, on top of the previous information, it was mentioned that "88% of recent survey responders found it morally acceptable to tax-deduct donactions". Treatments were randomized at the household level. 

**Main result**: Treatment has no effect and less than 0.5% of donors deduct their donations. 
![Share of deductors among eligible donors](/projects/charity/field_pic_1.png)

