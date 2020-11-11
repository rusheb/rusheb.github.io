---
layout: post
title: "Protect your Crown Jewels with Conclave"
date: 2020-11-11
---

In 1671, a man named Thomas Blood almost managed to steal the Crown Jewels. 

He achieved this by befriending the keeper of the jewels, Talbot Edwards. After gaining his trust, Blood convinced Edwards to let him into the Jewel House to show the jewels to Blood and his companions. Once the thieves had been let in, they knocked Edwards unconscious and took the jewels from right under his nose! 

Why did Blood choose to steal the jewels in this way? What were his alternatives? He could have attempted to break into the Jewel House while the jewels were unattended. Alternatively, he could have waited until the jewels had to be moved, and attempted to steal them while they were being transported to their destination. In both scenarios, the jewels would have been under strong protection. It would have been nearly impossible to break into the Jewel House, and the jewels were likely to be guarded very closely while in transit. Instead, Blood took advantage of the trust he had gained to try to steal the jewels while they were most vulnerable: when the majority of their protection had been lifted.  

Data exists in one of 3 states: _at rest_ in local storage, _in transit_ between two locations, and _in use_ when it is being processed by applications. Jewels unattended in the vault are like data _at rest_, and jewels being transported to a new location can be thought of as data _in transit_. In both of these scenarios, modern encryption makes accessing the data infeasible. 

When we want a third party to do something with our data, we have to decrypt it to allow them to use it. Third party services allow us to make the most of our data by providing software and hardware that lets us process it, but this comes with associated risk. Our data, like the jewels, is most vulnerable while _in use_.

Knowing this, how can we protect data that is _in use_ while still allowing third parties to help us generate insight from it? Is there a way to leverage the power of cloud computing but protect our data from cloud providers? How can we ensure that the people using our data will not be able to misuse it in this vulnerable state? 

What if Edwards had been able to place a secure, tamperproof barrier in front of the Crown Jewels, even while they were being viewed? What if he could have kept Blood bound to his promise that he only intended to view the jewels and nothing more? 

In software, we can achieve this using secure enclaves, which create a trusted environment that is isolated from the operating system that hosts them. Enclaves can access and perform computations on data, while the data inside remains encrypted to the host operating system. We can cryptographically assert exactly what code is running inside our enclaves so we know that there will be no surprises. 

Conclave is a platform that makes it possible (and easy) to develop secure enclaves in JVM languages, providing a simple solution for protecting data in use. You can find out more at [conclave.net](https://conclave.net). 
