# Automation

Automating common tasks in building, testing, and releasing software helps to __increase efficiency and set up a reproducible process__ that can be implemented by tool chains. We can even automate the provisioning and deployment of the virtual machines and middlewares. This __ensures repeatibility__.

Automating tasks such as integrating, build, packaging, and deployment steps will __facilitate rapid iterative development__.

While automating the most error-prone, most repetitive, and most-time consuming activites is essential.

## Good practices

Do not automate simply because you want to. __It's bad if your automation activities are driven by technical instead of business considerations__.

Automation is performed to gain fast feedback. __Efficient automation makes humans more important__ not less. Be always aware of the consequences and pitfalls of automation.

## Pitfalls of Automation

* Law of marginal costs
* Verb/noun mistake
* Paradox of automation
* Irony of automation

### Law of marginal costs

In most cases you should not automate everything. Software development needs maintenance, and enchancements are coded continuously. The same is for the automation system itself.

If something has to change in the running automation system because new requirements have emerged or changes are implements, these activities will cost time and thus money.

### Verb/noun mistake

Projects activities are often mixed up with sense and stateless deliverables. 

For example, Testing is an activity/verb, not a noun. Understanding testing as a noun is suboptimal and __may lead to a focus on meaninless artifact types__ instead of concretely and effectively testing the application. You will most probably not want to automate 100% of your tests just to have a big batch of test cases.

Moreover, a crucial part of tests cannot be automated at all, for example, exploratory testing of user interfaces.

### Paradox of Automation

The more efficient the automated system is, the more __essential human contribution__ that is needed to run the automation system.

Humans are less involved in heavily automated systems, but their __involvement becomes more critical__.

If an automated system has an error, the full system is often completely unavailable until the error is identified and fixed. Finding the error is a nontrivial task that cannot be performed by a novice engineer who is not an expert at the underlying automated baby steps.

Strong skills and experience is needed to monitor and operate a running system, and to maintain and develop the system further because requirements will change.
