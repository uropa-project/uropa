# Uropa
## Universal Record Of Processing Activities

![alt_text](images/Welcome.png "Welcome image")


# What is Uropa? 

Uropa is a standard protocol designed to help companies and their Data Protection Officers (DPOs) or Chief Privacy Officers (CPOs) to comply with the legal requirements related to privacy laws from around the world.

Uropa defines how to write and document data processing activities in a **machine readable format**.

It is modeled on the [Open API Specification](https://swagger.io/specification/).


# Why Uropa?

Technological industries are increasingly subject to data protection laws being created by more and more countries.

These laws require companies demonstrate their compliance. In particular, the [GDPR](https://gdpr-info.eu/) requires companies to maintain Records of Processing Activities (ROPA) that are an accurate reflection of how a company processes the Personally Identifying Information (PII) that it collects.

**We believe that ROPA are the cornerstone of the data protection process**. 

 
Because companies rely on static tools to maintain their ROPA (such as Excel sheet, yes we know 👁), their ROPA don’t reflect the reality of the company’s processing. 

Uropa aims to address this issue with a universal and interoperable machine-readable record of processing. 

Our goal is twofold, we want to:

 1. Empower companies to automatically assess whether their policies are properly implemented and detect anomalies whether they use a self-made or a third-party compliance tool. 
 2. Enable interoperability between compliance tools and solutions so companies can centralize their privacy solutions without useless and time consuming compatibility efforts. 


# How to Use Uropa and Who is it For?

Uropa is meant to be used by persons editing data processing records. These persons could be:



* A techy/geek DPO (Data Protection Officers, more often known as “Mr or Mrs GDPR ” within your team, wanting to document its processing activities directly in JSON — these are THE guys 👍)
* CTOs in charge of GDPR (or similar laws) compliance (we love you too ❤️)
* Developers working on a solution to help companies maintain their compliance documentation (there a lot of them, yes we see you 👀).

Depending on who you are, Uropa is going to be used in different ways. 

As DPO or CTO wanting to just document your compliance, you’ll be able to write documents following the Uropa standards. Practically speaking, this means you’ll copy-paste the structure of a processing record from our github repository into your favorite IDE or text editor and you’ll save it in a JSON file (you crazy person! 🤯) . 

This way, you are prepared for the future (Congrats! 👏). One day, when your company wants to enable the full power of this data format, you’ll be able to directly import all of your work in a global governance dedicated software solution. You’ll reuse all of the fruits of your efforts to adopt a DevRegOps approach. You will also prepare for the future team of privacy engineers to take the floor and make their work easier because they’ll link the IT systems to your processing records, so that everything related to your privacy and data protection compliance becomes stateful (🏆).

As a Developer or a CTO of a company developing a software product (especially those aiming at editing processing records), you’ll be likely to love the unlimited possibilities of export and import that Uropa offers to you. Interoperability will become real between your processing records editing software and other systems. 

Additionally, processing records contain a lot of useful information for other types of software, including those related to cybersecurity or marketing. 

As a Developer working on a homemade project for your company, you might want to automate or script some actions to complete a business workflow, be it related to privacy or not. To do so, you’ll be able to consume APIs providing information contained in processing records under a format respecting the Uropa standards.

With Uropa, you get the best of both the IT and legal worlds (🎤🎶) so you can serve your business and respect your customers’ privacy (so wonderful, isn’t it 🥲?).


# Technology and Documentation

Uropa is defined using [JSON](https://www.json.org/json-en.html). No other technology is required to use this protocol. 

All of the objects composing the processing record are detailed in the [Uropa project documentation](https://gdpr.stoplight.io/docs/uropa/c2NoOjU1NjI5MTMz-processing-record)


# Community

If you want to participate in the project, or if you’re interested in making the work a more privacy respectful place, feel free to join our [Developers and Privacy Discord Server](https://discord.gg/EVr6ptb2s6)


# Who Uropa Is Maintained By?

Uropa is an open source project initially co-created by two French startups: [Alias.dev](https://www.alias.dev/) and [Leto.legal](https://www.leto.legal/).


# License

Uropa standard is open source and may be used under the terms of the [MIT License](https://opensource.org/licenses/MIT). 
